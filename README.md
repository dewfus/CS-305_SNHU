# CS-305_SNHU

# Artemis Financial Security Assessment Reflection

This submission reflects my work with Artemis Financial, where I conducted a
security assessment and implemented secure coding practices. Below are my
reflections on the process and its impact.

## Client Summary
Artemis Financial is a fintech company focused on secure digital transactions
and financial data integrity. Their software required a thorough security
assessment to identify vulnerabilities and propose best practices for secure
development. The company sought help addressing potential risks in their web
application, particularly around data exposure, authentication, and secure
communication.

## Strengths in Vulnerability Detection
I successfully identified key vulnerabilities in Artemis’s application,
including improper SSL configuration and lack of cryptographic verification.
Detecting these issues is crucial because insecure code can lead to data
breaches, financial loss, and reputational damage. My work added value by
strengthening Artemis’s trustworthiness and compliance posture.

## Challenges and Insights
One challenge was debugging SSL keystore alias conflicts and ensuring proper
port configuration. This process helped me understand the nuances of secure
deployment and reinforced the importance of iterative testing. It also
sharpened my troubleshooting skills under pressure.

## Security Layers and Future Strategy
To increase layers of security, I implemented checksum and hash verification
endpoints and configured SSL for encrypted communication. In future
assessments, I’ll incorporate automated vulnerability scanning tools early in
the process and set up CI/CD pipelines with integrated security checks. I’ll
also prioritize threat modeling to anticipate risks before they manifest in
code.

## Functionality and Post-Refactor Checks
I verified functionality through endpoint testing and checksum/hash validation.
After refactoring the code, I re-ran security tests and manually reviewed the
application to ensure no new vulnerabilities were introduced. I also captured
screenshots to document secure output formatting and endpoint behavior.

## Resources and Tools
I used the following resources and tools:
- Spring Boot documentation for SSL and endpoint configuration
- OWASP guidelines for secure coding practices
- Codecademy’s Machine Learning path for understanding secure data handling
- Java libraries for SHA-256 and AES-256 encryption

These tools will be valuable in future assignments and professional roles.

## Portfolio Value for Employers
This assignment demonstrates my ability to assess real-world software for
security flaws, implement cryptographic solutions, and communicate findings
clearly. Future employers will see my technical rigor, ethical awareness, and
commitment to secure development—all essential traits for software engineering
and ML roles.
