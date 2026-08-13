Hi, I'm Adeyemi 👋
Cybersecurity Analyst | Penetration Tester | SOC Analyst
Cybersecurity graduate — Abiola Ajimobi Technical University, Ibadan, Nigeria

- 🛡️ Cisco CyberOps Associate certified | Google Cybersecurity Certificate | CEH-trained
- 🎯 Ubuntu Bridge Initiative (UBI) Cyber Core Program — Associate, Ethical Hacking track
- 💼 Cybersecurity experience: GNT Nigeria (Cybersecurity Trainee) · Klemweb (Cybersecurity Intern)
- 🔍 Hands-on with SIEM monitoring, EDR/firewall log analysis, incident triage & escalation, MITRE ATT&CK mapping
- 🧰 Tools: Nmap, Burp Suite, Metasploit, Wireshark, Splunk, IBM QRadar, Kali Linux, Terraform, AWS CLI
- 🌱 Currently deepening: Active Directory enumeration (BloodHound, Kerberoasting); Linux and cloud (AWS IAM) privilege escalation

## 🔧 Featured Work

**[AWS IAM Privilege Escalation → Remediation](https://github.com/adeyemisodiq/ubi-stage7-iam-privesc)**
UBI Advanced Stage project. Cloud lab exercise: chained IAM misconfigurations (role enumeration → `PassRole` → Lambda execution) to escalate from a low-privilege role to a protected S3 secret, validated with 4 CloudTrail-evidenced edges. Remediated with a least-privilege Terraform fix — split execution roles plus a scoped `PassedToService` condition — verified by paired positive/negative tests, with full teardown and residual-resource verification.

**[Secure Multi-Tier Deployment on AWS — PrestaShop](https://github.com/adeyemisodiq/prestashop-aws-deployment)**
End-to-end AWS deployment of an e-commerce platform across two isolated tiers: EC2 (Apache/PHP application server) and a separate RDS MySQL instance, with security groups scoped so the database accepts traffic only from the application server's own security group — not a broad CIDR range. Documents a real network-troubleshooting diagnosis: traced a DB connection failure from a generic timeout down to an overscoped security group rule, then corrected it under least-privilege principles. Fully within AWS Free Tier.

**[Recon Engine](https://github.com/adeyemisodiq/recon-engine-)**
Python reconnaissance engine — UBI Advanced Stage project. 45 passing fixture tests, 16-deliverable submission package, live discovery chain executed against an authorized lab target (foothold flag captured).

**[Exploit Chain as Code — Command Injection to Root](https://github.com/adeyemisodiq/ubi-stage6-exploit-chain)**
UBI Advanced Stage project. Fully automated Python exploit chain: unauthenticated OS command injection → SSH pivot around a `NoNewPrivileges` restriction → tar wildcard argument injection for root privilege escalation. 5/5 reliability across clean-snapshot runs, 10/10 automated pytest suite, verified negative retest against a patched target, and root-cause remediation (not payload filtering) for both vulnerabilities.

**[Sankofa Digital — Penetration Test](https://github.com/adeyemisodiq/sankofa-legacy-admin-pentest)**
Full engagement chain: SQL injection → JWT `alg:none` bypass → SSRF → IMDSv1 credential theft. Formal writeup with findings and remediation.

**[PasswordStore Smart Contract Audit](https://github.com/adeyemisodiq#)**
Security audit — 2 High-severity findings (on-chain password visibility, missing access control) + 1 Informational. Formatted report included.

**[DFIR Capstone](https://github.com/adeyemisodiq#)**
Full forensic analysis of a simulated compromise — five formal deliverables covering incident timeline, evidence handling, and reporting.

**[Fraud Detection — ML on PaySim Dataset](https://github.com/adeyemisodiq#)**
Final Year Project: transaction fraud detection using Random Forest (F1 ~97.65%) and SVM (F1 ~82.22%), with SMOTE applied post-split to handle class imbalance.

📫 Connect: [LinkedIn](https://linkedin.com/in/adeyemi-adegbite-3152882b0) · Ibadan, Nigeria
