# CS305-Final-


This repository includes my completed Artemis Financial Practices for Secure Software Report, created for CS 305. The project demonstrates my ability to refactor code securely, apply cryptographic protections, and run vulnerability scans.

Reflection

Client and Requirements
Artemis Financial, a financial services company, needed secure communications and protection of sensitive customer data. They asked for integrity checks, encrypted transport, and mitigation of software supply-chain risks.

Strengths and Importance
I implemented SHA-256 for data integrity, enabled HTTPS with TLS 1.2/1.3, and added OWASP Dependency-Check. Coding securely is critical because it prevents data leaks, maintains trust, and supports compliance.

Challenges and Helpful Parts
TLS certificate configuration was the most difficult step, while the automated dependency scanning was especially useful and repeatable.

Layers of Security and Future Tools
I combined encryption, checksums, and dependency scanning. In future work I would continue using automated tools like OWASP and Snyk alongside manual code reviews.

Testing and Verification
I verified the app by running over HTTPS, checking checksum responses, and confirming no new vulnerabilities appeared after refactoring.

Resources and Practices
OWASP Dependency-Check, SHA-256 hashing, and PKCS#12 keystore setup were key resources. Practices like avoiding hardcoded secrets and restricting protocols will carry over into future work.

Value to Employers
This artifact shows I can assess vulnerabilities, apply cryptography correctly, configure TLS, and integrate security scanning into builds—skills directly applicable to secure software development.
