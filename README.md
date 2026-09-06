# Security Portfolio

Web application penetration testing reports and write-ups by **Subhan Majidov**.

Junior web application penetration tester, trained at IDTech Academy (Offensive Security: Web & Mobile Penetration Testing, completed with High Honor). All engagements below were performed against deliberately vulnerable applications in authorised training environments.

[LinkedIn](https://www.linkedin.com/in/subhan-majidov-9144aa306) · [TryHackMe](https://tryhackme.com/p/subhanmajidov) · [Hack The Box](https://profile.hackthebox.com/profile/019de24e-c45b-71f9-85d3-8d0310b052e2) · subhanmajidov@gmail.com

---

## Reports

### Meridian Corp — Internal Staff Portal & Mobile API (August 2026)

Two-day black-box penetration test of a PHP staff portal and its JWT-authenticated mobile API. Final assessment for the IDTech Academy course.

| | |
|---|---|
| **Duration** | 2 days (22–24 August 2026) |
| **Findings** | 27 (5 Critical · 9 High · 11 Medium · 2 Low) + 2 Informational |
| **Methodology** | Black-box, manual testing only — OWASP WSTG, OWASP Top 10 (2025), CVSS 3.1 |
| **Highlights** | RCE via unrestricted file upload chained with LFI · RCE via SSTI · unauthenticated account takeover via predictable reset token · JWT `alg:none` bypass · UNION and blind SQL injection · insecure deserialisation · mass assignment · IDOR in HTTP and WebSocket handlers |
| **Report** | Executive summary, root-cause analysis grouping 22 findings into 3 architectural causes, five-step prioritised remediation roadmap, 100 pages |

📄 **[Meridian Corp Web Application Penetration Test Report](reports/Meridian_Corp_Web_Application_Penetration_Test_Report.pdf)**

### ByteBazar — E-commerce Platform & REST API (June 2026)

Time-boxed two-hour black-box assessment of an e-commerce web application and its REST API. Mid-course lab at IDTech Academy.

| | |
|---|---|
| **Duration** | 2 hours |
| **Findings** | 12 (5 Critical · 6 High · 1 Medium) |
| **Methodology** | Black-box, manual testing — findings mapped to CWE and OWASP Top 10 |
| **Highlights** | Privilege escalation via mass assignment, JWT `alg:none` and missing admin authorisation · login and OTP brute force chained into full administrator account takeover · IDOR (read and write) · SQL injection and reflected XSS |
| **Report** | Steps to reproduce, evidence, security impact and a phased remediation plan, 28 pages |

📄 **[ByteBazar Web Application Penetration Test Report](reports/ByteBazar_Web_Application_Penetration_Test_Report.pdf)**

---

## Certificates

- **IDTech Academy — Cybersecurity (Web & Mobile Penetration Testing), Certificate of Completion with High Honor** — April–August 2026 · [PDF](certificates/IDTech_Certificate.pdf) · Credential ID `b3c15201-05e8-485c-99f4-fc9b633c0c23`
- **TryHackMe — Jr Penetration Tester** — [Verify](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-KTCCN3IYLP.pdf)
- **PortSwigger Web Security Academy** — all learning paths and labs completed (2026)

---

## Tooling

Burp Suite (Proxy, Repeater, Intruder) · Nmap · FFUF · Gobuster · Dirsearch · SQLMap · curl · Kali Linux

---

*Reports are published for portfolio purposes. Target hosts were instructor-provided training environments and are no longer online.*
