# CS-305
Welcome to the CS 305 repository! This repository contains a set of security-focused projects I developed as part of my CS 305 course at Southern New Hampshire University. Throughout this course, I explored secure coding principles, vulnerability assessment, and best practices for hardening applications against threats. This repository showcases my ability to identify, report, and remediate real-world software security vulnerabilities.

## About the Course
CS 305 focuses on the essential skills of software security in modern development. The course emphasizes secure design, identifying weaknesses in existing code, and implementing best practices to mitigate risks. Projects in this course required both technical analysis and professional documentation to simulate real-world software security scenarios.

Key topics in this course included:

- Software Vulnerabilities – Discovering and analyzing flaws in source code.
- Secure Coding Practices – Refactoring code to improve security posture.
- Threat Mitigation – Applying encryption, access control, and input validation.
- Static Analysis Tools – Using Maven Dependency-Check to locate vulnerable libraries.
- Risk Reporting – Communicating findings to non-technical stakeholders effectively.

## What You'll Find Here
This repository contains Project One and Project Two for CS 305, which focus on the security assessment of a fictional client, Artemis Financial. These projects simulate the real-world process of auditing insecure code, performing a risk analysis, and implementing fixes.

- The key components of these projects include:
- Manual Code Review – Inspected a Java web application to identify and document insecure coding patterns.
- Vulnerability Report – Prepared a comprehensive report with detailed findings and recommended remediations.
- Maven Dependency Analysis – Performed a static scan to identify outdated or high-risk libraries.
- Mitigation Strategy – Refactored the application’s code and dependencies to reduce risk exposure.
- SSL Certificate Implementation – Configured secure communication with a self-signed certificate using Java Keytool.

## Why This Project Matters
The project helped solidify my understanding of how even small oversights in code can lead to serious vulnerabilities. Learning to identify, report, and remediate these issues prepares me to contribute to secure software design in professional settings. This project strengthened my ability to think critically about security in every phase of the software development lifecycle.

## Reflection
## Who was the client? What issue did the company want you to address?
The client, Artemis Financial, is a fictional financial services company that manages customer accounts and sensitive financial data. They needed a complete security audit of their software application to uncover vulnerabilities and reduce their risk profile. My responsibility was to identify weak points in their codebase, reduce dependency-related vulnerabilities, and improve their communication protocols through SSL encryption.

## What did you do well when finding software vulnerabilities? Why is secure coding important?
I was especially thorough in the manual review, spotting logical flaws in user authentication, hardcoded secrets, and unsafe input handling. Secure coding is vital because poor security can result in data breaches, system downtime, and reputational damage. Secure practices ensure that data remains confidential and systems remain trustworthy.

## What part of the vulnerability assessment was challenging or helpful?
The manual review was the most intensive but also the most rewarding. It helped me understand how minor oversights—like unvalidated input or outdated libraries—can create exploitable paths for attackers. Static analysis tools like OWASP Dependency-Check were helpful in pinpointing vulnerable packages that might otherwise be overlooked.

## How did you increase layers of security, and what would you use in the future?
I applied multiple security layers, including code refactoring for safer logic flow, enforcing stronger access control, and implementing encrypted communications using a self-signed SSL certificate. In the future, I’d continue using tools like Dependency-Check and incorporate others like SonarQube or Burp Suite to get a broader perspective on vulnerabilities. I would also apply threat modeling to better prioritize mitigation strategies.

## How did you ensure the application was secure and functional after changes?
After each round of changes, I reran tests, verified Maven builds, and reviewed output logs to ensure no new issues were introduced. I also re-scanned the project with Dependency-Check to confirm that the vulnerability count was significantly reduced. The final count dropped from over 200 vulnerabilities to under 60, showing clear improvement.

## What tools or practices might help in the future?
Practices like input sanitization, avoiding hardcoded credentials, and using strong encryption libraries will always be foundational. Tools such as OWASP ZAP, SonarLint, and key management systems like HashiCorp Vault would further elevate future projects.

## What could you show employers from this project?
This project serves as a comprehensive example of my ability to conduct a full-cycle vulnerability assessment, apply best security practices, and produce clean, secure, and functional code. The documented improvement—from risk identification to mitigation—demonstrates technical depth, accountability, and professional readiness for software security roles.

## Future Applications
The skills I developed in CS 305 are highly transferable to software engineering, cybersecurity, and DevSecOps roles. Whether it’s identifying vulnerabilities, encrypting data transmission, or applying best practices for secure code, this course has provided a strong foundation in building and maintaining secure systems. These skills will serve me well in future work environments that require secure communication, reliable applications, and resilient infrastructure.

Thank you for visiting this repository! I hope it provides a clear representation of my software security knowledge and my ability to apply those skills in real-world scenarios.
