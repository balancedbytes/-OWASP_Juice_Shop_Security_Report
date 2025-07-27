# -OWASP_Juice_Shop_Security_Report

This repository contains a penetration testing report of the OWASP Juice Shop web application, conducted as part of my practical cybersecurity work.

About the Report

Context: This penetration test was conducted treating OWASP Juice Shop as a live company web application. This approach helped simulate real-world security assessment scenarios, including detailed reporting, risk analysis, and strategic recommendations as if for an actual client.

The report documents an external penetration test performed on the OWASP Juice Shop application, identifying six key vulnerabilities ranging from critical to medium severity. The findings include:

• SQL Injection (Critical)
• Broken Access Control (Critical)
• Brute Force Attack on Admin Password (High)
• Insecure Direct Object Reference (Medium)
• Security Misconfiguration (Medium)
• Sensitive Data Exposure (Medium)

These vulnerabilities were validated with manual testing and tools such as Burp Suite, demonstrating real risk and providing actionable remediation recommendations.

Contents

1. OWASP_Juice_Shop_Security_Report.pdf — Full 12-page PDF detailing findings, severity ratings, proofs of concept, and strategic recommendations.

2. README.md — This overview document.

Key Highlights

- The assessment revealed critical vulnerabilities that could allow unauthorized access, privilege escalation, and data exposure.

- Immediate remediation is recommended for critical and high severity issues.

- The report includes detailed technical explanations and practical recommendations for securing the application.

How to Use This Repository

1. Review the PDF report for a thorough understanding of each vulnerability.
2. Use the findings as a learning resource or guide for securing similar web applications.
3. Explore manual testing techniques demonstrated in the report to improve your penetration testing skills.

Tools & Environment

Burp Suite Community Edition for manual interception and brute force testing.
Browser Developer Tools for front-end inspection and endpoint discovery.
TryHackMe OWASP Juice Shop lab environment for safe testing.
Custom wordlists (e.g., best1050.txt) for password attacks.


About Me

I’m Emman, a Computer Engineering student and Lead Penetration Tester at Geez Security. This project reflects my hands-on experience in web application security testing and reporting.
