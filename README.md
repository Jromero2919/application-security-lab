# application-security-lab
Hands-on cybersecurity project analyzing vulnerable applications using Snyk, OWASP tools, and secure development practices.

🔐 Cyber-Demo: Application Security Lab

Hands-on AppSec project focused on performing SAST, SCA, and vulnerability remediation on intentionally insecure applications including OWASP Juice Shop and OWASP NodeGoat.
This project demonstrates practical experience with secure coding analysis, dependency risk management, and DevSecOps tooling.

🛠 Tech Stack & Tools

Snyk (SAST, SCA, IaC)

Node.js, npm

Docker, MongoDB

Git/GitHub Security (Dependabot, secret scanning)

OWASP Juice Shop, NodeGoat

🔍 Security Work Performed

Ran SAST scans using Snyk Code to identify insecure code patterns, injection vectors, crypto misuse, and auth issues.

Performed SCA dependency analysis to detect outdated packages, high/critical CVEs, and vulnerable transitive dependencies.

Executed vulnerability triage: categorizing issues by severity, exploitability, and impact using CVSS data.

Applied remediation by upgrading risky libraries, removing deprecated packages, and validating fixes through re-scans.

Reviewed OWASP Top 10 categories present in both apps (XSS, IDOR, Broken Auth, Insecure Deserialization, etc.).


🚀 Running the Vulnerable Apps
Juice Shop
git clone https://github.com/juice-shop/juice-shop
cd juice-shop
npm install
npm start

NodeGoat (with Docker)
git clone https://github.com/OWASP/NodeGoat
cd NodeGoat
docker-compose up

🧠 Skills Demonstrated

Static Application Security Testing (SAST)

Software Composition Analysis (SCA)

Secure dependency management

DevSecOps scanning workflows

Vulnerability triage & remediation

Understanding of OWASP Top 10

📘 Summary

This project showcases technical capability in scanning, analyzing, and remediating application security risks using modern AppSec tooling. It supports my transition from QA/Release Engineering into Cybersecurity and DevSecOps.
