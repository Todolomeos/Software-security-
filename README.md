1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a company that creates personalized financial plans for its customers, including savings, retirement, investments, and insurance. They wanted to modernize their software and make sure their web application was secure. The main issue they needed help with was adding secure communication, encryption, and a checksum feature to protect client data and verify file integrity.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I did well identifying outdated dependencies and fixing issues that could lead to security risks. I updated the tools, added encryption, and made sure the application used HTTPS. Coding securely is important because it protects sensitive information and prevents attacks. Strong security helps a company build trust with customers, avoid data breaches, and keep its systems stable and reliable.

3. Which part of the vulnerability assessment was challenging or helpful to you?
The most challenging part was getting the OWASP Dependency‑Check tool to work correctly. The older version could not connect to the NVD database, and I had to update the plugin and add my API key. This process was helpful because it taught me how to troubleshoot security tools and understand how dependency scanning works in real projects.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased security by adding AES‑256 encryption, SHA‑256 hashing, generating certificates, switching the application to HTTPS, and scanning dependencies for known vulnerabilities. In the future, I would continue using tools like OWASP Dependency‑Check, NVD, and secure coding guidelines to find vulnerabilities and choose the best ways to fix them.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I made sure the application was functional by running the Spring Boot server and checking that it started without errors. I tested the HTTPS connection and verified the checksum endpoint worked correctly. After refactoring, I ran the dependency‑check scan again to confirm that no new vulnerabilities were introduced and that all security updates were successful.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I used OWASP Dependency‑Check, NVD API keys, SSL/TLS certificates, AES‑256 encryption, SHA‑256 hashing, and secure coding practices like validation and refactoring. These tools and habits will help me in future projects because they are commonly used in real‑world software development to keep applications safe and maintainable.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I could show employers my secure Spring Boot application, the encryption and hashing features I implemented, the certificate setup for HTTPS, and the dependency‑check report. I can also show my documentation and README to demonstrate that I can explain my work clearly, follow security best practices, and troubleshoot real security issues.
