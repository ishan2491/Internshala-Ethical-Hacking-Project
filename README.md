# Internshala-Ethical-Hacking-Project
Basics of Information Security, Computer Networking and Web  Development, Information Gathering and VAPT of some important vulnerabilities in the OWASP top 10,  Automating VAPT, and Documenting and Reporting Vulnerabilities. 
Web Application Security Project

Project Overview

This project evaluates the security posture of a web application, identifying vulnerabilities and assessing their potential impact. The analysis provides actionable insights for developers and security professionals to mitigate risks and enhance the application’s security.

Key Features of the Report

Security Status: The web application was classified as extremely vulnerable based on the findings.

Vulnerability Analysis:

Critical Issues:

SQL Injection (3 instances)

Insecure Direct Object References (IDOR) (3 instances)

Rate Limiting Flaws (1 instance)

Insecure File Uploads (1 instance)

Default Admin Password (1 instance)

Remote File Inclusion (1 instance)

Severe Vulnerabilities:

Reflected Cross-Site Scripting (XSS) (1 instance)

Stored Cross-Site Scripting (XSS) (1 instance)

Moderate and Low Risks:

Directory Listing (2 instances)

Descriptive Error Messages (1 instance)

Client-Side Bypass Filters (2 instances)

Default File Misconfiguration Flaws (5 instances)

Attack Scenarios Highlighted

SQL Injection:

Hackers can inject crafted SQL commands into form fields to extract database structure and sensitive information.

Cross-Site Scripting (XSS):

Allows attackers to execute code in a trusted user’s browser, stealing session cookies or taking control of the site.

Brute Force Attacks:

Used to crack passwords, login credentials, and encryption keys, granting unauthorized access to systems.

Insecure Direct Object References (IDOR):

Attackers can modify filenames to access sensitive data belonging to other users.

Vulnerability Statistics

Critical: 16

Severe: 7

Moderate: 6

Low: 6

Recommendations

Implement robust input validation to prevent SQL Injection.

Sanitize user inputs and adopt Content Security Policies (CSP) to mitigate XSS.

Enforce strong password policies and multi-factor authentication (MFA) to prevent brute force attacks.

Apply access control mechanisms to restrict unauthorized access to sensitive data.

Regularly audit and patch components with known vulnerabilities.

Supporting Materials

Video Demonstration: force_browsing.mp4 provides a practical example of one vulnerability.

Detailed Report: For in-depth analysis, refer to the Final Project web application.pdf.

How to Use This Report

Review the detailed vulnerability breakdown.

Use the recommendations to prioritize and address the identified issues.

Incorporate the findings into the application’s security development lifecycle
