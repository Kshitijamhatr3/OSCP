# OSCP 
💗 Welcome to the OSCP (Offensive Security Certified Professional) Preparation Resources repository! This repository is designed to be a comprehensive and curated collection of resources from multiple sources, aimed at helping you prepare effectively for the OSCP exam. Whether you are just starting your OSCP journey or looking to refine your skills, this repository contains valuable materials to guide you through every step of the process. 💗

## ∎∎∎ Topics ∎∎∎
### 1) Basics
### 2) Information Gathering
#### 2.1 Passive Information Gathering
##### 2.1.1 OSINT
    * OSINT framework ➨ https://osintframework.com/
    * Google Dorking ➨ https://github.com/Kshitijamhatr3/google-dork-cheatsheet
    * Whoislookup ➨ https://www.whois.com/whois/
    * Nslookup ➨ https://shorturl.at/9pFZn
    * Shodan ➨ https://www.shodan.io/
    * Maltego ➨ https://www.maltego.com/
    * Wayback machine ➨ https://web.archive.org/
##### 2.1.2 Social Media Recon
    * Social Media Platform
    * Social Media Mining Tools ➨ Maltego, Social-Engineer Toolkit (SET)
##### 2.1.3 Domain Name and WHOIS Information
    * Subdomain finder ➨ https://subdomainfinder.c99.nl/
    * Subdomain enumeration ➨ https://dnsdumpster.com/
    * Subdomain enumeration (based on certificates) ➨ https://crt.sh/
    * DNS lookup tool ➨ https://mxtoolbox.com/DnsLookup.aspx
    * Whois lookup ➨ https://www.whois.com/whois/ (registrar, registration date, and contact details )
    * Nslookup ➨ nslookup is a command-line tool to retrieve a domain's information, including its IP address and DNS record.
    ✍️ Subdomain Enumeration : https://www.ceeyu.io/resources/blog/subdomain-enumeration-tools-and-techniques
    
##### 2.1.4 Metadata Analysis
    * FOCA: A tool specifically designed for extracting metadata from online documents ➨ https://github.com/ElevenPaths/FOCA
    * Metadata ➨ https://www.metadata2go.com
##### 2.1.5 Email Harvesting
    * theHarvester: A tool designed for gathering email addresses and other information from public sources. ➨ https://github.com/laramies/theHarvester
    * Hunter.io: A web-based tool for finding email addresses based on domain names. ➨ https://hunter.io/
##### 2.1.6 Public Records and Database Searches
    * Pipl: A people search engine that aggregates data from various sources. ➨ https://pipl.com/
    * Public record database ➨ https://www.searchpublicrecords.com
##### 2.1.7 SSL/TLS Certificate Analysis
    * Censys: A search engine for finding and analyzing SSL certificates and also for searching HOSTS. ➨ https://search.censys.io/
    * Qualys SSL Labs: Multiple SSL related tools. ➨ https://www.ssllabs.com/projects/index.html
##### 2.1.8 Code Repository Monitoring 
    * GitHub Search ➨ https://github.com/search
    * Pastebin ➨ https://pastebin.com/
##### 2.1.9 Threat Intelligence Platforms
    * Threat Crowd: A search engine for discovering and sharing threat intelligence. ➨ ci-www.threatcrowd.org
    * Virustotal: A tool for analyzing suspicious files and URLs to detect malware and other threats. ➨ https://www.virustotal.com/gui/home/upload
    
#### 2.2 Active Information Gathering
##### 2.2.1 Network Scanning
    * Topics:
    
      - Understanding TCP/IP protocols
      - ICMP scanning
      - TCP/UDP port scanning
      - Service version detection
      - OS fingerprinting
      
    * Tools:
    
      - Nmap: Used for network discovery and security auditing.
      - Zenmap: GUI version of Nmap.
      - Unicornscan: A fast network scanning tool.
      
##### 2.2.2 Vulnerability Scanning
    * Topics:
    
      - Common vulnerabilities and exposures (CVE)
      - Vulnerability databases
      - Scanning methodologies

    * Tools:
    
      - OpenVAS: A full-featured vulnerability scanner.
      - Nessus: A popular commercial vulnerability scanner.
      - Nikto: A web server scanner.
      - Burpsuite: 
      
##### 2.2.3 Banner Grabbing
    * Topics:
      - Understanding service banners.
      - Using banners to identify service versions
      
    * Tools:
      - Telnet/Netcat: For manual banner grabbing.
        Example: nc <target_ip> <port> (Connects to a service and grabs the banner)
      - Nmap: Can also be used to grab banners.
      
##### 2.2.4 Wireless Network Scanning
    * Topics:
      - Wireless protocols (802.11 standards)
      - Wireless encryption and authentication methods

    * Tools:
      - Aircrack-ng: A suite for wireless network auditing.
      - Kismet: A wireless network detector and sniffer.
      
##### 2.2.5 Web Application Testing
    *  Topics:
       - Understanding web technologies (HTTP/HTTPS, HTML, SQL, etc.)
       - Common web vulnerabilities (SQL injection, XSS, etc.)

    * Tools:
      - Burp Suite: A comprehensive web application security testing tool.
      - OWASP ZAP: An open-source web application security scanner.
      - Wapiti: A web application vulnerability scanner.
      
##### 2.2.6 Password Cracking
    * Topics:
      - Brute force and dictionary attacks
      - Understanding password hashing mechanisms

    * Tools:
      - Hydra: A parallelized login cracker.
      - John the Ripper: A fast password cracker.
      - Medusa: A speedy, parallel, and modular login brute-forcer.
      
##### 2.2.7 Social Engineering
    * Topics:
      - Phishing techniques.
      - Pretexting and impersonation

    * Tools:
      - Social-Engineer Toolkit (SET): A framework for automating social engineering attacks.
      - Phishing Frameworks: Such as Gophish.
      
##### 2.2.8 Exploit Research and Development
    * Topics:
      - Understanding exploit frameworks.
      - Writing custom exploits
      
    * Tools:
      - Metasploit Framework: A widely used penetration testing framework.
      - Exploit-DB: A database of public exploits and vulnerable software.
      
##### 2.2.9 Network Traffic Analysis
    * Topics:
      - Capturing and analyzing network packets
      - Protocol analysis
    * Tools:
      - Wireshark: A network protocol analyzer.
      - Tcpdump: A command-line packet analyzer
      
##### 2.2.10 Service Enumeration
    * Topics:
      - Enumerating services on a network.
      - Identifying running services and their configurations.
   
    * Tools:
      - Nmap: For service enumeration.
      - Netcat: For manual service testing.
      - Enum4linux: For enumerating information from Windows and Samba systems.
    
### 3) Vulnerability Scanning

#### 3.1 Network Vulnerability Scanning

##### 3.1.1 Nessus
    * Official documentation: https://docs.tenable.com/nessus/Content/GettingStarted.htm
##### 3.1.2 OpenVAS
    * Beginner tutorial: https://infosecwriteups.com/introduction-to-openvas-a-vulnerability-scanner-cd5bf830e2fe
    * Beginner tutorial: https://hackertarget.com/openvas-tutorial-tips/
##### 3.1.3 Nmap
##### 3.1.4 QualysGuard
##### 3.1.5 Metasploit Framework
##### 3.1.6 Netcat

#### 3.2 Website Vulnerability Scanning
##### 3.2.1 Burp Suite
##### 3.2.2 OWASP ZAP
##### 3.2.3 Acunetix
##### 3.2.4 Nikto
##### 3.2.5 Arachni
##### 3.2.6 Wapiti

### 4) Introduction to Web Applications
### 5) Common Web Application Attacks
### 6) SQL Injection Attacks
### 7) Client-Side Attacks
### 8) Locating Public Exploits
### 9) Fixing Exploits
### 10) Antivirus Evasion
### 11) Password Attacks
### 12) Windows Privilege Escalation
### 13) Linux Privilege Escalation
### 14) Port Redirection and SSH Tunneling
### 15) Advanced Tunneling
### 16) The MetasploitFramework
### 17) Active Directory

## ∎∎∎ My Resources( General topics) ∎∎∎
### 1) Active directory
  * 1.1 Active Directory training ➨ https://youtu.be/sI9pbhasVSA?si=MFzveqg3RDh97jMC
  * 1.2 Active Directory course ➨ https://www.serveracademy.com/blog/active-directory-tutorial-for-beginners/
### 2) Authentication
  * 2.1 Authentication Bypass (OTP) ➨ https://youtu.be/LYDTnkCurU0?si=2KzClFCmHvck6dhG
  * 2.2 Kerberos Authentication explained ➨ https://youtu.be/5N242XcKAsM?si=DACMwl6hVpFCANXI
### 3) Web Application
  * 3.1 Web Application Architecture ➨ https://www.youtube.com/watch?v=d1Gd-MGaleE&list=PLUU3EzfPr915ebZONvUVHKm8Bls6D7EgA
### 4) Roadmap 
 * 4.1 All courses roadmap ➨ https://roadmap.sh/
