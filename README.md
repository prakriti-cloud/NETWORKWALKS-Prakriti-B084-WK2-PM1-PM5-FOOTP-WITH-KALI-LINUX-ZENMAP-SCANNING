**📌 Project Overview**  
This project focuses on passive and active footprinting alongside local network discovery using Kali Linux and Zenmap.  
The purpose of the lab is to gather publicly available domain intelligence, fingerprint web infrastructure, and map active hosts across a local subnet without disrupting network operations.  
By combining command-line OSINT utilities with graphical network scanning, the workflow demonstrates how security analysts build complete visibility over both external web targets and internal local networks.

**🎯 Objectives**  
The main objectives of this project are to:  
- Gather domain registration records, registrar details, and name servers using whois.  
- Fingerprint target web servers, CMS platforms, and underlying frameworks with whatweb.  
- Resolve public IPv4 addresses and inspect raw HTTP response headers via nslookup and curl.  
- Detect Web Application Firewalls (WAFs) protecting target domains using wafw00f.  
- Enumerate DNS records (SOA, NS, MX, TXT, SRV) and verify DNSSEC configuration with dnsrecon.  
- Identify local network interfaces, IPv4 addresses, and CIDR subnet ranges using ipconfig.  
- Discover live hosts and analyze hardware MAC address vendors on a /24 subnet using Zenmap (nmap -sn).  
- Export a visual network topology map to document host-to-gateway relationships.

**🛡️ Usage & Practical Applications**  
The techniques and tools practiced in this lab provide foundational reconnaissance skills for authorized security assessments and network administration.  
They can be applied to activities such as:  
- External attack surface mapping and OSINT gathering  
- DNS infrastructure auditing and misconfiguration checks  
- Web technology stack and WAF identification  
- Local subnet calculation and CIDR network scoping  
- Active device discovery and unauthorized host detection  
- Hardware MAC address OUI and vendor fingerprinting  
- Visual network topology documentation  
