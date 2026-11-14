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

**Evidences of Footprinting and Scanning**  
<img width="953" height="533" alt="Screenshot 2026-11-13 082920" src="https://github.com/user-attachments/assets/4bb94b01-c217-437f-8677-49b7fd63f4ab" />  
<img width="953" height="220" alt="Screenshot 2026-11-13 085439" src="https://github.com/user-attachments/assets/29fbf9ba-bf49-46e9-bb0a-d9c4a0cad602" />  
<img width="953" height="234" alt="Screenshot 2026-11-13 090341" src="https://github.com/user-attachments/assets/1e0e2e8f-2e0a-432e-b35c-c2b8c1779807" />  
<img width="953" height="295" alt="Screenshot 2026-11-13 090721" src="https://github.com/user-attachments/assets/47ab31bb-9923-4207-821f-128b44e038ee" />  
<img width="953" height="344" alt="Screenshot 2026-11-13 091043" src="https://github.com/user-attachments/assets/3fabfc5e-1c55-4ff7-8346-cfa02f8c0fd3" />  
<img width="953" height="385" alt="Screenshot 2026-11-13 091632" src="https://github.com/user-attachments/assets/48fe0227-01f0-4df8-bdfa-f63eaf859627" />  
<img width="953" height="533" alt="Screenshot 2026-11-13 172652" src="https://github.com/user-attachments/assets/481f9c2a-fdb3-451b-bff8-c7678503a0e3" />  
<img width="953" height="533" alt="Screenshot 2026-11-14 142315" src="https://github.com/user-attachments/assets/54fe3784-525b-49ba-a7e4-dd31b146d579" />







