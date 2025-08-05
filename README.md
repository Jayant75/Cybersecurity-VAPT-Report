# Vulnerability Assessment and Penetration Testing (VAPT) Project
##👤 Author
Jayant Singh  
**Institution: JSS , Noida 
**Supervisor: Mr Nikhil Pandey   
**Submission Date: 5 August 2025

---

## 📌 Abstract
This project outlines a systematic Vulnerability Assessment and Penetration Testing (VAPT) conducted on a target web application. The objective was to identify, exploit, and document security vulnerabilities using industry-standard tools and methodologies. The report includes tool usage, discovered vulnerabilities, mitigation strategies, and testing challenges.

---

## 🛠️ Tools Used

- **Nmap**: Port scanning and service enumeration.
- **Burp Suite**: Web application testing (intercepting traffic, vulnerability scanning).
- **SQLMap**: SQL injection discovery and exploitation.
- **OWASP ZAP**: Automated vulnerability detection. Aww

---

## 🧭 Methodology

1. **Reconnaissance**: Collect domain information, subdomains, and IPs using OSINT.
2. **Scanning & Enumeration**: Run Nmap to identify open ports and services.
3. **Vulnerability Discovery**: Use OWASP ZAP to detect weaknesses.
4. **Manual Testing**: Deploy Burp Suite and SQLMap for deeper exploration.
5. **Exploitation**: Validate impact through controlled payloads.
6. **Reporting**: Categorize findings by severity and suggest remediation.

---

##  📊 Results- Vulnerabilities Identified

| Vulnerability            | Severity   | Tool Used      | Mitigation                  |
|--------------------------|------------|----------------|-----------------------------|
| SQL Injection            | High       | SQLMap         | Parameter sanitization      |
| XSS (Cross-Site Scripting)| Medium    | Burp Suite     | Output encoding             |
| Open Port (FTP - 21)     | Medium     | Nmap           | Restrict access, secure FTP |

📎 See `report/Cybersecurity-(VAPT) Project Report.pdf folder for evidence.

---

## ⚔️ Challenges Faced

- Dealing with HTTPS interception through self-signed certs.
- False positives during automated scans (ZAP).
- Network throttling impacted scanning speed.
- Ensuring ethical boundary adherence while exploiting.

---

## ✅ Conclusion

The project successfully identified multiple security flaws in the test environment, highlighting real-world risks posed by poor input handling, misconfigured services, and outdated components. The findings emphasize the importance of proactive security auditing.

---

## 📚 References

- OWASP Testing Guide: [https://owasp.org/www-project-web-security-testing-guide](https://owasp.org/www-project-web-security-testing-guide)
- Nmap Docs: [https://nmap.org/book/man.html](https://nmap.org/book/man.html)
- SQLMap Usage: [https://github.com/sqlmapproject/sqlmap](https://github.com/sqlmapproject/sqlmap)

---

