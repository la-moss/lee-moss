# Lee Moss — Azure/Terraform Incident Labs

Azure Infrastructure Engineer at UK Home Office | IaC & DevOps

I publish **repo-based incident labs** so you can sharpen real debugging instincts by spotting and fixing realistic Azure/Terraform misconfigurations — not just reading tutorials.

**Weekly loop:**  
Production-style ticket → intentionally broken repo → clone → investigate → identify gaps → fix → compare with my walkthrough.

No deployment required — simply run the Python HCL2 guardrail script to validate and surface unmet conditions.

### Start Here
- **Week 1 — When “Allowed” Traffic Still Can’t Leave the VNet**  
  https://github.com/la-moss/week-1

- **Week 2 — DR Failover That Works… Until You Actually Need It**  
  https://github.com/la-moss/week-2

- **Week 3 — Identity Looks Correct. Access Still Fails.**  
  https://github.com/la-moss/week-3

- **Week 3.5 — Automation Identities and the Illusion of Least Privilege**  
  https://github.com/la-moss/week-3.5

- **Week 4 — Private Endpoints, Private DNS, and the Lies They Tell You**  
  https://github.com/la-moss/week-4

- **Week 5 — The Cluster Is “Healthy” (Until You Need Telemetry)**  
  https://github.com/la-moss/Week-5

- **Week 6 — Security Guardrails That Pass… and Still Leave You Exposed**  
  https://github.com/la-moss/Week-6

- **Week 7 — CI/CD Is Green, but the Platform Isn’t**  
  https://github.com/la-moss/Week-7

- **Week 8 — Shared Terraform Modules as a Hidden Control Plane**  
  https://github.com/la-moss/Week-8

- **Week 9 — Routes Exist. Traffic Still Doesn’t Flow.**  
  https://github.com/la-moss/Week-9


### Generate Your Own Lab (AI-Powered)
Need a fresh production-style ticket + broken repo on demand?  
Supports any cloud provider and IaC tool (Azure, AWS, GCP, Terraform, etc.).  
➡️ **InfraTickets (Custom GPT):** [Generate incident lab](https://chatgpt.com/g/g-69087d89f1288191bc986d18be68aff8-iac-incident-lab-repo-ticket-generator)

### What You'll Practice
- Detecting & remediating networking misconfigurations (DNS, routes, NSGs, private endpoints, hub/spoke)
- Enforcing IAM controls (RBAC, least privilege, break-glass patterns)
- Validating DR/failover readiness + blast-radius limits
- Strengthening IaC guardrails (linting, policy checks, “plan isn’t proof”)
- Identifying Kubernetes (AKS) compliance & security gaps
- Operational rigour: logs, diffs, verification, change discipline
- Governance: policy-as-code, CI guardrails, drift detection
- Cost awareness: spending signals + pragmatic trade-offs

### Stay Connected
New incident lab every Monday + walkthroughs on LinkedIn:  
➡️ [linkedin.com/in/lam-ai](https://www.linkedin.com/in/lam-ai)

### Disclaimer
All content is built in a **personal sandbox**. No employer systems or data involved.  
All views are my own and not those of my employer.
