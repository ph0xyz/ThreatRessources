# 🛡️ Cybersecurity Threat Intelligence & Advisory Sources

A curated collection of cybersecurity advisory sources, RSS feeds, threat intelligence platforms, and software tools – built for SOCs, CERTs, and security researchers to stay ahead of emerging threats.

---

## 📖 Manual Readers

Manually browsable advisory portals for vulnerability tracking and alert monitoring:

- **CCB Belgium – Advisories**  
  [ccb.belgium.be/advisories](https://ccb.belgium.be/advisories)
  
- **CERT Austria**  
  - Warnings: [cert.at/warnungen](https://www.cert.at/de/meldungen/warnungen/)  
  - News: [cert.at/aktuelles](https://www.cert.at/de/meldungen/aktuelles/)  
  - Daily Reports: [cert.at/tagesberichte](https://www.cert.at/de/meldungen/tagesberichte/)
  
- **CERT-Bund – Kurzmeldungen**  
  [wid.cert-bund.de/portal/wid/kurzinformationen](https://wid.cert-bund.de/portal/wid/kurzinformationen)
  
- **CISA – Cybersecurity Advisories**  
  - All Advisories: [cisa.gov/news-events/cybersecurity-advisories](https://www.cisa.gov/news-events/cybersecurity-advisories)  
  - Code Red Advisories: [cisa.gov/code-red](https://www.cisa.gov/news-events/cybersecurity-advisories?f%5B0%5D=advisory_type%3A94)
  
- **CERT-EU – 2025 Advisories**  
  [cert.europa.eu/publications/security-advisories/2025](https://cert.europa.eu/publications/security-advisories/2025)
  
- **CVEFeed.io – Vulnerability Aggregation**  
  [cvefeed.io](https://cvefeed.io/)
  
- **Fortinet FortiGuard**  
  - AppControl DB: [fortiguard.fortinet.com/appcontrol](https://fortiguard.fortinet.com/appcontrol)  
  - PSIRT Blog Feed: [feeds.fortinet.com/fortinet/blog/psirt](https://feeds.fortinet.com/fortinet/blog/psirt)  
  - Security Advisories: [fortiguard.com/psirt](https://www.fortiguard.com/psirt)
  
- **Palo Alto Networks Security Advisories**  
  [securityadvisories.paloaltonetworks.com](https://securityadvisories.paloaltonetworks.com/)

---


## ⚙️ Tools & Software

Software tools and platforms developed by CIRCL, Pandora, and related initiatives – these are designed for analysis, threat data processing, and operational intelligence (distinct from manual advisory sites):

- **Pandora** – Cybersecurity analysis platform  
  [pandora.circl.lu](https://pandora.circl.lu)
  
- **Vulnerability Lookup** – Search vulnerabilities across multiple sources  
  [vulnerability-lookup.org](https://www.vulnerability-lookup.org/)
  
- **Pandora Analysis on GitHub** – Open-source projects and tools  
  [github.com/pandora-analysis](https://github.com/pandora-analysis)
  
- **CIRCLean** – Project for cleaning and processing threat data  
  [circl.lu/projects/CIRCLean/](https://circl.lu/projects/CIRCLean/)
  
- **Passive DNS** – CIRCL's passive DNS service  
  [circl.lu/services/passive-dns/](https://circl.lu/services/passive-dns/)
  
- **URLAbuse** – Report and lookup abused URLs  
  [circl.lu/urlabuse/](https://circl.lu/urlabuse/)
  
- **Lookyloo** – Visual analysis of web artifacts and URLs  
  [lookyloo.circl.lu/](https://lookyloo.circl.lu/)
  
- **Vulnerability Service (CIRCL)** – Explore vulnerabilities from CIRCL  
  [vulnerability.circl.lu/](https://vulnerability.circl.lu/)
  
- **IP to ASN Mapping Whois Service** – Track IP address announcements over time  
  [circl.lu/services/ip-asn-history/](https://circl.lu/services/ip-asn-history/)  
  > Developed by CIRCL to look up the evolution of IP address announcements over the past four years.
  
- **BGP Ranking – IP to ASN Mapping**  
  [bgpranking.circl.lu/ipasn](https://bgpranking.circl.lu/ipasn)
  
- **BGP Ranking – General BGP and Routing Analysis**  
  [bgpranking.circl.lu/](https://bgpranking.circl.lu/)

  **MISP Proejct - IOC sharing platform**
  [misp-project.org](https://misp-project.org/)

---

## 📦 CSAF Resources

Machine-readable security advisories in CSAF format for integration in automated workflows and vulnerability management:

- **📘 BSI CSAF Portal**  
  [bsi.bund.de – CSAF](https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Empfehlungen-nach-Angriffszielen/Industrielle-Steuerungs-und-Automatisierungssysteme/CSAF/CSAF_node.html)

- **🔗 CSAF Aggregator (CERT-Bund)**  
  [aggregator.json](https://wid.cert-bund.de/.well-known/csaf-aggregator/aggregator.json)  
  

### 🏷️ Trusted CSAF Providers

Below are selected trusted providers with machine-readable `provider-metadata.json`:

| Publisher                         | CSAF Metadata URL |
|----------------------------------|-------------------|
| **Intevation GmbH**              | [Link](https://intevation.de/.well-known/csaf/provider-metadata.json) |
| **Nozomi Networks**              | [Link](https://csaf.data.security.nozominetworks.com/provider-metadata.json) |
| **Red Hat Product Security**     | [Link](https://security.access.redhat.com/data/csaf/v2/provider-metadata.json) |
| **Huawei PSIRT**                 | [Link](https://www.huawei.com/.well-known/csaf/provider-metadata.json) |
| **CISA**                         | [Link](https://www.cisa.gov/sites/default/files/csaf/provider-metadata.json) |
| **SICK PSIRT**                   | [Link](https://www.sick.com/.well-known/csaf/provider-metadata.json) |
| **Stackable Security Team**      | [Link](https://advisories.stackable.tech/.well-known/csaf/provider-metadata.json) |
| **Open-Xchange GmbH**            | [Link](https://www.open-xchange.com/.well-known/csaf/provider-metadata.json) |
| **Siemens ProductCERT**          | [Link](https://cert-portal.siemens.com/productcert/csaf/provider-metadata.json) |
| **BSI / CERT-Bund**              | [Link](https://wid.cert-bund.de/.well-known/csaf/provider-metadata.json) |
| **Hitachi Energy PSIRT**     | [Link](https://aggregator.cert-bund.de/.well-known/csaf-aggregator/www_hitachienergy_com_cybersecurity_alerts-and-notifications/provider-metadata.json) |


---

## 📡 RSS Feeds

Real-time vulnerability and advisory updates for integration into feed readers, SIEMs, or SOAR tools:

### General & National CERTs

- [CERT-Bund Security RSS](https://wid.cert-bund.de/content/public/securityAdvisory/rss)  
- [CISA – All Advisories](https://www.cisa.gov/cybersecurity-advisories/all.xml)  
- [CISA – ICS Advisories](https://www.cisa.gov/cybersecurity-advisories/ics-advisories.xml)
- [CISA - Known Exploited Vulnerabilities](https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json)
- [CISA EPSS Feed](https://api.first.org/data/v1/epss)
- [CERT-EU RSS](https://cert.europa.eu/publications/security-advisories-rss)
- [EUVD latest Vulnerabilities](https://euvdservices.enisa.europa.eu/api/lastvulnerabilities)
- [Canada CCCS RSS](https://www.cyber.gc.ca/api/cccs/rss/v1/get?feed=alerts_advisories&lang=en)  
- [NCSC UK](https://www.ncsc.gov.uk/api/1/services/v1/all-rss-feed.xml)  
- [Finland NCSC](https://www.kyberturvallisuuskeskus.fi/feed/rss/en)  
- [CERT Polska](https://cert.pl/en/rss.xml)  
- [CERT Slovenia](https://www.cert.si/en/category/news/feed/)

### Vendor-Specific Feeds

- **Siemens ProductCERT**  
  - Advisories: [RSS](https://cert-portal.siemens.com/productcert/rss/advisories.atom?ste_sid=6cf9821d2148622624d167e8ab7104bd)  
  - Alerts: [RSS](https://cert-portal.siemens.com/productcert/rss/alerts.atom?ste_sid=6cf9821d2148622624d167e8ab7104bd)
  
- **CVEFeed.io RSS**  
  - Latest: [RSS](https://cvefeed.io/rssfeed/latest.xml)  
  - High Severity: [RSS](https://cvefeed.io/rssfeed/severity/high.xml)
  
- **Palo Alto Networks**  
  [RSS](https://securityadvisories.paloaltonetworks.com/rss.xml)
  
- **Cisco PSIRT Advisories**  
  [RSS](https://sec.cloudapps.cisco.com/security/center/psirtrss20/CiscoSecurityAdvisory.xml)
  
- **HP Security Advisories**  
  [RSS](https://support.hp.com/wcc-widget-services/us-en/rss-feed?category=business-solutions-software&id=232422101974597001049413910241836)

### Topic-Specific Feeds (Talkback.sh)

- [Network Security](https://talkback.sh/resources/feed/category/7/)  
- [Industrial Control Systems](https://talkback.sh/resources/feed/category/6/)

---

## 📬 Email Newsletters

Get timely email updates from trusted CERTs and vendors:

- **CISA Code Red Alerts (USA)**  
  [Subscribe](https://public.govdelivery.com/accounts/USDHSCISA/subscriber/new?qsp=CODE_RED)
  
- **Siemens ProductCERT (Vendor)**  
  [Subscribe](https://www.siemens.com/global/en/products/services/cert.html#SubscribetoSecurityAdvisories)
  
- **CERT Austria Mailinglisten**  
  - Warnings: [warning.lists.cert.at](https://lists.cert.at/mailman3/postorius/lists/warning.lists.cert.at/)  
  - Daily Reports: [daily.lists.cert.at](https://lists.cert.at/mailman3/postorius/lists/daily.lists.cert.at/)

---

## 🧠 IOCs & Threat Intelligence

Search, collect, or integrate Indicators of Compromise (IOCs) from reliable open-source repositories:

- [ThreatFeeds.io](https://threatfeeds.io/) – Central aggregation hub  
- [Talos Intelligence](https://www.talosintelligence.com/) – Cisco's research unit  
- [ThreatFox](https://threatfox.abuse.ch/) – Malware IOC sharing platform  
- [URLHaus](https://urlhaus.abuse.ch/) – Malicious URL database (Abuse.ch)

---

_🔐 Stay ahead of threats. Monitor early. Respond fast._
