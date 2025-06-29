# CS305: Software Security
## Client Overview and Software Needs
My client, Artemis Financial, is a consulting company that creates personalized financial plans for clients, including retirement, investments, savings, and insurance. The company wanted to modernize its software systems and improve the security of its RESTful web application. They engaged Global Rain, where I work as a developer on the agile scrum team, to assess and strengthen the security of their software application. Specifically, they asked us to identify and mitigate vulnerabilities to protect sensitive financial data from external threats.

## Addressing Security Vulnerabilities
One of the things I did well was thoroughly inspecting the codebase for insecure coding practices and implementing updates to increase overall security. I focused on best practices like input validation, avoiding hard-coded credentials, and using strong cryptographic algorithms like SHA-256. Coding securely is important because it protects sensitive data, builds user trust, and reduces the risk of breaches or financial loss. Secure software adds value by minimizing liability, maintaining client confidence, and aligning with industry regulations.

## Challenges and Assessment Insights
One of the most challenging aspects of the vulnerability assessment was identifying false positives in security scan results and understanding which issues posed real risks. At the same time, it was helpful to use structured scanning tools and OWASP guidelines to prioritize the most critical vulnerabilities. This experience sharpened my ability to separate surface-level issues from deeper threats.

## Strengthening Security and Mitigation Techniques
I increased layers of security by applying secure hashing for data integrity, removing hard-coded secrets, and ensuring role-based access was enforced where needed. In the future, I would use tools like OWASP ZAP, dependency-checkers, and static code analysis to assess vulnerabilities and inform mitigation strategies. I would also stay current with CVE databases and NIST guidelines.

## Testing Functionality and Ensuring Security
After refactoring the code, I verified the application’s functionality using unit tests and ensured no new vulnerabilities were introduced by re-running automated security scans. I also reviewed secure coding guidelines and tested edge cases to validate data input and output integrity. These steps helped ensure the application remained both secure and functional.

## Helpful Tools and Practices
Some resources and practices I found helpful included the OWASP Top 10, SHA-256 for hashing, and secure API design patterns. Additionally, automated tools like Maven Dependency-Check helped identify outdated or risky dependencies. These will be valuable in future security-related development tasks.

## Showcasing Skills to Employers
This assignment gave me a strong example of secure software development and vulnerability assessment. I would show future employers my vulnerability assessment report, the refactored secure codebase, and my ability to use security tools and practices to improve real-world applications. It demonstrates my problem-solving skills, attention to detail, and readiness to handle secure software projects in professional environments.
