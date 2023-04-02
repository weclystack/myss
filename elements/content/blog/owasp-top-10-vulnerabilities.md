+++
categories = ["Bug Hunter"]
date = 2023-04-01T23:00:00Z
description = ""
image = "/images/owasp-top-ten-1000-1-5.png"
title = "OWASP Top 10 Vulnerabilities"
type = "featured"

+++
**OWASP (Open Web Application Security Project) is a non-profit organization dedicated to improving software security. The OWASP Top 10 is a list of the top 10 most critical web application security risks. The latest version of OWASP Top 10 as of 2021 is:**

##### 1.Injection:

Injection flaws, such as SQL, NoSQL, OS, and LDAP injection, occur when untrusted data is sent to an interpreter as part of a command or query. The attacker's hostile data can trick the interpreter into executing unintended commands or accessing data without proper authorization.

##### 2.Broken Authentication and Session Management:

Application functions related to authentication and session management are often not implemented correctly, allowing attackers to compromise passwords, keys, or session tokens, or to exploit other implementation flaws to assume other users' identities.

##### 3.Cross-Site Scripting (XSS):

XSS flaws occur whenever an application includes untrusted data in a new web page without proper validation or escaping, or updates an existing web page with user-supplied data using a browser API that can create JavaScript. XSS allows attackers to execute scripts in the victim's browser that can hijack user sessions, deface web sites, or redirect the user to malicious sites.

##### 4.Broken Access Control:

Restrictions on what authenticated users are allowed to do are often not properly enforced. Attackers can exploit these flaws to access unauthorized functionality and/or data, such as accessing other users' accounts, viewing sensitive files, modifying other users' data, or changing access rights.

##### 5.Security Misconfiguration:

Security misconfiguration is the most commonly seen issue. This is commonly a result of insecure default configurations, incomplete or ad hoc configurations, open cloud storage, misconfigured HTTP headers, and verbose error messages containing sensitive information. Not only must all operating systems, frameworks, libraries, and applications be securely configured, but they must be patched/upgraded in a timely fashion.

##### 6.Insecure Cryptographic Storage:

Many web applications do not properly protect sensitive data, such as credit cards, passwords, and session tokens, during storage and transmission. Attackers may steal or modify such weakly protected data to conduct credit card fraud, identity theft, or other crimes.

##### 7.Insufficient Logging and Monitoring:

Insufficient logging and monitoring, coupled with missing or ineffective integration with incident response, allows attackers to further attack systems, maintain persistence, pivot to more systems, and tamper, extract, or destroy data. Most breach studies show time to detect a breach is over 200 days, typically detected by external parties rather than internal processes or monitoring.

##### 8.Insecure Communication:

Applications frequently fail to encrypt network traffic when it is necessary to protect sensitive communications. Attackers can eavesdrop on network traffic to steal sensitive data transmitted between clients and servers (e.g., payment credentials, personally identifiable information (PII), or other sensitive information).

##### 9.Using Components with Known Vulnerabilities:

Components, such as libraries, frameworks, and other software modules, run with the same privileges as the application. If a vulnerable component is exploited, such an attack can facilitate serious data loss or server takeover. Applications and APIs using components with known vulnerabilities may undermine application defenses and enable various attacks and impacts.

##### 10.Insufficient Attack Protection:

The majority of applications and APIs lack the basic ability to detect, prevent, and respond to both manual and automated attacks. Attack protection goes far beyond basic input validation and involves automatically detecting and blocking threats from entering or spreading across applications and APIs.

**That's probably all I can say this time with the vulnerabilities that often occur today.**