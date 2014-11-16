Metatags
========

All about meta tags. Important meta tags are covered but not all.

##http-equiv
```
<meta http-equiv="X-Frame-Options" content="DENY" />
```
DENY – Prevents any site from framing the page 

Note: Latest specs asks to set in the HTTP header not in Meta tags

```
<meta http-equiv="refresh" content="30">
```
Refresh document every 30 seconds:

```
<meta http-equiv="x-dns-prefetch-control" content="off">
```
Turn off the DNS pre fetch

## DNS prefetch
```
<link rel="dns-prefetch" href="//www.yahoo.com" />
```
## Prefetch and prerender
```
<link rel="prefetch prerender" href="http://www.google.com" />
```
