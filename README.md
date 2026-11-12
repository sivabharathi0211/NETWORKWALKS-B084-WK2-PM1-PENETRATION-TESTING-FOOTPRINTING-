🔍 Penetration Testing – Footprinting & Reconnaissance

📌 About the Project

This project demonstrates the footprinting and reconnaissance phase of penetration testing using commonly used cybersecurity tools in Kali Linux.

Footprinting is an essential initial stage of penetration testing that involves collecting information about a target domain, website, DNS infrastructure, and web server. This project explores different command-line tools to understand how security professionals gather and analyze publicly available information before conducting further security assessments.

🎯 Objectives

- Understand the fundamentals of footprinting and reconnaissance.
- Gather domain registration and DNS information.
- Identify website technologies and server details.
- Analyze HTTP response headers and status codes.
- Identify Web Application Firewall (WAF) technologies.
- Develop practical experience with Kali Linux tools.

🛠️ Tools & Technologies

1. WHOIS

Used to collect domain registration information, including registrar details, domain creation and expiration dates, and nameserver information.

Command:

whois networkwalks.com<img 
<img width="1366" height="643" alt="1000160885" src="https://github.com/user-attachments/assets/35483170-7b4a-4cd3-8fee-a76520b57199" />


2. WhatWeb

A web technology fingerprinting tool used to identify CMS platforms, web servers, frameworks, and technologies used by a website.

Command:

whatweb networkwalks.com

<img width="1600" height="665" alt="1000160886" src="https://github.com/user-attachments/assets/c0b0f761-888d-4cf5-9b33-5872e3a3b376" />

3. NSLOOKUP

A DNS lookup utility used to identify domain IP addresses and retrieve DNS records.

Commands:

nslookup networkwalks.com

<img width="1366" height="643" alt="1000160887" src="https://github.com/user-attachments/assets/70cdf4ad-e10b-428f-84ab-ea3c27262fb1" />

4. cURL

A command-line utility used to communicate with web servers and inspect HTTP responses, headers, and website connectivity.

Commands:

curl -I networkwalks.com

<img width="1366" height="643" alt="1000160888" src="https://github.com/user-attachments/assets/b69d100c-d82b-4c5c-a498-9473cde92152" />


5. WAFW00F

A Web Application Firewall detection tool used to identify whether a website is protected by a WAF and determine its possible provider.

Command:

wafw00f networkwalks.com

<img width="1366" height="643" alt="1000160889" src="https://github.com/user-attachments/assets/e73ca236-eea4-42b0-9811-a86d0c44c890" />


6. Dns recon

A DNS reconnaissance tool used to enumerate DNS records, discover subdomains, and check for potential DNS misconfigurations.

Command:

dnsrecon -d networkwalks.com

<img width="1366" height="643" alt="1000160890" src="https://github.com/user-attachments/assets/0167f597-867d-4df6-8a0b-c7a26893bb3c" />


🛠️ Tools & Their Uses

| Tool     | Usage                                    |
| -------- | ---------------------------------------- |
| WHOIS    | Domain information gathering.            |
| WhatWeb  | Website technology identification.       |
| NSLOOKUP | DNS and IP address lookup.               |
| DNSRecon | DNS enumeration and subdomain discovery. |
| cURL     | HTTP request and header analysis.        |
| WAFW00F  | Web Application Firewall detection.      |

🔄 Practical Workflow

1. Domain Information Gathering: Use WHOIS to collect domain registration details.
2. DNS Enumeration: Use NSLOOKUP and DNSRecon to identify DNS records and related information.
3. Technology Fingerprinting: Use WhatWeb to identify website technologies.
4. HTTP Analysis: Use cURL to inspect HTTP headers and server responses.
5. WAF Detection: Use WAFW00F to identify possible Web Application Firewall protection.

## 🔍 Footprinting – Findings & Security Analysis

| ID | Finding | Evidence | Security Relevance | Risk |
|---|---|---|---|---|
| F-01 | Domain Information | WHOIS | Supports public domain profiling | 🟢 Low |
| F-02 | Web Technology Information | WhatWeb | Helps identify website technologies | 🟠 Medium |
| F-03 | DNS/IP Information | NSLOOKUP | Helps identify network information | 🟢 Low |
| F-04 | HTTP Technical Information | cURL | Helps analyze HTTP headers and responses | 🟢 Low |
| F-05 | WAF Information | WAFW00F | Reveals defensive technology | 🟢 Low |
| F-06 | DNS Infrastructure Information | DNSRecon | Helps build an infrastructure profile | 🟠 Medium |

📚 Key Learning Outcomes

- Gained hands-on experience with footprinting and reconnaissance tools.
- Understood domain registration and DNS enumeration techniques.
- Learned website technology fingerprinting.
- Practiced HTTP header and response analysis.
- Explored Web Application Firewall detection.
- Improved practical command-line skills in Kali Linux.

⚠️ Disclaimer

This project is developed strictly for educational and ethical cybersecurity learning purposes. All tools and techniques must be used only on systems, domains, and networks for which explicit authorization has been obtained.

👨‍💻 Author

Siva Bharathi R - Cybersecurity intern B084
