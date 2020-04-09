# http协议

要了解http协议最好用火狐浏览器，有原生的请求头和响应头，以Get方式请求google为例：

```
Request URL:https://www.google.com/images/nav_logo299.webp
Request Method:GET
Remote Address:0.0.0.0:443
Status Code:
200
Version:HTTP/2
Referrer Policy:origin
```
request header
```
HTTP/2 200 OK
accept-ranges: bytes
content-type: image/webp
content-length: 4396
date: Thu, 09 Apr 2020 12:03:25 GMT
expires: Thu, 09 Apr 2020 12:03:25 GMT
cache-control: private, max-age=31536000
last-modified: Tue, 23 Apr 2019 01:00:00 GMT
x-content-type-options: nosniff
server: sffe
x-xss-protection: 0
alt-svc: quic=":443"; ma=2592000; v="46,43",h3-Q050=":443"; ma=2592000,h3-Q049=":443"; ma=2592000,h3-Q048=":443"; ma=2592000,h3-Q046=":443"; ma=2592000,h3-Q043=":443"; ma=2592000,h3-T050=":443"; ma=2592000
X-Firefox-Spdy: h2
```
response header
```
Host: www.google.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.12; rv:75.0) Gecko/20100101 Firefox/75.0
Accept: image/webp,*/*
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate, br
Referer: https://www.google.com/
Connection: keep-alive
Cookie: 1P_JAR=2020-04-09-12; NID=202=CLyvCfSSXhcltM7rAQ4tmNHj-zncDnyykpcoPsd6MpmvstvKQvOAewsAhifD93jxekCiV5f66RkKct2RwzNhnwhYEAsjoK19z3Dywi7NEI3k_hrL459P4VSZrhZwG11Kwq-ZBBRP1H2rTh-cnp4VScVBm7e8eYM4kklskn8oK4o; ANID=AHWqTUm6aiDbiqP7xTRsJHucSxgPZ6bN_p_5r6TbX7xg0zCJgUKSMovJqrkocifF
Cache-Control: max-age=0
TE: Trailers
If-Modified-Since: Tue, 23 Apr 2019 01:00:00 GMT
```