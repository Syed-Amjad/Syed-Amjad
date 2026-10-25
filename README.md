# Hi, I'm Syed Amjad Ali 👋

### DevSecOps Engineer · Kubernetes Security · Linux Hardening & Firewalls · GitOps

I secure Linux servers, Kubernetes clusters and cloud infrastructure, **and I prove the controls work.**
5+ years designing, automating and securing production infrastructure on AWS, Azure and large on-prem Linux fleets.

> **Verified, not asserted.** If I say something is blocked, I show you it being blocked: real attacks, real logs, measured results.

📍 Karachi, Pakistan (UTC+5) · 💼 Available for freelance projects · 🌐 [syedamjad.com](https://syedamjad.com/)

---

## 🛠️ What I can do for you

| Service | What you get |
|---|---|
| 🛡️ **Linux server hardening** | CIS Benchmark remediation as Ansible automation, key-only SSH, firewalld / iptables / ipset, Fail2Ban, before-and-after scan evidence |
| ☸️ **Kubernetes security** | Pod Security Admission, least-privilege RBAC, default-deny NetworkPolicy, Kyverno admission policies, Falco runtime detection |
| 🔐 **Software supply chain security** | SBOMs, Trivy severity gates, keyless Cosign image signing in CI and signature verification at admission |
| 🚀 **GitOps & delivery** | ArgoCD app-of-apps, Helm and Kustomize, Istio mTLS and canary releases, Prometheus / Grafana / Loki with alerts that really fire |
| ☁️ **Cloud & Infrastructure as Code** | Terraform on AWS and Azure, high-availability web platforms, S3 + CloudFront, WAF, backups with tested restores |
| 🔥 **Firewall automation** | Policy-as-code firewall management across Linux fleets: safe apply, rollback, drift detection and automatic access expiry |

---

## ⭐ Featured projects

### 🔒 [Zero-Trust Kubernetes Supply Chain](https://github.com/Syed-Amjad/zerotrust-gitops) · [case study](https://syedamjad.com/projects/zero-trust-supply-chain/)
Seven independent enforcement layers (signed images, Kyverno admission, Pod Security, NetworkPolicy, Istio mTLS and egress control, Falco), all deployed by ArgoCD.
**Seven attacks were run against it on purpose: six held, and the seventh failed silently. Finding out why is documented step by step.**
`k3s` `Kyverno` `Cosign` `Trivy` `Istio` `Falco` `ArgoCD` `Terraform` · CI pipeline: [supply-chain-app](https://github.com/Syed-Amjad/supply-chain-app)

### 🚀 [GitOps Delivery Platform with Service Mesh](https://github.com/Syed-Amjad/platform-gitops) · [case study](https://syedamjad.com/projects/gitops-delivery-platform/)
Git is the only way in: ArgoCD app-of-apps, Istio canaries counted rather than assumed, metrics and logs correlated in Grafana.
**A manual change was reverted by ArgoCD in 4 seconds. 17 defects were found during the build, 16 fixed, each one written up.**
`ArgoCD` `Istio` `Helm` `Kustomize` `Prometheus` `Loki` `Vault` · App source: [k8s-platform-app](https://github.com/Syed-Amjad/k8s-platform-app)

### 🏗️ [Secure High-Availability Web Platform on AWS](https://github.com/Syed-Amjad/secure-ha-web-platform) · [case study](https://syedamjad.com/projects/secure-ha-web-platform/)
Multi-AZ, load-balanced, MySQL GTID replication, encrypted backups and a WAF, built with Terraform and hardened with Ansible, then deliberately broken.
**Losing a web node caused 0 seconds of full outage; a full restore from S3 took 24 seconds end to end.**
`Terraform` `Ansible` `AWS` `MySQL` `WAF`

### 🛡️ [Secure EC2 Linux Hardening (RHEL)](https://github.com/Syed-Amjad/secure-ec2-linux-hardening) · [case study](https://syedamjad.com/projects/ec2-linux-hardening/)
Defence in depth for a production server: least-privilege IAM, Security Groups, firewalld rules, key-only SSH, Fail2Ban and CloudWatch alarms.
`RHEL` `firewalld` `Fail2Ban` `SSH` `CloudWatch`

### ☁️ [Static Website on AWS with Terraform](https://github.com/Syed-Amjad/aws-static-site-s3-cloudfront-terraform)
Private S3 origin behind CloudFront with Origin Access Control, HTTPS via ACM and least-privilege IAM. No public buckets, no wildcard IAM, no HTTP.
`Terraform` `S3` `CloudFront` `ACM`

---

## 🏢 Production work (client code is private; case studies are public)

- **[Firewall Automation & Governance Platform](https://syedamjad.com/projects/firewall-automation-platform/):** centralised, database-driven host firewall policy for a production Linux fleet. **Deployments 3x faster**, with safe apply, rollback and automatic revocation of temporary access.
- **[SSL Certificate Lifecycle Automation](https://syedamjad.com/projects/ssl-certificate-automation/):** issue, install, disable and revoke Let's Encrypt certificates across multi-tenant nginx hosts, with private keys kept out of the web tier.
- **[Node Configuration Inventory & Server Scoring](https://syedamjad.com/projects/configuration-inventory/):** a read-only collector that inventories and scores every server in a Linux fleet over SSH.
- **[Firewall Fleet Orchestrator](https://syedamjad.com/projects/firewall-fleet-orchestrator/):** central policy, SHA256 drift detection and Ansible rollout across an EC2 fleet.

---

## 🧰 Tech stack

**Security:** Kyverno · Falco · Trivy · Cosign / Sigstore · Istio mTLS · OPA · CIS Benchmarks · OpenSCAP · Fail2Ban · iptables / ipset · firewalld · Cloudflare & AWS WAF
**Kubernetes & GitOps:** Kubernetes (kubeadm, k3s, EKS, AKS) · Helm · Kustomize · ArgoCD · Istio · Vault
**Cloud & IaC:** AWS · Azure · Terraform · Ansible
**CI/CD:** GitHub Actions · Jenkins · GitLab CI
**Observability:** Prometheus · Grafana · Loki · CloudWatch
**Code:** Python (FastAPI, Flask) · Bash · TypeScript / JavaScript · MySQL · PostgreSQL

---

## 🤝 How I work

- ✅ **Fixed scope, fixed price.** You know what you get and what it costs before we start.
- ✅ **You keep the automation.** Every job leaves behind code (Ansible roles, policies, pipelines), not just a document.
- ✅ **Every change is tested.** Backups and rollback first, so nobody gets locked out of their own server.
- ✅ **Clear written reports.** What I found, what I changed, and how to verify it yourself.

---

## 📬 Work with me

[![Upwork](https://img.shields.io/badge/Hire_me_on-Upwork-14a800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~01479d3940bca521fc)
[![Fiverr](https://img.shields.io/badge/Hire_me_on-Fiverr-1dbf73?style=for-the-badge&logo=fiverr&logoColor=white)](https://www.fiverr.com/amjad22291)
[![Website](https://img.shields.io/badge/Portfolio-syedamjad.com-0a66c2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://syedamjad.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/syed-amjad-ali93/)

📧 syed.amjad.hashmi@gmail.com
