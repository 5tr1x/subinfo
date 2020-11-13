<h2>Description</h2>

Discovers subdomains, filters live hosts, and checks for possible subdomain takeover

<h2>Requirements</h2>

[subfinder](https://github.com/projectdiscovery/subfinder)

[assetfinder](https://github.com/tomnomnom/assetfinder)

[amass](https://github.com/OWASP/Amass)

[subjack](https://github.com/haccer/subjack)

[httprobe](https://github.com/tomnomnom/httprobe)

<h2>Features</h2>

- takes list of domains as input and combines results of 3 subdomain enumeration tools
- tests for possible subdomain takeover 
- identifies live hosts
- saves output of all subdomains and live subdomains

<h2>Usage</h2>

`subinfo <domain list>`
