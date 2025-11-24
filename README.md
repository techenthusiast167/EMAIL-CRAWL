# EmailCrawl

![Python](https://img.shields.io/badge/Python-3.6+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![OSINT](https://img.shields.io/badge/OSINT-Tool-orange.svg)
![Security](https://img.shields.io/badge/Cybersecurity-Professional-red.svg)

**EmailCrawl** is a professional-grade OSINT (Open Source Intelligence) tool designed for advanced email address extraction through comprehensive web crawling. Built for cybersecurity professionals, penetration testers, and intelligence analysts.

---

## Table of Contents

- Overview
- Key Features
- Importance in OSINT & Cybersecurity
- Installation
- Usage
- Output Examples
- Use Cases
- Legal & Ethical Considerations
- Contributing
- Disclaimer

---

## Overview

EmailCrawl is a specialized reconnaissance tool that systematically crawls websites and their subdirectories to extract valid email addresses. Unlike generic web scrapers, it employs advanced validation algorithms to filter out false positives and identify legitimate contact information.

---


## KEY FEATURES

Advanced Crawling Engine

• **Intelligent URL Discovery** - Parses robots.txt, sitemaps, and HTML content

• **Configurable Depth Control** - Adjustable crawl depth and page limits

• **Same-Domain Focus** - Stays targeted on the specified domain

• **Respectful Crawling** - Built-in delays and proper user-agent headers


## SMART EMAIL EXTRACTION

• **Multi-Source Extraction** - Visible text, meta tags, and mailto links

• **Advanced Validation** - Sophisticated false positive filtering

• **Real-Time Discovery** - Live email detection with source URLs

• **Duplicate Prevention** - Automatic deduplication of found emails


## PROFESSIONAL FEATURES

• **Proxy Support** - HTTP/SOCKS proxy integration for anonymity

• **Comprehensive Reporting** - JSON and TXT output formats

• **Domain Analysis** - Email distribution by domain

• **Performance Metrics** - Detailed crawl statistics and timing




## IMPORTANCE IN OSINT & CYBERSECURITY

### OSINT Intelligence Gathering


**Primary Use Cases**:

• **Threat Intelligence** - Identify key personnel in target organizations

• **Attack Surface Mapping** - Discover contact points for social engineering

• **Corporate Reconnaissance** - Map organizational structure via email patterns


## CYBERSECURITY APPLICATION


**Defensive Security**:

• **External Threat Assessment** - Understand what email information is publicly exposed

• **Phishing Defense** - Identify emails that could be targeted in phishing campaigns

• **Security Awareness** - Demonstrate information exposure to employees

**Offensive Security**:

• **Penetration Testing** - Email discovery for authorized security assessments

• **Red Team Operations** - Social engineering preparation and reconnaissance

• **Vulnerability Assessment** - Identify information disclosure risks

• **Investigative Research** - Gather contact information for legal investigations



## STRATEGIC VALUE

• **Early Warning System** - Detect exposed email addresses before attackers do

• **Attack Prevention** - Proactively secure vulnerable contact points

• **Compliance** - Identify GDPR/Privacy Act compliance issues

• **Risk Management** - Quantify organizational exposure through public data



## INSTALLATION

**Prerequisites**

    Python 3.6 or higher

    pip package manager

**Quick Manual Installation**

Visit the link below to get the script, then use nano to install it:

**https://gist.github.com/techenthusiast167/6de049a8260cf8c53d424aeb7ff8402d**

**Step-by-Step**:

• Click on the link below to access the script

• Copy the script content

• Use nano to create and install the tool



**Install dependencies**

     pip install requests beautifulsoup4 tldextract colorama


## USAGE

**Basic Command**

      python3 emailcrawl.py https://example.com


**Deep Reconnaissance With Custom Limits**

    python3 emailcrawl.py https://example.com --max-pages 500 --max-depth 4



**With Proxy For Operational Security**

     python3 emailcrawl.py https://example.com --proxy http://127.0.0.1:8080


**Custom Output And Faster Crawling**

     python3 emailcrawl.py https://example.com --delay 0.5


## FULL COMMAND REFERENCE

**Option	 Description	  Default**

--max-pages NUM	  Maximum pages to crawl	> 200

--max-depth NUM	  Maximum crawl depth	>  3

--output FILE	    Custom output file path	 >  auto-generated

--proxy URL	H     TTP/SOCKS proxy URL	 >  none

--delay SECONDS	  Delay between requests	 >  1

-h, --help	S     how help message	 > N/A


## OUTPUT EXAMPLES

**Real-Time Discovery**

[EMAIL] Found: john.doe@company.com (mailto link from: https://company.com/contact)
[EMAIL] Found: sarah.wilson@company.com (from: https://company.com/team)
[EMAIL] Found: info@company.com (from: https://company.com/about)



## SUMMARY REPORT


============================================================
EMAILCRAWL - EXTRACTION SUMMARY
============================================================
[STATS] Pages Crawled: 147
[STATS] Unique Emails Found: 23
[STATS] Crawl Duration: 45.32 seconds

**EMAIL DOMAINS DISTRIBUTION**:

  company.com: 18 emails
  gmail.com: 3 emails
  outlook.com: 2 emails

**UNIQUE EMAILS EXTRACTED**:

  admin@company.com
  info@company.com
  john.doe@company.com


## LEGAL & ETHICAL CONSIDERATION

Authorized Use Only


### LEGAL USES:

✓ Security assessments with explicit permission
✓ Your own websites and applications
✓ Public bug bounty programs
✓ Academic research with ethics approval

### ILLEGAL USES:

✗ Unauthorized access to systems
✗ Harassment or spam campaigns
✗ Commercial exploitation without consent
✗ Violation of terms of service


## RESPONSIBLE DISCLOSURE

• Always obtain proper authorization before scanning

• Respect robots.txt and website terms of service

• Use appropriate rate limiting to avoid service disruption

• Report discovered vulnerabilities responsibly


## CONTRIBUTING

The author welcome contributions from the security community!

**Areas for Improvement**:

• Enhanced email pattern recognition

• Additional output formats (CSV, XML)

• Integration with other OSINT tools

• Performance optimizations
    

**Contribution Process**

• Fork the repository

• Create a feature branch

• Submit a pull request with comprehensive testing

