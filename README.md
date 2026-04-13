# eWPTv2 (eLearnSecurity Web Penetration Tester) - Complete Structure with TryHackMe & PortSwigger Labs

> **Purpose:** Comprehensive study guide mapping every eWPT video lesson with relevant TryHackMe rooms and PortSwigger labs for hands-on practice and exam preparation.
> **Total Labs Available:** ~1275 TryHackMe rooms + ~300 PortSwigger labs (~1575 total labs)
> **Estimated Study Time:** 120-150 hours (video + labs)
> **Structure:** Shows ALL video lessons individually (no abbreviations)

---

## Complete eWPT Course Structure with Integrated Labs

```
eWPT/
│
├─── [ ] Section 1: Introduction
│    └── [ ] 1.1 - Introduction
│         └─── [ ] TryHackMe Practice Labs:
│              └── [ ] Foundational Knowledge:
│                   ├── [ ] Starting Out In Cyber Sec
│                   ├── [ ] Pentesting Fundamentals
│                   ├── [ ] Principles of Security
│                   └── [ ] Security Awareness
│
├─── [ ] Section 2: Introduction to Web App Security Testing
│    │
│    ├─── [ ] 2.1 Welcome & Course Introduction
│    │    ├── [ ] 2.1.1 - Course Introduction
│    │    └─── [ ] Labs: Course Basics (foundational)
│    │
│    ├─── [ ] 2.2 Overview - Introduction to Web App Security Testing
│    │    ├── [ ] 2.2.1 - Introduction To Web Application Security
│    │    ├── [ ] 2.2.2 - Web Application Security Testing
│    │    ├── [ ] 2.2.3 - Common Web Application Threats & Risks
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├─── [ ] Web Security Fundamentals:
│    │         │    ├── [ ] Web Security Essentials
│    │         │    ├── [ ] Web Application Security
│    │         │    ├── [ ] Web Hacking Fundamentals
│    │         │    └── [ ] Intro to Web Hacking
│    │         │
│    │         └─── [ ] OWASP & Standards:
│    │              ├── [ ] OWASP Top 10 2025: Application Design Flaws
│    │              ├── [ ] OWASP Top 10 2025: Insecure Data Handling
│    │              ├── [ ] OWASP Top 10 2025: IAAA Failures
│    │              ├── [ ] OWASP API Security Top 10 - 1
│    │              ├── [ ] OWASP API Security Top 10 - 2
│    │              └── [ ] OWASP Broken Access Control
│    │
│    ├─── [ ] 2.3 Architecture & Components
│    │    ├── [ ] 2.3.1 - Web Application Architecture
│    │    ├── [ ] 2.3.2 - Web Application Technologies - Part 1
│    │    ├── [ ] 2.3.3 - Web Application Technologies - Part 2
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├─── [ ] Web Architecture:
│    │         │    ├── [ ] How the Web Works
│    │         │    ├── [ ] Protocols and Servers
│    │         │    ├── [ ] Protocols and Servers 2
│    │         │    ├── [ ] Web Application Basics
│    │         │    └── [ ] Walking An Application
│    │         │
│    │         └─── [ ] Technologies:
│    │              ├── [ ] HTTP in Detail
│    │              ├── [ ] Packets & Frames
│    │              ├── [ ] Network Core Protocols
│    │              └── [ ] Networking Essentials
│    │
│    ├─── [ ] 2.4 Fundamentals - HTTP Protocol Fundamentals
│    │    ├── [ ] 2.4.1 - Introduction To Http
│    │    ├── [ ] 2.4.2 - Http Requests - Part 1
│    │    ├── [ ] 2.4.3 - Http Requests - Part 2
│    │    ├── [ ] 2.4.4 - Http Responses
│    │    ├── [ ] 2.4.5 - Http Basics Lab - Part 1
│    │    ├── [ ] 2.4.6 - Http Basics Lab - Part 2
│    │    ├── [ ] 2.4.7 - Https
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├─── [ ] HTTP Fundamentals:
│    │         │    ├── [ ] How the Web Works
│    │         │    ├── [ ] HTTP in Detail
│    │         │    ├── [ ] HTTP Browser Desync
│    │         │    ├── [ ] Packets & Frames
│    │         │    └── [ ] HTTP Request Smuggling
│    │         │
│    │         ├─── [ ] HTTPS & Encryption:
│    │         │    ├── [ ] Encryption - Crypto 101
│    │         │    ├── [ ] Cryptography Basics
│    │         │    ├── [ ] Introduction to Cryptography
│    │         │    ├── [ ] Cryptography for Dummies
│    │         │    ├── [ ] Hashing Basics
│    │         │    ├── [ ] Public Key Cryptography Basics
│    │         │    ├── [ ] Public Key Infrastructure
│    │         │    └── [ ] JWT Security
│    │         │
│    │         └─── [ ] PortSwigger Labs:
│    │              ├── [ ] HTTP request smuggling, basic CL.TE vulnerability
│    │              ├── [ ] HTTP request smuggling, basic TE.CL vulnerability
│    │              └── [ ] HTTP/2 request smuggling via CRLF injection
│    │
│    ├─── [ ] 2.5 Testing Lifecycle
│    │    ├── [ ] 2.5.1 - Web App Pentesting Methodology
│    │    ├── [ ] 2.5.2 - Owasp Top 10
│    │    ├── [ ] 2.5.3 - Owasp Top 10 - Part 2
│    │    ├── [ ] 2.5.4 - Owasp Top 10 - Part 3
│    │    ├── [ ] 2.5.5 - Pre-Engagement Phase
│    │    ├── [ ] 2.5.6 - Documentation Phase
│    │    ├── [ ] 2.5.7 - Documentation Phase - Part 2
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├─── [ ] Methodology:
│    │         │    ├── [ ] Pentesting Fundamentals
│    │         │    ├── [ ] Threat Modelling
│    │         │    └── [ ] Security Engineer Intro
│    │         │
│    │         └─── [ ] OWASP:
│    │              ├── [ ] OWASP Top 10 2025: Application Design Flaws
│    │              ├── [ ] OWASP Top 10 2025: Insecure Data Handling
│    │              ├── [ ] OWASP Top 10 2025: IAAA Failures
│    │              └── [ ] Vulnerabilities 101
│
├─── [ ] Section 3: Information Gathering
│    │
│    ├─── [ ] 3.1 Web Enumeration & Information Gathering
│    │    ├── [ ] 3.1.1 - Introduction
│    │    ├── [ ] 3.1.2 - OWASP Information Gathering
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├─── [ ] General Enumeration:
│    │         │    ├── [ ] Web Enumeration
│    │         │    ├── [ ] Web Attack Forensics - Drone Alone
│    │         │    ├── [ ] Shodan.io
│    │         │    ├── [ ] Passive Reconnaissance
│    │         │    └── [ ] Intro to Web Hacking
│    │         │
│    │         └─── [ ] PortSwigger Labs:
│    │              ├── [ ] Discovering vulnerabilities quickly with targeted scanning
│    │              └── [ ] Scanning non-standard data structures
│    │
│    ├─── [ ] 3.2 Finding Ownership & IP Addresses
│    │    ├── [ ] 3.2.1 - Whois
│    │    ├── [ ] 3.2.2 - Web Recon
│    │    ├── [ ] 3.2.3 - Passive Recon
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Passive Reconnaissance
│    │         ├── [ ] Shodan.io
│    │         ├── [ ] Search Skills
│    │         └── [ ] Searchlight - IMINT
│    │
│    ├─── [ ] 3.3 Reviewing Webserver Metafiles for Information Leakage
│    │    ├── [ ] 3.3.1 - Review Metafiles
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Web Application Basics
│    │         ├── [ ] Walking An Application
│    │         └── [ ] Source Code Analysis
│    │
│    ├─── [ ] 3.4 Search Engine Discovery
│    │    ├── [ ] 3.4.1 - Google Dorks
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Google Dorking
│    │         ├── [ ] Passive Reconnaissance
│    │         └── [ ] Web Enumeration
│    │
│    ├─── [ ] 3.5 Web App Fingerprinting
│    │    ├── [ ] 3.5.1 - Web Fingerprinting
│    │    ├── [ ] 3.5.2 - WAF Detection
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Web Application Basics
│    │         ├── [ ] Web Hacking Fundamentals
│    │         └── [ ] WAF: Introduction
│    │
│    ├─── [ ] 3.6 Source Code Analysis
│    │    ├── [ ] 3.6.1 - Copy Source
│    │    ├── [ ] 3.6.2 - Web Analysis
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Walking An Application
│    │         ├── [ ] Content Discovery
│    │         └── [ ] Web Enumeration
│    │
│    ├─── [ ] 3.7 Website Crawling & Spidering
│    │    ├── [ ] 3.7.1 - Passive Crawling
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Passive Crawling with Burp Suite
│    │         ├── [ ] Burp Suite: The Basics
│    │         └── [ ] Introduction to OWASP ZAP
│    │
│    ├─── [ ] 3.8 Web Servers
│    │    ├── [ ] 3.8.1 - Web Recon
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Network Services 2
│    │         ├── [ ] Network Discovery Detection
│    │         └── [ ] Vulnerability Scanner Overview
│    │
│    ├─── [ ] 3.9 DNS Enumeration
│    │    ├── [ ] 3.9.1 - Dns Zone Transfers
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] DNS Manipulation
│    │         ├── [ ] DNS in Detail
│    │         └── [ ] Subdomain Enumeration
│    │
│    ├─── [ ] 3.10 Subdomains
│    │    ├── [ ] 3.10.1 - Subdomain Enumeration
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Subdomain Enumeration
│    │         ├── [ ] Passive Reconnaissance
│    │         └── [ ] Web Enumeration
│    │
│    ├─── [ ] 3.11 Web Server Vulnerability Scanning
│    │    ├── [ ] 3.11.1 - Web Scanning
│    │    ├── [ ] 3.11.2 - Scanning Web Application with Nikto
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Vulnerability Scanner Overview
│    │         ├── [ ] Scanning Web Application with Nikto
│    │         ├── [ ] Introduction to OWASP ZAP
│    │         └── [ ] Scanning Web Application with ZAProxy
│    │
│    ├─── [ ] 3.12 File & Directory Enumeration
│    │    ├── [ ] 3.12.1 - File Enumeration
│    │    ├── [ ] 3.12.2 - Directory Enumeration with Gobuster
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Content Discovery
│    │         ├── [ ] Directory (path discovery)
│    │         ├── [ ] ffuf
│    │         └── [ ] Gobuster: The Basics
│    │
│    └─── [ ] 3.13 Automated Recon Frameworks
│         ├── [ ] 3.13.1 - Automated Frameworks
│         │
│         └─── [ ] TryHackMe Practice Labs:
│              ├── [ ] Burp Suite: The Basics
│              ├── [ ] Introduction to OWASP ZAP
│              └── [ ] Web Application Basics
│
├─── [ ] Section 4: Web Proxies
│    │
│    ├─── [ ] 4.1 Web Proxies Introduction
│    │    ├── [ ] 4.1.1 - Introduction To Web Proxies
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Burp Suite: The Basics
│    │         └── [ ] Introduction to OWASP ZAP
│    │
│    ├─── [ ] 4.2 Burp Suite
│    │    ├── [ ] 4.2.1 - Introduction To Burp Suite
│    │    ├── [ ] 4.2.2 - Configuring The Burp Proxy
│    │    ├── [ ] 4.2.3 - Burp Suite Dashboard & UI
│    │    ├── [ ] 4.2.4 - Burp Suite Target & Scope
│    │    ├── [ ] 4.2.5 - Passive Crawling With Burp Suite
│    │    ├── [ ] 4.2.6 - Passive Crawling with Burp Suite (Lab)
│    │    ├── [ ] 4.2.7 - Burp Suite Intruder
│    │    ├── [ ] 4.2.8 - Directory Enumeration with Burp Suite
│    │    ├── [ ] 4.2.9 - Attacking Basic Auth With Intruder & Decoder
│    │    ├── [ ] 4.2.10 - Attacking Basic Auth with Burp Suite (Lab)
│    │    ├── [ ] 4.2.11 - Burp Suite Repeater
│    │    ├── [ ] 4.2.12 - Vulnerable Online Calculator - Code Injection
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├─── [ ] Burp Suite Fundamentals:
│    │         │    ├── [ ] Burp Suite: The Basics
│    │         │    ├── [ ] Burp Suite: Intruder
│    │         │    ├── [ ] Burp Suite: Repeater
│    │         │    └── [ ] Burp Suite: Other Modules
│    │         │
│    │         ├─── [ ] Burp Suite Labs:
│    │         │    ├── [ ] Passive Crawling with Burp Suite
│    │         │    ├── [ ] Directory Enumeration with Burp Suite
│    │         │    ├── [ ] Attacking Basic Auth with Burp Suite
│    │         │    └── [ ] Custom Tooling using Burp
│    │         │
│    │         └─── [ ] PortSwigger Labs:
│    │              ├── [ ] Basic SSRF against the local server
│    │              ├── [ ] Basic SSRF against another back-end system
│    │              └── [ ] HTTP request smuggling, confirming CL.TE
│    │
│    └─── [ ] 4.3 OWASP ZAP
│         ├── [ ] 4.3.1 - Introduction To Owasp Zap
│         ├── [ ] 4.3.2 - Owasp Zap Dashboard & UI
│         ├── [ ] 4.3.3 - Configuring The Owasp Zap Proxy
│         ├── [ ] 4.3.4 - Owasp Zap Context & Scope
│         ├── [ ] 4.3.5 - Directory Enumeration With Owasp Zap
│         ├── [ ] 4.3.6 - Directory Enumeration with ZAProxy (Lab)
│         ├── [ ] 4.3.7 - Web App Scanning With Owasp Zap
│         ├── [ ] 4.3.8 - Scanning Web Application with ZAProxy (Lab)
│         ├── [ ] 4.3.9 - Spidering With Owasp Zap
│         ├── [ ] 4.3.10 - Active Crawling with ZAProxy (Lab)
│         ├── [ ] 4.3.11 - Attacking Http Login Forms With Owasp Zap
│         ├── [ ] 4.3.12 - Attacking HTTP Login Form with ZAProxy (Lab)
│         │
│         └─── [ ] TryHackMe Practice Labs:
│              ├── [ ] Introduction to OWASP ZAP
│              ├── [ ] OWASP ZAP
│              ├── [ ] Scanning Web Application with ZAProxy
│              ├── [ ] Directory Enumeration with ZAProxy
│              └── [ ] Active Crawling with ZAProxy
│
├─── [ ] Section 5: Cross-Site Scripting (XSS)
│    │
│    ├─── [ ] 5.1 Introduction to XSS Attacks
│    │    ├── [ ] 5.1.1 - Introduction
│    │    ├── [ ] 5.1.2 - Javascript Primer
│    │    ├── [ ] 5.1.3 - Analysis
│    │    ├── [ ] 5.1.4 - XSS: Cross-Site Scripting Attacks
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] XSS (Cross-Site Scripting)
│    │         ├── [ ] Intro to Cross-site Scripting
│    │         ├── [ ] JavaScript Primer (Web Fundamentals)
│    │         └── [ ] Web Hacking Fundamentals
│    │
│    ├─── [ ] 5.2 Reflected XSS
│    │    ├── [ ] 5.2.1 - Introduction To Reflected Xss
│    │    ├── [ ] 5.2.2 - Reflected XSS
│    │    ├── [ ] 5.2.3 - Exploiting Reflected Xss Vulnerabilities
│    │    ├── [ ] 5.2.4 - WP Relevanssi plugin XSS
│    │    ├── [ ] 5.2.5 - Cookie Stealing Via Reflected Xss
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] XSS (Cross-Site Scripting)
│    │         ├── [ ] XSS - Merry XSSMas
│    │         ├── [ ] Intro to Cross-site Scripting
│    │         └── [ ] Advanced XSS (custom payloads)
│    │
│    ├─── [ ] 5.3 Stored XSS
│    │    ├── [ ] 5.3.1 - Introduction To Stored Xss
│    │    ├── [ ] 5.3.2 - ApPHP MicroBlog
│    │    ├── [ ] 5.3.3 - Exploiting Stored Xss Vulnerabilities In
│    │    ├── [ ] 5.3.4 - MyBB Downloads Plugin
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] XSS (Cross-Site Scripting)
│    │         ├── [ ] OWASP Juice Shop (Stored XSS section)
│    │         ├── [ ] OWASP Mutillidae II
│    │         └── [ ] Web Application Exploitation
│    │
│    ├─── [ ] 5.4 DOM-Based XSS
│    │    ├── [ ] 5.4.1 - Introduction To Dom-Based Xss
│    │    ├── [ ] 5.4.2 - Exploitation
│    │    ├── [ ] 5.4.3 - Exploiting DOM-Based XSS Vulnerabilities
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] XSS (Cross-Site Scripting)
│    │         ├── [ ] OWASP Juice Shop (DOM XSS)
│    │         └── [ ] DVWA (Stored XSS challenges)
│    │
│    └─── [ ] 5.5 XSS Tools
│         ├── [ ] 5.5.1 - Identifying & Exploiting Xss Vulnerabilities
│         ├── [ ] 5.5.2 - XSS Attack with XSSer
│         │
│         └─── [ ] TryHackMe Practice Labs:
│              ├── [ ] XSS (Cross-Site Scripting)
│              ├── [ ] XSSer - XSS Exploitation Tool
│              └── [ ] Burp Suite: The Basics (XSS scanning)
│
├─── [ ] Section 6: SQL Injection
│    │
│    ├─── [ ] 6.1 SQL Injection Fundamentals
│    │    ├── [ ] 6.1.1 - Introduction To Sql Injection
│    │    ├── [ ] 6.1.2 - Analysis
│    │    ├── [ ] 6.1.3 - Types
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] SQL Injection
│    │         ├── [ ] SQL Injection Lab
│    │         ├── [ ] SQL Fundamentals
│    │         └── [ ] SQL Injection fundamentals
│    │
│    ├─── [ ] 6.2 Databases
│    │    ├── [ ] 6.2.1 - Introduction To Databases & DBMS
│    │    ├── [ ] 6.2.2 - Relational Vs NoSQL Databases
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] SQL Fundamentals
│    │         ├── [ ] MongoDB Basics (NoSQL)
│    │         └── [ ] Database Security
│    │
│    ├─── [ ] 6.3 SQL Primer
│    │    ├── [ ] 6.3.1 - Introduction To Sql
│    │    ├── [ ] 6.3.2 - Sql Fundamentals - Part 1
│    │    ├── [ ] 6.3.3 - Sql Fundamentals - Part 2
│    │    ├── [ ] 6.3.4 - SQL Basics
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] SQL Fundamentals
│    │         ├── [ ] SQL Injection
│    │         └── [ ] SQLMap: The Basics
│    │
│    ├─── [ ] 6.4 Finding SQLi Vulnerabilities
│    │    ├── [ ] 6.4.1 - Hunting
│    │    ├── [ ] 6.4.2 - Hunting
│    │    ├── [ ] 6.4.3 - Finding
│    │    ├── [ ] 6.4.4 - Finding
│    │    ├── [ ] 6.4.5 - Mutillidae 2
│    │    ├── [ ] 6.4.6 - Finding
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] SQL Injection
│    │         ├── [ ] OWASP Juice Shop (SQLi section)
│    │         ├── [ ] OWASP Mutillidae II
│    │         └── [ ] DVWA (SQL Injection)
│    │
│    ├─── [ ] 6.5 In-Band SQL Injection
│    │    ├── [ ] 6.5.1 - Exploitation
│    │    ├── [ ] 6.5.2 - Exploitation
│    │    ├── [ ] 6.5.3 - PHPMyRecipes
│    │    ├── [ ] 6.5.4 - Exploitation
│    │    ├── [ ] 6.5.5 - Exploiting Union-Based SQL Injection - Part 2
│    │    ├── [ ] 6.5.6 - Vulnerable Results Portal: Union Based SQLi
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] SQL Injection
│    │         ├── [ ] SQL Injection Lab
│    │         ├── [ ] OWASP Juice Shop
│    │         └── [ ] DVWA
│    │
│    ├─── [ ] 6.6 Blind SQL Injection
│    │    ├── [ ] 6.6.1 - Introduction
│    │    ├── [ ] 6.6.2 - OpenSupports
│    │    ├── [ ] 6.6.3 - Exploitation
│    │    ├── [ ] 6.6.4 - Exploitation
│    │    ├── [ ] 6.6.5 - Victor CMS
│    │    ├── [ ] 6.6.6 - Exploitation
│    │    ├── [ ] 6.6.7 - Exploitation
│    │    ├── [ ] 6.6.8 - CiMe Citas Medicas
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] SQL Injection
│    │         ├── [ ] SQLMap: The Basics
│    │         ├── [ ] Boolean-Based SQL Injection
│    │         └── [ ] Time-Based Blind SQLi
│    │
│    └─── [ ] 6.7 NoSQL Injection
│         ├── [ ] 6.7.1 - Nosql Fundamentals - Part 1
│         ├── [ ] 6.7.2 - Nosql Fundamentals - Part 2
│         ├── [ ] 6.7.3 - MongoDB Basics
│         ├── [ ] 6.7.4 - Mongodb Nosql Injection
│         ├── [ ] 6.7.5 - MongoDB NoSQL injection
│         │
│         └─── [ ] TryHackMe Practice Labs:
│              ├── [ ] NoSQL Injection
│              ├── [ ] Detecting NoSQL injection
│              ├── [ ] Exploiting NoSQL operator injection
│              └── [ ] MongoDB security
│
├─── [ ] Section 7: Common Attacks
│    │
│    ├─── [ ] 7.1 HTTP Authentication Attacks
│    │    ├── [ ] 7.1.1 - Http Method Tampering
│    │    ├── [ ] 7.1.2 - HTTP Method Enumeration
│    │    ├── [ ] 7.1.3 - Attacking Basic Http Authentication
│    │    ├── [ ] 7.1.4 - Attacking Basic Auth with Burp Suite
│    │    ├── [ ] 7.1.5 - Attacking Http Digest Authentication
│    │    ├── [ ] 7.1.6 - Attacking HTTP Authentication with Hydra
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Authentication Bypass
│    │         ├── [ ] Hydra
│    │         ├── [ ] Authentication Methods
│    │         ├── [ ] Burp Suite: Intruder
│    │         └── [ ] Multi-Factor Authentication
│    │
│    ├─── [ ] 7.2 Sensitive Data Exposure
│    │    ├── [ ] 7.2.1 - Sensitive Data
│    │    ├── [ ] 7.2.2 - Vulnerable Apache III
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Information disclosure in error messages
│    │         ├── [ ] Information disclosure on debug page
│    │         ├── [ ] Source code disclosure via backup files
│    │         ├── [ ] OWASP Top 10 2025: Insecure Data Handling
│    │         └── [ ] Sensitive Data Exposure
│    │
│    ├─── [ ] 7.3 Broken Authentication
│    │    ├── [ ] 7.3.1 - Attacking
│    │    ├── [ ] 7.3.2 - Vulnerable Bank Portal: Dictionary Attack
│    │    ├── [ ] 7.3.3 - Attacking
│    │    ├── [ ] 7.3.4 - Unlimited Attempts
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Authentication Bypass
│    │         ├── [ ] Broken Authentication
│    │         ├── [ ] Password Attacks
│    │         ├── [ ] Brute force attacks
│    │         └── [ ] Hydra
│    │
│    ├─── [ ] 7.4 Session Security
│    │    ├── [ ] 7.4.1 - Introduction To Session Management
│    │    ├── [ ] 7.4.2 - Session Ids & Cookies
│    │    ├── [ ] 7.4.3 - Session Hijacking & Session Fixation
│    │    ├── [ ] 7.4.4 - Session
│    │    ├── [ ] 7.4.5 - Improper Session Management III
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Session Management
│    │         ├── [ ] Session Hijacking
│    │         ├── [ ] Session Security
│    │         ├── [ ] Cookies
│    │         └── [ ] Session Fixation
│    │
│    ├─── [ ] 7.5 CSRF (Cross-Site Request Forgery)
│    │    ├── [ ] 7.5.1 - Introduction To Cross-Site Request Forgery
│    │    ├── [ ] 7.5.2 - Advanced Electron Forum Csrf
│    │    ├── [ ] 7.5.3 - Advanced Electron Forum
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] CSRF (Cross-Site Scripting)
│    │         ├── [ ] Burp Suite: Intruder (CSRF tokens)
│    │         ├── [ ] Session Management
│    │         └── [ ] PortSwigger: CSRF vulnerability labs
│    │
│    ├─── [ ] 7.6 Injection & Input Validation
│    │    ├── [ ] 7.6.1 - Rce Via Mysql
│    │    ├── [ ] 7.6.2 - Vulnerable File Backup Utility - Command Injection
│    │    ├── [ ] 7.6.3 - Php Code Injection
│    │    ├── [ ] 7.6.4 - PHP Code Injection
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Command Injection
│    │         ├── [ ] SQL Injection
│    │         ├── [ ] Code Injection
│    │         ├── [ ] PHP Code Injection
│    │         └── [ ] Input Validation
│    │
│    └─── [ ] 7.7 Security Misconfigurations
│         ├── [ ] 7.7.1 - Rce Via Mysql
│         ├── [ ] 7.7.2 - RCE via MySQL
│         │
│         └─── [ ] TryHackMe Practice Labs:
│              ├── [ ] Security Misconfigurations
│              ├── [ ] Apache/Nginx Configuration
│              ├── [ ] Web Server Security
│              └── [ ] RCE Vulnerabilities
│
├─── [ ] Section 8: File & Resource Attacks
│    │
│    ├─── [ ] 8.1 Arbitrary File Upload Vulnerabilities
│    │    ├── [ ] 8.1.1 - Introduction
│    │    ├── [ ] 8.1.2 - Exploitation
│    │    ├── [ ] 8.1.3 - Vulnerable Apache IV
│    │    ├── [ ] 8.1.4 - Bypassing
│    │    ├── [ ] 8.1.5 - Vulnerable Nginx II
│    │    ├── [ ] 8.1.6 - Bypassing
│    │    ├── [ ] 8.1.7 - Vulnerable Apache V
│    │    ├── [ ] 8.1.8 - Workaround
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Upload Vulnerabilities
│    │         ├── [ ] File Upload Bypass
│    │         ├── [ ] Web Shell Upload
│    │         ├── [ ] Arbitrary File Upload
│    │         └── [ ] File Upload Evasion
│    │
│    ├─── [ ] 8.2 Directory Path Traversal
│    │    ├── [ ] 8.2.1 - Introduction
│    │    ├── [ ] 8.2.2 - Directory Traversal Basics
│    │    ├── [ ] 8.2.3 - Directory Traversal
│    │    ├── [ ] 8.2.4 - Opening Files
│    │    ├── [ ] 8.2.5 - Opening Files
│    │    ├── [ ] 8.2.6 - OpenEMR Arbitrary File Read
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] File Inclusion
│    │         ├── [ ] Path Traversal
│    │         ├── [ ] Directory Traversal
│    │         ├── [ ] LFI vulnerabilities
│    │         └── [ ] File path traversal labs
│    │
│    ├─── [ ] 8.3 Local File Inclusion (LFI)
│    │    ├── [ ] 8.3.1 - Introduction
│    │    ├── [ ] 8.3.2 - Local File Inclusion Basics
│    │    ├── [ ] 8.3.3 - Local File Inclusion
│    │    ├── [ ] 8.3.4 - Wordpress Imdb Widget Lfi
│    │    ├── [ ] 8.3.5 - WordPress IMDb Widget
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] File Inclusion
│    │         ├── [ ] Local File Inclusion
│    │         ├── [ ] LFI challenges
│    │         ├── [ ] Path Traversal
│    │         └── [ ] Web Shell challenges
│    │
│    └─── [ ] 8.4 Remote File Inclusion (RFI)
│         ├── [ ] 8.4.1 - Introduction
│         ├── [ ] 8.4.2 - Remote File Inclusion
│         ├── [ ] 8.4.3 - Remote File Inclusion I
│         │
│         └─── [ ] TryHackMe Practice Labs:
│              ├── [ ] File Inclusion
│              ├── [ ] Remote File Inclusion
│              ├── [ ] RFI vulnerabilities
│              └── [ ] Web Application Exploitation
│
├─── [ ] Section 9: Web Services
│    │
│    ├─── [ ] 9.1 Web Services Introduction
│    │    ├── [ ] 9.1.1 - Introduction To Web Services
│    │    ├── [ ] 9.1.2 - Web Services Vs APIs
│    │    ├── [ ] 9.1.3 - Web Service Implementations
│    │    ├── [ ] 9.1.4 - Wsdl Language Fundamentals
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] API Fundamentals
│    │         ├── [ ] Web Services
│    │         ├── [ ] API Security
│    │         ├── [ ] REST API
│    │         └── [ ] SOAP & WSDL
│    │
│    └─── [ ] 9.2 Web Services Testing
│         ├── [ ] 9.2.1 - Web Service Security Testing
│         ├── [ ] 9.2.2 - Wsdl Disclosure & Method Enumeration
│         ├── [ ] 9.2.3 - Invoking Hidden Methods
│         ├── [ ] 9.2.4 - Testing For Sql Injection
│         ├── [ ] 9.2.5 - Testing For Command Injection
│         ├── [ ] 9.2.6 - Web Services
│         │
│         └─── [ ] TryHackMe Practice Labs:
│              ├── [ ] API Security
│              ├── [ ] Web Service Enumeration
│              ├── [ ] SOAP Injection
│              ├── [ ] GraphQL security
│              └── [ ] REST API Attacks
│
├─── [ ] Section 10: CMS Pentesting
│    │
│    ├─── [ ] 10.1 Security Testing Introduction
│    │    ├── [ ] 10.1.1 - Introduction
│    │    ├── [ ] 10.1.2 - Introduction
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] CMS Security
│    │         ├── [ ] WordPress Security
│    │         └── [ ] Joomla Security
│    │
│    ├─── [ ] 10.2 Information Gathering & Enumeration
│    │    ├── [ ] 10.2.1 - Wordpress Enumeration
│    │    ├── [ ] 10.2.2 - WordPress AdRotate
│    │    ├── [ ] 10.2.3 - WordPress Enumeration
│    │    ├── [ ] 10.2.4 - WordPress RCE
│    │    ├── [ ] 10.2.5 - WordPress Enumeration
│    │    ├── [ ] 10.2.6 - WP Security Audit Log plugin
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] WordPress Enumeration
│    │         ├── [ ] WPScan
│    │         ├── [ ] WordPress Plugins
│    │         ├── [ ] Theme enumeration
│    │         └── [ ] User enumeration
│    │
│    ├─── [ ] 10.3 Vulnerability Scanning
│    │    ├── [ ] 10.3.1 - WordPress Vulnerability Scanning
│    │    ├── [ ] 10.3.2 - WP Symposium plugin SQL Injection
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] WPScan
│    │         ├── [ ] WordPress Plugin Vulnerabilities
│    │         ├── [ ] Theme Vulnerabilities
│    │         └── [ ] Core Vulnerabilities
│    │
│    ├─── [ ] 10.4 Authentication Attacks
│    │    ├── [ ] 10.4.1 - Wordpress Brute-Force Attacks
│    │    ├── [ ] 10.4.2 - WordPress Plugin
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] WordPress Brute Force
│    │         ├── [ ] Hydra (WordPress plugin)
│    │         └── [ ] XML-RPC attacks
│    │
│    ├─── [ ] 10.5 Exploiting Vulnerabilities
│    │    ├── [ ] 10.5.1 - WordPress Plugin Exploitation
│    │    ├── [ ] 10.5.2 - WordPress Plugin Exploitation
│    │    ├── [ ] 10.5.3 - WP Appointment Booking Calendar Stored XSS
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] WordPress RCE
│    │         ├── [ ] Plugin Exploitation
│    │         ├── [ ] Theme Exploitation
│    │         └── [ ] XSS in WordPress
│    │
│    └─── [ ] 10.6 WordPress Black-Box Pentest
│         ├── [ ] 10.6.1 - Wordpress Black-Box Pentest
│         ├── [ ] 10.6.2 - Exploiting WordPress
│         │
│         └─── [ ] TryHackMe Practice Labs:
│              ├── [ ] WordPress Security
│              ├── [ ] WordPress Enumeration
│              ├── [ ] WordPress Exploitation
│              └── [ ] Full WordPress Pentest
│
├─── [ ] Section 11: Encoding & Filtering Evasion
│    │
│    ├─── [ ] 11.1 Encoding
│    │    ├── [ ] 11.1.1 - Encoding Basics
│    │    ├── [ ] 11.1.2 - Encoding Introduction
│    │    ├── [ ] 11.1.3 - Html Encoding
│    │    ├── [ ] 11.1.4 - Url Encoding - Part 1
│    │    ├── [ ] 11.1.5 - Url Encoding - Part 2
│    │    ├── [ ] 11.1.6 - Base64 Encoding
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] Encoding Fundamentals
│    │         ├── [ ] Cryptography for Dummies
│    │         ├── [ ] URL Encoding
│    │         ├── [ ] HTML Encoding
│    │         └── [ ] Base64 Encoding
│    │
│    ├─── [ ] 11.2 Filtering
│    │    ├── [ ] 11.2.1 - Filtering Introduction
│    │    ├── [ ] 11.2.2 - Bypassing Filters
│    │    ├── [ ] 11.2.3 - Mutillidae 2
│    │    ├── [ ] 11.2.4 - Bypassing Filters
│    │    ├── [ ] 11.2.5 - Bypassing
│    │    ├── [ ] 11.2.6 - Damn Vulnerable Web Application
│    │    ├── [ ] 11.2.7 - Bypassing Filters
│    │    ├── [ ] 11.2.8 - Chamilo LMS
│    │    │
│    │    └─── [ ] TryHackMe Practice Labs:
│    │         ├── [ ] XSS: Bypassing Filters
│    │         ├── [ ] SQLi: Bypassing WAF
│    │         ├── [ ] Input Filtering
│    │         ├── [ ] Output Encoding
│    │         ├── [ ] OWASP Juice Shop (filter bypasses)
│    │         └── [ ] DVWA (filter evasion)
│    │
│    └─── [ ] 11.3 Evasion Techniques
│         ├── [ ] 11.3.1 - Introduction To Evasion
│         ├── [ ] 11.3.2 - Bypassing Squid Proxy - Browser Based
│         ├── [ ] 11.3.3 - Squid: Browser Based Restriction
│         │
│         └─── [ ] TryHackMe Practice Labs:
│              ├── [ ] Obfuscation Principles
│              ├── [ ] XSS Obfuscation
│              ├── [ ] SQLi Obfuscation
│              ├── [ ] WAF Bypasses
│              └── [ ] Advanced Filtering Evasion
│
└─── [ ] Section 12: Conclusion
     └── [ ] 12.1 - Course Conclusion
          └── [ ] Exam Preparation & Next Steps
               ├── [ ] Review key concepts from each section
               ├── [ ] Practice with PortSwigger Web Security Academy
               ├── [ ] Complete HTB or THM full penetration testing labs
               └── [ ] Take practice exam simulations
```

---

## Success Metrics

- **100% Video Completion:** All 11 core sections watched
- **70% Lab Completion:** At least 70% of TryHackMe + PortSwigger labs completed
- **PortSwigger Academy:** Minimum 80% of relevant labs completed
- **10+ Full Pentests:** Real-world scenario testing
- **Personal Notes:** Key concepts and payloads documented
- **Exam Readiness:** Practice exams scoring 80%+

---

**Last Updated:** April 2026  
**Target Certification:** eLearnSecurity eWPT (Web Penetration Tester)  
**Estimated Total Study Time:** 120-150 hours  
**Total Practice Labs:** ~1575 labs (TryHackMe + PortSwigger)
