# Artemis Financial Practices for Secure Software Report – Journal Reflection

Client Overview:
Artemis Financial is a consulting firm focused on delivering customized financial plans to its clients. As part of its initiative to modernize operations, Artemis sought to enhance the security of its web application to ensure secure communication and protect sensitive financial data.

Software Requirements:
The client requested improvements to secure data transmission through HTTPS, implement a checksum mechanism for verifying file integrity, and ensure all cryptographic practices complied with industry standards. This included encryption implementation, SSL certificate generation, and vulnerability testing.

Security Vulnerability Findings:
During the vulnerability assessment, I used tools like the OWASP Dependency-Check to identify known issues in the application’s third-party libraries. One of the strengths of my approach was following secure coding standards while refactoring the code. I also ensured encryption was implemented using AES-256, a widely accepted, secure algorithm. Secure code is essential to prevent data breaches, maintain client trust, and comply with regulations like GDPR or SOX.

Challenges & Helpful Aspects:
A challenging part of the assessment was configuring the suppression.xml to eliminate false positives in the static analysis results. However, this step was helpful in learning how to accurately interpret scanner results and avoid noise in security reports. Creating a self-signed SSL certificate with Java Keytool was another valuable experience, reinforcing how encryption and secure communications work in a real-world application.

Security Layer Enhancements:
I implemented multiple layers of security, including enabling HTTPS through a self-signed certificate, using AES encryption to compute checksums, and applying SHA-256 hashing. Going forward, I would continue using tools like OWASP, static code analyzers, and penetration testing utilities to assess and prioritize vulnerabilities.

Functional & Secure Validation:
To ensure the application worked securely and correctly, I ran it over HTTPS and verified the hash endpoint functionality. I used Maven build commands and dependency-check reports to confirm that no new vulnerabilities were introduced during the refactor.

Tools & Practices Used:
I utilized Eclipse IDE, Java Keytool, OWASP Dependency-Check, AES encryption, and SHA-256 hashing. These tools and practices align with industry best practices and can be applied in future security-sensitive projects.

Showcasing for Future Employers:
This project showcases my ability to identify software vulnerabilities, implement encryption, configure secure communication, and run automated security tests. I can present the final refactored code, the secure hash verification endpoint, and the vulnerability assessment reports to demonstrate my practical knowledge in secure software development.
