# Proxy Blocking WAF Rules (Cloudflare)
Cloudflare WAF rules to detect control VPN/Proxy/Tor request.

**Gets irregular updates.**
 
- Common VPN hostings are fully blocked. Like OVH, DIGITAL-OCEAN and many others. Also detects some bots, crawlers, bad vulnerability scanners too.
- Blocks requests based on the AS numbers.
- Tested with a bunch of different VPNs such as Proton, Adguard, HMA and more. Including some free/cheap Chrome Web Store VPNs.

> [!NOTE]
> There is two VPN/Proxy blocking rules since Cloudflare has a char limit of 4096 per rule. Make sure you don't have more than 2-3 rules in your current WAF configuration if you're a Cloudflare Free user.

## Contribute
- Some VPNs are not being detected? Contribute to this repository! Add the AS numbers you find to both [block_vpns2](/block_vpns2) and [asn_list](/asn_list) and create a pull request (please also add the VPN names to description). Thanks for your support!

## Used in this repository

- [bad-asn-list](https://github.com/brianhama/bad-asn-list/) by [brianhama](https://github.com/brianhama/)
