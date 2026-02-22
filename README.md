Module Eight Reflection

During this course, I worked with a fictional client, Artemis Financial, a financial services company that needed improvements to the security of its software application. The main concern was protecting sensitive financial data and ensuring secure communication between systems. The goal was to identify vulnerabilities in the application and refactor it to follow modern secure coding standards.

One thing I did well during the vulnerability assessment was carefully reviewing the OWASP Dependency-Check results and taking the time to understand the findings instead of simply ignoring warnings. I implemented SHA-256 hashing to help support data integrity and configured HTTPS using SSL certificates to encrypt communication between systems. Secure coding is especially important in financial systems because even small vulnerabilities can lead to data breaches, financial loss, and damage to customer trust. Strong security practices help maintain stability and credibility for a company.

One of the more challenging parts of this project was configuring SSL correctly and troubleshooting issues with the OWASP plugin when scans failed due to configuration or dependency problems. Although it was frustrating at times, working through these issues helped me better understand how security tools function within a Spring Boot application and how layered security works in real-world development. It also gave me more confidence working through technical problems independently.

To increase layers of security, I implemented cryptographic hashing, enabled TLS encryption for HTTPS communication, and performed repeated dependency scans to verify improvements. In future projects, I would expand this approach by integrating automated security testing into a CI/CD pipeline and using additional static analysis tools to continuously monitor for vulnerabilities.

After refactoring the application, I verified that the program compiled successfully, that the secure HTTPS endpoint functioned properly, and that no new vulnerabilities were introduced during the changes. Running before-and-after scans confirmed that security improvements did not negatively impact functionality.

Throughout this assignment, I used Java 17, Spring Boot, Maven, OWASP Dependency-Check, SHA-256 hashing, and SSL/TLS configuration. These tools and practices will continue to be valuable in my future development work.

Overall, this artifact reflects my ability to analyze vulnerabilities, refactor code securely, configure encrypted communications, and apply Secure SDLC principles in a practical setting.
