# Secrets Management:
|  | Price | Authentication | Auditing & Logging | IAM Integration |
| :--- | :--- | :--- | :--- | ---- |
| Hashicorp Vault | [Paid](https://www.hashicorp.com/products/vault/pricing), with various licensing options<br>  | Advanced options like LDAP, SAML, OIDC | Detailed logs, audit trails | Integrates with major IAM providers |
| VaultWarden(Bitwarden) | Free, Open-Source | Basic username/password, API tokens | Basic logging | Limited IAM integration options |


|  | Price | Installation | Focus | Features | Ease of Use |
| :--- | :--- | :--- | :--- | ---- | ---- |
| Gitleaks | Free, Open-source | self-hosting and manual configuration | detecting secrets in Git repositories | Limited to detection and output formats | Requires technical expertise to install, configure, and interpret results |
| GitGuardian | [Paid](https://www.gitguardian.com/pricing) | SaaS solution | secrets detection, code vulnerabilities, malware, and infrastructure misconfigurations. | Real-time scanning, advanced alerting, incident management, and integrations with CI/CD pipelines and security tools. | Nice UI, easier to use for less technical users. |


# Code Security : 
## SCA : 
|  | Price | Detection Methods | Features | Ease of Use |
| :--- | :--- | :--- | :--- | :--- |
| Snyk | [Freemium (limited features)](https://snyk.io/plans/) | Pattern matching, machine learning, public vulnerability databases | Continuous integration integration, container image scanning, license compliance, remediation guidance | User-friendly web interface, CLI |
| OWASP Dependency Check | Free | Pattern matching, public vulnerability databases | Basic scanning, reporting | CLI |
| Dependency-Track | Free | Pattern matching, public vulnerability databases, custom rules | Continuous integration integration, container image scanning, vulnerability prioritization, license compliance, remediation guidance | Web interface, CLI |
| WhiteSource Bolt | Freemium (limited features) | Machine learning, public vulnerability databases, custom rules | Continuous integration integration, container image scanning, license compliance, remediation guidance, risk scoring | Web interface, CLI |


## SAST : 
|      | Price     | Detection Methods     | Features     | Ease of Use     |
|:-----|:-----|:-----|:-----|:-----|
| SonarQube     | [Free & Paid versions](https://www.sonarsource.com/products/sonarqube/downloads/)     | Static code analysis, taint analysis, control flow analysis     | Code quality analysis, security hotspot detection, remediation guidance, reporting     | User-friendly web interface, CLI     |
| Snyk     | [Freemium (limited features), Paid](https://snyk.io/plans/)     | Static code analysis, machine learning, public vulnerability databases     | Continuous integration integration, container image scanning, vulnerability prioritization, remediation guidance, SBOM generation     | User-friendly web interface, CLI     |
| Checkmarx CxOne     | Paid     | Static code analysis, machine learning, proprietary algorithms     | Extensive reporting, vulnerability prioritization, remediation guidance, policy management, custom rules     | User-friendly web interface, CLI     |
| Veracode     | Paid     | Static code analysis, machine learning, proprietary algorithms     | Extensive reporting, vulnerability prioritization, remediation guidance, policy management, custom rules     | User-friendly web interface, CLI     |

# Container Security :
| Feature | Trivy | Snyk Container | Docker Scout | Aqua Security | Anchore Enterprise |
| ---- | ---- | ---- | ---- | ---- | ---- |
| Pricing | Free | [Freemium (limited features), Paid](https://snyk.io/plans/) | Free | Paid | [Paid](https://anchore.com/pricing/) |
| Supported Features | Vulnerability scanning, misconfiguration scanning, image analysis, license compliance | Vulnerability scanning, misconfiguration scanning, container image scanning, license compliance | Vulnerability scanning, misconfiguration scanning, container image scanning, image signing, runtime protection | Extensive vulnerability scanning, misconfiguration scanning, container image scanning, runtime protection, compliance enforcement | Extensive vulnerability scanning, misconfiguration scanning, container image scanning, runtime protection, compliance enforcement, SBOM generation |
| Detection Methods | Public vulnerability databases, pattern matching | Public vulnerability databases, machine learning | Public vulnerability databases, pattern matching | Machine learning, public vulnerability databases, proprietary algorithms | Public vulnerability databases, machine learning, proprietary algorithms |
| Ease of Use | CLI, simple integration | User-friendly web interface, CLI | CLI | User-friendly web interface, CLI | User-friendly web interface, CLI |


# IaC Security :
| Feature | TerraScan | Snyk IaC | Checkov | Trivy |
| ---- | ---- | ---- | ---- | ---- |
| Open Source | Yes | Yes (Limited features) | Yes | Yes |
| Pricing | Free | Freemium (limited features), Paid | Free, Paid | Free |
| Supported IaC Languages | Terraform, CloudFormation, ARM Templates, Kubernetes manifests | Terraform, CloudFormation, Helm charts, Kubernetes manifests | Terraform, CloudFormation, AWS SAM, Kubernetes manifests, Serverless Framework, Helm charts, Bicep, OpenAPI, Dockerfile | Kubernetes manifests, Dockerfiles |
| Detection Methods | Static analysis, policy-based rules | Static analysis, machine learning | Static analysis, policy-based rules | Vulnerability scanning, static analysis |
| Features | Vulnerability scanning, misconfiguration detection, policy compliance, security best practices checks | Vulnerability scanning, misconfiguration detection, policy compliance, security best practices checks, container image scanning | Vulnerability scanning, misconfiguration detection, policy compliance, security best practices checks, IaC file editing | Vulnerability scanning, misconfiguration detection, SBOM generation |
| Ease of Use | CLI, simple integration | User-friendly web interface, CLI | CLI, web interface | CLI |


