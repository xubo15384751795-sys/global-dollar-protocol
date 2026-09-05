# HKMA Open API diagnostic retry

```text
Task: HKMA official endpoint diagnostic (one round, then STOP)
Question: Can Interbank Liquidity / Monetary Base / HIBOR Daily be fetched with a minimal GET?
Scope version: 3.0
Timestamp: 2026-09-05T08:49:56Z
Stop reason: OFFICIAL_API_UNAVAILABLE_AFTER_DIAGNOSTIC_RETRY
Human review required: NO
```

No data invented. No third-party fill-in.

---

## Environment

```text
HTTP_PROXY=http://127.0.0.1:7897
HTTPS_PROXY=http://127.0.0.1:7897
ALL_PROXY=socks5://127.0.0.1:7897
DNS: api.hkma.gov.hk CNAME 0e03td2gqdgtitmdzm5x3akyxowyjphy.aligfwaf.com
A: 47.52.123.171
AAAA: none from getaddrinfo
TCP 443 to 47.52.123.171: succeeded (direct nc)
Local proxy 127.0.0.1:7897: up
TLS: TLSv1.2 ECDHE-RSA-AES128-GCM-SHA256
Cert: CN=api.hkma.gov.hk, issuer Hongkong Post e-Cert SSL CA 3 - 17, verify ok
```

`curl --noproxy` is unknown on this curl 8.7.1 wrapper path; direct tests used `env -u HTTP_PROXY HTTPS_PROXY ALL_PROXY ...`.

---

## Fault matrix

Minimal GET: `pagesize=1&offset=0`, connect-timeout 10, max-time 30.

| Test | Interbank Liquidity | Monetary Base | HIBOR Daily |
|---|---|---|---|
| minimal GET via proxy | HTTP 502 (`alb`), Via SLB | timeout after CONNECT (exit 28) | timeout after CONNECT (exit 28) |
| direct / unset proxy | HTTP 502 (`alb`), Via SLB | HTTP 502 (`alb`), Via SLB | HTTP 502 (`alb`), Via SLB |
| IPv4 direct | HTTP 502 | — | — |
| HTTP/1.1 direct | HTTP 502 | — | — |
| urllib, proxy env on | HTTP 502 | — | — |
| urllib, proxy env off | HTTP 502 | — | — |

Liquidity is the only endpoint that consistently returns an HTTP body. Origin is 502, not a client timeout.

---

## 502 headers (direct, Interbank Liquidity)

```text
HTTP/1.1 502 Bad Gateway
Date: Sat, 05 Sep 2026 08:49:56 GMT
Content-Type: text/html
Content-Length: 164
Connection: keep-alive
Set-Cookie: acw_tc=...;path=/;HttpOnly;Max-Age=1800
Via: HTTP/1.1 SLB.143
Strict-Transport-Security: max-age=31536000
```

Body:

```html
<html>
<head><title>502 Bad Gateway</title></head>
<body bgcolor="white">
<center><h1>502 Bad Gateway</h1></center>
<hr><center>alb</center>
</body>
</html>
```

`acw_tc` is Aliyun WAF. `alb` is the gateway that generated 502. Client reached the HKMA API edge; the application behind it did not.

---

## Branch result

```text
DNS: OK
TCP/TLS: OK
Direct vs proxy: both reach HTTP; proxy adds timeouts on two endpoints
IPv4: same 502
urllib vs curl: same 502
Request size: pagesize=1, not a bulk-history problem
```

Classification: HKMA/WAF/ALB origin 502, not local requester bug.

---

## Stop

```text
OFFICIAL_API_UNAVAILABLE_AFTER_DIAGNOSTIC_RETRY
```

Do not estimate HIBOR or Aggregate Balance. Keep using `data/indicators/fx_daily.csv` (Yahoo USD/HKD) until this origin returns 200.
