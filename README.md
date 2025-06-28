# CS-305
Welcome to the CS 305 repository! This repository contains a set of security-focused projects I developed as part of my CS 305 course at Southern New Hampshire University. Throughout this course, I explored secure coding principles, vulnerability assessment, and best practices for hardening applications against threats. This repository showcases my ability to identify, report, and remediate real-world software security vulnerabilities.

## About the Course
CS 305 focuses on the essential skills of software security in modern development. The course emphasizes secure design, identifying weaknesses in existing code, and implementing best practices to mitigate risks. Projects in this course required both technical analysis and professional documentation to simulate real-world software security scenarios.

Key topics in this course included:

-- Software Vulnerabilities – Discovering and analyzing flaws in source code.
-- Secure Coding Practices – Refactoring code to improve security posture.
-- Threat Mitigation – Applying encryption, access control, and input validation.
-- Static Analysis Tools – Using Maven Dependency-Check to locate vulnerable libraries.
-- Risk Reporting – Communicating findings to non-technical stakeholders effectively.

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
Briefly summarize your client, Artemis Financial, and its software requirements.
Artemis Financial is a fictional financial services company specializing in savings plans, insurance, and retirement services. The company requested a full security audit of its legacy software application, along with updated practices to improve secure communication and reduce vulnerabilities in its codebase and dependencies.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely?
I was particularly effective at identifying outdated dependencies and hardcoded credentials. I also recognized insufficient input validation and a lack of secure communication protocols. Secure coding is crucial because it prevents data breaches, protects user privacy, and upholds business reputation—especially in industries like finance, where trust is paramount.

## Which part of the vulnerability assessment was challenging or helpful to you?
The most challenging part was the manual code review. It required attention to detail and a deep understanding of the application’s logic. However, this process was also the most educational—it taught me how to spot insecure patterns that automated tools might miss.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by applying input validation, encrypting sensitive data, replacing outdated libraries, and removing hardcoded values. In future assessments, I would use tools like OWASP ZAP and Snyk, combined with regular static and dynamic code reviews to maintain layered defense strategies.

## How did you make certain the code and software application were functional and secure?
After refactoring the code, I performed Maven builds, tested the SSL certificate configuration, and validated that data loading and application features still functioned as intended. I reran the dependency scans to confirm that vulnerabilities had been reduced significantly without introducing new ones.
