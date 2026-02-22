# CS-305 Software Security

This repository contains portfolio artifacts and security analysis projects completed in CS-305 at Southern New Hampshire University.

Topics covered include:

- Secure coding practices
- Cryptographic hashing (SHA-256)
- HTTPS configuration with SSL certificates
- OWASP Dependency-Check vulnerability analysis
- Secure Software Development Lifecycle (Secure SDLC)

---

## Module Eight Reflection

### Client Summary

Artemis Financial is a financial services company that required improvements to its application security. The organization needed to strengthen data integrity and secure communications while addressing dependency vulnerabilities identified through static analysis tools.

The primary objective was to refactor the application to follow secure coding standards and verify compliance with modern security practices.

### Secure Coding and Value of Security

When vulnerabilities were identified, I implemented SHA-256 hashing for integrity verification and configured HTTPS using SSL certificates to protect data in transit. Secure coding is essential because financial applications process sensitive data that must be protected against tampering, interception, and exploitation.

Strong software security protects customer trust, prevents financial loss, and supports regulatory compliance.

### Challenges and Learning

One of the most challenging aspects was troubleshooting SSL configuration and resolving OWASP Dependency-Check plugin issues. However, this process helped me better understand vulnerability analysis tools and how secure configurations function within Spring Boot applications.

### Increasing Layers of Security

Security layers were increased by:

- Implementing SHA-256 cryptographic hashing  
- Enabling HTTPS with TLS encryption  
- Running OWASP Dependency-Check scans  
- Comparing before-and-after vulnerability reports  

In the future, I would incorporate automated CI/CD security scanning and additional static analysis tools.

### Verifying Functionality and Security

After refactoring, I verified that:

- The application compiled successfully
- The HTTPS endpoint functioned correctly
- No new vulnerabilities were introduced
- The dependency scan results remained consistent

This ensured the software remained both functional and secure.

### Tools and Practices Used

- Java 17
- Spring Boot
- Maven
- OWASP Dependency-Check
- SHA-256 cryptographic hashing
- SSL/TLS configuration

### Portfolio Value

This artifact demonstrates my ability to:

- Perform a secure software refactor
- Implement cryptographic protections
- Configure HTTPS properly
- Conduct vulnerability analysis using industry tools
- Apply Secure SDLC principles

It reflects practical software security skills relevant to real-world development environments.
