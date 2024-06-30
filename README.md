# CS305
Artemis Financial Practices for Secure Software Report

## Client Overview
**Artemis Financial** is a fictitious company that requires an assessment of their software security. The primary issue addressed in this part of the course was identifying and mitigating security vulnerabilities within their software systems to ensure a strong protection against potential external threats and interal errors resusulting in the release of sensative data.

## Summary of Actions Taken
1. **Identifying Vulnerabilities:** Conducted a thorough assessment of the client's software to uncover security weaknesses.
2. **Enhancing Security Layers:** Implemented stronger security to protect against identified vulnerabilities.
3. **Ensuring Functionality and Security:** Refactored the codebase to improve security while maintaining functionality, followed by testing to ensure no new vulnerabilities were introduced.

## Importance of Secure Coding
Secure coding is crucial as it helps prevent unauthorized access, data breaches, and other security threats. Implementing secure software practices enhances the company’s reputation, builds trust with clients, and protects sensitive information.

## Challenges and Learning Points
The vulnerability assessment process presented challenges in accurately identifying and mitigating all potential security issues. However, it provided valuable insights into the importance of a structured approach to security and the benefits of thorough testing and validation.

## Security Enhancements
- **Algorithm Cipher:** Recommended and implemented AES-256 for its strong protection against brute-force attacks and compliance with industry regulations.
- **Certificate Management:** Generated and deployed (self signed) SSL certificates to encrypt communications.
- **Refactoring Code:** Introduced a dedicated service class for hashing logic, ensuring separation of concerns and improved scalability.

## Future Assessment Tools and Techniques
For future vulnerability assessments, tools such as OWASP ZAP and dependency-check reports will be extreamly helpful to identify and prioritize mitigation techniques in Java programs. Althought many package managers in other languages today come with built in dependency checkers like NPM and Cargo. Continuous integration of security practices will be maintained to ensure ongoing protection.

## Ensuring Functionality and Security
After refactoring the code, testing, including functional and build testing, was conducted to ensure the application remained secure and fully functional. Dependency-check reports were used to verify the absence of new vulnerabilities.

## Useful Resources and Tools
- **Java Security Standard Algorithm Names:** For selecting appropriate cryptographic algorithms.
- **PCI DSS and GDPR Compliance Guidelines:** Ensuring compliance with industry standards.
- **Investopedia and Red Hat Articles:** For understanding cryptographic hash functions and the history of encryption.

## Demonstrating Skills to Future Employers
This assignment showcases my ability to:
- Conduct thorough security assessments.
- Implement robust security measures.
- Refactor code for improved security and maintainability.
- Use industry-standard tools and practices to ensure software security.

