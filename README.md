# Web Security Assessment – clariva.co.uk

⚠️ This assessment was performed with permission and for educational purposes only.

---

## Overview

This project documents a basic web application security assessment conducted on a live website.

The objective was to identify:

* exposed endpoints
* misconfigurations
* potential attack surface

---

## Scope

* Target: https://www.clariva.co.uk
* Method: Passive reconnaissance only
* No intrusive testing performed

---

## Methodology

* Technology fingerprinting (WhatWeb)
* HTTP header inspection
* robots.txt and sitemap analysis
* Manual browser inspection (DevTools)

---

## Key Findings

### Technology Stack

* WordPress (detected via frontend artifacts)
* IONOS managed hosting
* Apache web server

---

### Attack Surface

* No publicly accessible login panel
* Limited number of endpoints
* Mostly static-like content

---

### Observations

* robots.txt exposes `/wp-admin/`
* HTTPS enforced
* Rate-limiting headers present

---

## Risk Assessment

Overall risk level: **Low**

---

## Conclusion

The application demonstrates a reduced attack surface and no obvious exploitable vulnerabilities.

This highlights the effectiveness of:

* limiting exposed endpoints
* using managed infrastructure
* minimizing dynamic functionality

---

## Skills Demonstrated

* Web reconnaissance
* Enumeration techniques
* Attack surface analysis
* Security-oriented thinking

---

## Lessons Learned

* Not all applications expose vulnerabilities
* robots.txt is not a security mechanism
* Reduced attack surface significantly improves security posture

