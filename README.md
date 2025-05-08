# Proxy Blocking WAF Rules (Cloudflare)
Cloudflare WAF rules I use to block requests from VPN/Proxy/Tor clients.

***Gets irregular updates.***

- Tested with a bunch of different VPNs such as Proton, Adguard, HMA and more. Including some free/cheap Chrome Web Store VPNs.
- Blocks requests based on the AS numbers.
- There is two VPN/Proxy blocking rules since Cloudflare has a char limit per rule.

## Why?
*Why would you prevent VPN/Proxy/Tor users to login your website?*

> Mostly security reasons of course. And for example if you got someone who is stalking your personal web page with a VPN, you can easily get rid of them.
