## Lee Moss — Production Incident Labs  
Azure Infrastructure Engineer (UK Home Office) | Kubernetes, IaC, DevOps  

I publish **weekly repo-based incident challenges** that simulate real SEV-style failures.

Some run live in Kubernetes (Kind-based).  
Others focus on Azure/Terraform platform reasoning.

You clone a broken repo, investigate real signals, identify root cause, implement fixes, and validate behaviour under pressure — like a live platform incident.

---

### Weekly Loop

Ticket → broken environment → deploy → investigate → fix → verify → compare with walkthrough.

---

### Start Here

- **Week A — Auth Failures Across Endpoints (Kubernetes Runtime Incident)**  
  https://github.com/la-moss/Kubernetes-Auth-failures-across-endpoints  

- **Week 1 — When "Allowed" Traffic Still Can't Leave the VNet**  
  https://github.com/la-moss/week-1  

- **Week 4 — Private Endpoints, Private DNS, and the Lies They Tell You**  
  https://github.com/la-moss/week-4  

- **Week 8 — Shared Terraform Modules as a Hidden Control Plane**  
  https://github.com/la-moss/Week-8  

- **Week 9 — Routes Exist. Traffic Still Doesn't Flow.**  
  https://github.com/la-moss/Week-9  

Full archive: https://github.com/la-moss

---

### What You'll Practice

- Kubernetes reliability and incident debugging  
- Service resilience: timeouts, retries, readiness, rollout safety  
- Networking diagnostics (DNS, routes, hub/spoke, private endpoints)  
- IAM/RBAC and least-privilege controls  
- DR/failover readiness and blast-radius limits  
- IaC design trade-offs and platform coupling  
- Operational discipline: logs, diffs, verification, change control  

---

### Foundation (Legacy Track)

Earlier labs focused on **Azure/Terraform guardrails and static validation** — building audit and enforcement instincts before runtime.

Those repos remain available in the archive.

---

### Generate Your Own Lab (AI-Powered)
Need a fresh production-style ticket + broken repo on demand?  
Supports any cloud provider and IaC tool (Azure, AWS, GCP, Terraform, etc.).  
➡️ **InfraTickets (Custom GPT):** [Generate incident lab](https://chatgpt.com/g/g-69087d89f1288191bc986d18be68aff8-iac-incident-lab-repo-ticket-generator)

---

New incident lab every Monday + walkthroughs on LinkedIn:  
https://linkedin.com/in/lam-ai  

All content is built in a personal sandbox.  
No employer systems or data involved.  
All views are my own.
