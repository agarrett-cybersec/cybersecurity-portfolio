# SQL Injection Attack
## Overview
SQL injection is a web application vulnerability that allows attackers to insert malicious SQL commands into a vulnerable application and interact with its backend database. In this lab, I used the Damn Vulnerable Web Application (DVWA) to demonstrate how SQL injection can be used to access or manipulate database information in a controlled environment.
## Purpose
The purpose of this lab was to understand how SQL injection vulnerabilities occur, identify vulnerable web application inputs, and demonstrate how improper input handling can expose sensitive database information.
## Lab Demonstration
The lab demonstrates the process of identifying a vulnerable input in DVWA and submitting SQL injection commands to interact with the application's backend database. The exercise shows how a vulnerable application can potentially allow unauthorized access to database information.
## Video: [Watch Lab Demonstration](https://youtu.be/Gm0AhfdDDIY)
## Security Takeaway
SQL injection can expose sensitive information and potentially allow attackers to modify or delete database data. Proper input validation, parameterized queries, and secure coding practices are important for protecting web applications against SQL injection attacks.


# Cross-Site Scripting (XSS) Attack
## Overview
Cross-Site Scripting (XSS) is a web application vulnerability that allows an attacker to inject malicious code into a web page. In this lab, I used the Damn Vulnerable Web Application (DVWA) to demonstrate how an XSS vulnerability can be identified and exploited in a controlled environment.
## Purpose
The purpose of this lab was to understand how XSS vulnerabilities can affect web applications and how vulnerable parameters can be exploited to execute malicious code in a user's browser.
## Lab Demonstration
The lab demonstrates the process of accessing DVWA, configuring the security levels to Low and Medium, identifying a vulnerable parameter, and testing an XSS payload to observe how injected code is executed by the web browser.
## Video: [Watch Lab Demonstration](https://youtu.be/F3gaTkRABh4)
## Security Takeaway
XSS vulnerabilities can allow attackers to execute malicious code within a user's browser and potentially compromise sensitive information or user sessions. Identifying and properly securing vulnerable inputs is an important part of protecting web applications from XSS attacks.


