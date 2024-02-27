# Secrets Management:


| Feature/Tool         | Bitwarden (Paid)                                                                   | HashiCorp Vault                                                | AWS Secrets Manager                                        | Vaultwarden                             |
| -------------------- | ---------------------------------------------------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------- | --------------------------------------- |
| Deployment           | Cloud-based, self-hosted                                                           | Cloud-based, on-premises                                       | Cloud-based (AWS)                                          | Self-hosted                             |
| Target Users         | Individuals, small teams                                                           | Large organizations, enterprises                               | AWS users                                                  | Individuals, small teams                |
| Secret Types         | Passwords, notes, logins                                                           | Any type of secret (passwords, tokens, certificates, etc.)     | Any type of secret (passwords, tokens, certificates, etc.) | Passwords, notes, logins                |
| Auditing and Logging | Basic audit logs                                                                   | Detailed audit logs, RBAC                                      | Detailed audit logs, RBAC                                  | Basic audit logs                        |
| Integrations         | Limited integrations with password managers, security tools                        | Extensive integrations with CI/CD tools, cloud providers, etc. | Extensive integrations with AWS services                   | Limited integrations (community-driven) |
| IAM Integration      | No                                                                                 | Yes                                                            | Yes                                                        | No                                      |
| Pricing              | Individual ($10/month), Families ($3.33/month per user), Teams ($5/month per user) | Open source (Enterprise version available, pricing varies)     | Pay-per-use based on API calls and secret storage size     | Free (donations accepted)               |


-------------------------------------------------------------------------------


| Feature/Tool      | Gitleaks                                                     | GitGuardian                                                                                                                         |
| ----------------- | ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------- |
| Detection Scope   | Code, comments, commits, file paths                          | Code, comments, commits, file paths, pull requests, branches, issues, comments across various platforms (GitHub, GitLab, Bitbucket) |
| Supported Secrets | Wide range of common secrets (passwords, tokens, keys, etc.) | Extensive list of pre-defined secrets, custom secret detection capabilities                                                         |
| False Positives   | May require more tuning to manage false positives            | Generally lower false positive rate due to advanced detection methods                                                               |
| Integrations      | Limited integrations                                         | Extensive integrations with CI/CD tools, development platforms, security tools                                                      |
| Pricing           | Free and open-source, Self-Hosted                            | Free plan with limited features, paid plans with advanced functionalities, SaaS solution                                            |
# Code Security : 
## Software Composition Analysis (SCA) : 


| Feature/Tool            | Snyk (Free & Paid)                                                   | OWASP Dependency-Check (Open Source)     |
| ----------------------- | -------------------------------------------------------------------- | ---------------------------------------- |
| Deployment              | Cloud-based, self-hosted                                             | Self-hosted                              |
| Supported Languages     | Wide range of programming languages                                  | Wide range, but not as extensive as Snyk |
| Vulnerability Updates   | Automatic updates                                                    | Manual updates                           |
| Remediation Suggestions | Yes (including upgrade paths)                                        | No                                       |
| False Positives         | Lower rate due to continuous learning                                | Medium rate                              |
| Integrations            | Extensive integrations with CI/CD tools, development platforms, etc. | Limited integrations(has jenkins plugin) |
| Ease of Use             | User-friendly web interface, CLI                                     | CLI                                      |
| Pricing                 | Free plan with limited features, paid plans with additional features | Free                                     |



## SAST : 

| Feature/Tool            | SonarQube (Free & Paid)                                              | Snyk Code (Free & Paid)                                                            |
| ----------------------- | -------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| Focus                   | Primarily Code Quality, with Security as an add-on                   | Primarily Security, with some Development Features                                 |
| Supported Languages     | Wide range, including major programming languages                    | Wide range, including major programming languages                                  |
| False Positives         | May require more tuning to manage false positives                    | Generally lower false positive rate, due to focus on dependencies                  |
| Remediation Suggestions | Yes, basic suggestions                                               | Yes, detailed suggestions with upgrade paths and actionable steps                  |
| Integrations            | Extensive integrations with CI/CD tools, development platforms, etc. | Extensive integrations with CI/CD tools, development platforms, and security tools |
| Pricing                 | Free community edition, paid editions with additional features       | Free plan with limited features, paid plans with advanced functionalities          |
| Learning Curve          | Steeper learning curve due to broader functionalities                | Easier to use due to specific focus on security and dependencies                   |


# Container Security :

| Feature/Tool       | Snyk Container                                                                                                   | Trivy                                                                              | Docker Scout                                                                |
| ------------------ | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| Focus              | Broad Spectrum Security (Vulnerability scanning, misconfigurations, license compliance)                          | Vulnerability Scanning (OS packages, libraries, container configuration)           | Vulnerability Scanning (OS packages, libraries)                             |
| Analysis Scope     | Container images, Infrastructure as Code (IaC) files, Kubernetes manifests                                       | Container images, file systems                                                     | Container images                                                            |
| Supported Features | Vulnerability scanning, misconfiguration detection, license compliance, remediation guidance, CI/CD integrations | Vulnerability scanning, misconfiguration detection, SBOM generation, image signing | Vulnerability scanning, SBOM generation                                     |
| Ease of Use        | User-friendly interface, cloud-based                                                                             | CLI-based, requires some technical expertise                                       | User-friendly interface, cloud-based (limited free plan)                    |
| Pricing            | Free plan with limited features, paid plans with additional functionalities                                      | Free and open-source                                                               | Free plan with limited features, paid plans with additional functionalities |

# IaC Security :


| Feature                     | Checkov                     | Terrascan                            | Trivy                     |
| --------------------------- | --------------------------- | ------------------------------------ | ------------------------- |
| Compliance Checks           | Supports various frameworks | Limited built-in checks              | Not applicable            |
| Remediation Suggestions     | Specific suggestions        | Basic suggestions                    | Links & advice            |
| Pricing                     | Free                        | Free & Open-Source                   | Free & Open-Source        |
| VS Code Integration         | Yes                         | Planned (not available)              | CLI, extensions available |
| Jenkins Integration         | Yes                         | Yes                                  | Yes                       |
| Other Integrations          | Gitlab, Github              | Gitlab, Github, ArgoCD, Kubernetes.. | Popular options           |
| Cloud Provider Integrations | AWS, GCP, Azure, others     | AWS, GCP, Azure, others              | Primarily cloud-agnostic  |


