Hi there, I'm Larry, a passionate [GRC Engineer and Data Security Professional](https://www.linkedin.com/in/larry-wilkes-splunk-engineer/). I build compliance-as-code — Terraform infrastructure that proves NIST 800-53 controls with machine-readable, cryptographically signed evidence, not just checkbox documentation. Background in Cribl/Splunk observability engineering and 20 years in law enforcement/corrections, now focused on GRC engineering and cloud security.

**US Army Veteran | Cribl Certified 5X | Splunk Certified 2X | Certified GRC Engineer, Auditor Specialty (CGE-AUD)**

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)
![Cribl](https://img.shields.io/badge/Cribl-F26722?style=flat)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![NIST 800--53](https://img.shields.io/badge/NIST%20800--53-1B3A57?style=flat)
![OPA/Rego](https://img.shields.io/badge/OPA%2FRego-7D9D9C?style=flat)

**Currently building:** [cge-p-capstone](https://github.com/Larry-Wilkes-CyberCloud/cge-p-capstone) — a full Terraform + Rego + GitHub Actions GRC pipeline with signed evidence chain-of-custody across AWS and GCP.

<h2>🛡️ GRC Engineering Projects:</h2>

- <b>Flagship Project — Acme Health GRC Capstone</b> ([repo](https://github.com/Larry-Wilkes-CyberCloud/acme-health-grc-capstone))
  - [Full HIPAA-defensible compliance pipeline (Terraform, Rego, GitHub Actions, OSCAL) — wraps a real deployed AWS workload (VPC, Lambda, API Gateway, DynamoDB, S3) with a customer-managed KMS key, 5 OPA policies enforcing HIPAA Security Rule controls with 14/14 tests passing, a signed evidence pipeline (Cosign + S3 Object Lock), and a validated OSCAL component definition — plus a real production bug found and fixed along the way](https://github.com/Larry-Wilkes-CyberCloud/acme-health-grc-capstone/blob/main/WRITEUP.md)

- <b>Infrastructure as Code / Compliance Automation</b>
  - [Compliant S3 Bucket (Terraform, AWS) -- NIST 800-53 encryption, versioning, access controls](https://github.com/Larry-Wilkes-CyberCloud/cge-p-capstone#lab-23--compliant-s3-bucket-terraform-aws)
  - [Compliant GCS Bucket Module (Terraform, GCP) -- reusable, policy-enforced](https://github.com/Larry-Wilkes-CyberCloud/cge-p-capstone#lab-24--compliant-gcs-bucket-module-terraform-gcp)
  - [Immutable Evidence Vault (Terraform, AWS) -- S3 Object Lock, Cosign-signed evidence](https://github.com/Larry-Wilkes-CyberCloud/cge-p-capstone#lab-25--immutable-evidence-vault-with-cryptographic-signing-terraform-aws)
  - [Compliance Policies in Rego (OPA, GCP) -- policy-as-code, NIST 800-53, 8/8 tests passing](https://github.com/Larry-Wilkes-CyberCloud/cge-p-capstone#lab-33--compliance-policies-in-rego-opa-gcp)
  - [Conftest Policy Gate (OPA/Conftest, AWS) -- cross-cloud CI gate, fail-closed](https://github.com/Larry-Wilkes-CyberCloud/cge-p-capstone#lab-34--integrating-policy-as-code-with-terraform-via-conftest-aws)
  - [GRC Evidence Pipeline (GitHub Actions + AWS OIDC) -- keyless CI/CD, red/green PR proof](https://github.com/Larry-Wilkes-CyberCloud/cge-p-capstone#lab-43--building-a-grc-evidence-pipeline-aws--github-actions)
  - [Evidence Chain of Custody (Cosign, Sigstore) -- signed, tamper-proof evidence](https://github.com/Larry-Wilkes-CyberCloud/cge-p-capstone#lab-44--evidence-management--chain-of-custody-aws)
  - [AWS Security Baseline (CloudTrail, Terraform) -- audit logging, documented service restriction](https://github.com/Larry-Wilkes-CyberCloud/cge-p-capstone/tree/master/terraform/baselines/aws)
  - [GCP Security Baseline (Workload Identity Federation) -- keyless auth, live-verified](https://github.com/Larry-Wilkes-CyberCloud/cge-p-capstone/tree/master/terraform/baselines/gcp)
  - [OSCAL Component Definition (compliance-trestle, NIST 800-53) -- machine-readable evidence traversal](https://github.com/Larry-Wilkes-CyberCloud/cge-p-capstone/tree/master/oscal)
---
<h2>👨‍💻 Cybersecurity Projects:</h2>

- <b>Splunk App/CyberSentinel: Threat Hunting and Analysis</b>
  - [Threat Hunting and Analysis App](https://github.com/Larry-Wilkes-CyberCloud/CyberySentinel)
  - [Threat Detection Workflows](https://github.com/Larry-Wilkes-CyberCloud/Threat-Detection-Workflows)
 
- <b>CRIBL Projects</b>
   - [Cribl Stream in Action Syslog to S3 Elasticsearch](https://github.com/Larry-Wilkes-CyberCloud/Cribl-Stream-in-Action-Syslog-to-S3-Elasticsearch)    
   - [Cribl Search Essentials & Architecture Lab](https://github.com/Larry-Wilkes-CyberCloud/Cribl-Search-Lab)
 
- <b>Azure /Cloud Cybersecurity Projects</b>
  - [Live SOC/Honeynet in Azure](https://github.com/Larry-Wilkes-CyberCloud/Azure-Cloud-Soc)
  
- <b>ISO 27001 Projects</b>
    - [Information Asset Register Presentation](https://github.com/Larry-Wilkes-CyberCloud/IAR-Procedure)
    
- <b>Nessus Tenable Scans and Group Policy</b>
   - [Created basic, advanced, and advanced dynamic scans with Nessus and implemented group policy](https://github.com/Larry-Wilkes-CyberCloud/Nessus-Scans)
- <b>Data Loss Prevention</b>
  - [DLP blocking file rule for removable storage device](https://github.com/Larry-Wilkes-CyberCloud/Data-Loss-Prevention)
- <b>Information Security Awareness Campaign</b>
  - [IS Awareness Video](https://github.com/Larry-Wilkes-CyberCloud/Information-Security-Awareness/tree/main)
- <b>Social Engineering Investigation</b>
  - [Investigate E-mails sent in and report suspicious items](https://github.com/Larry-Wilkes-CyberCloud/Social-Engineering-Investigation)
  
---
<h2>👨‍💻 QA Automation Projects:</h2
                               
- **Playwright Projects**
    - [Amazon Cart Functionality Testing](https://github.com/Larry-Wilkes-CyberCloud/Amazon-Cart-Functionality)
    - [Amazon Search Functionality Testing](https://github.com/Larry-Wilkes-CyberCloud/Amazon-Search-Functionality-Project)
    - [This project is aimed to design a test suite for SQA](https://github.com/Larry-Wilkes-CyberCloud/playwright-tests-sqa)
  
- **Manual API Testing Using Postman**
    - [Policy Payment Options Validation using Postman](https://github.com/Larry-Wilkes-CyberCloud/Policy-Payment-Options)
    - [Vehicle VIN validation using Postman](https://github.com/Larry-Wilkes-CyberCloud/Vin-Validation-using-Postman)
    - [Driver Validation API using Postman](https://github.com/Larry-Wilkes-CyberCloud/Larry-Wilkes-CyberCloud-Driver-Validation-Using-Postman)
    - [Vehicle Registered State Validation using Postman](https://github.com/Larry-Wilkes-CyberCloud/Vehicle-Registered_State-Validation)
  
- **Automation API Testing Using Postman**
    - [Driver API Automation Validation using Postman](https://github.com/Larry-Wilkes-CyberCloud/Driver-API-Automation)
---
<h2>🤳 Connect with me:</h2>

[<img align="left" alt="Larry Wilkes | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />](https://www.linkedin.com/in/larry-wilkes-splunk-engineer/)
