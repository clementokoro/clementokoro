## Hi, I'm Clement Okoro - Principal SRE & Infrastructure Architect

I design and operate production-grade Kubernetes platforms on AWS with a focus on
observability, GitOps, high availability, and security compliance.

---

### 🏗️ What I'm Currently Running

A **4-node Kubernetes cluster on AWS** (Amazon Linux, Kubernetes v1.29) managed end-to-end
via GitOps - 14 applications deployed and monitored across 4 isolated environments
(dev / qa / staging / production).

| Layer | Technology |
|---|---|
| **Container Orchestration** | Kubernetes v1.29 · kubeadm · Flannel CNI |
| **GitOps** | ArgoCD · App-of-Apps · Hub & Spoke ApplicationSets |
| **Observability** | Prometheus · Grafana · Loki · Tempo · OpenTelemetry · DataDog |
| **Alerting** | Alertmanager → PagerDuty · Slack · Email · Jira (auto-ticket) |
| **CI/CD** | GitLab CI/CD · SLSA Level 2 · Trivy CVE scanning · k6 load testing |
| **Security** | Sealed Secrets · cert-manager · Zero Trust NetworkPolicies · HIPAA/SOC2 controls |
| **IaC** | Terraform · Helm · Ansible |
| **Resilience** | Velero backups · LitmusChaos · Chaos Engineering · Multi-Region DR |
| **Cloud** | AWS EC2 · VPC · Route 53 · S3 · CloudWatch · Cost Explorer |

---

### 📁 Key Projects

| Repository | Description |
|---|---|
| [**sre-lab-infra**](https://github.com/clementokoro/sre-lab-infra) | Kubernetes GitOps control plane - ArgoCD manifests, Helm values, App-of-Apps |
| [**gallery-api**](https://github.com/clementokoro/gallery-api) | Go REST API with OpenTelemetry instrumentation - the production-grade workload |
| [**sre-runbooks**](https://github.com/clementokoro/sre-runbooks) | Incident post-mortems, runbooks, chaos experiment reports |

---

### 🔧 Background

10+ years in enterprise infrastructure and quality engineering.
IBM · Purpose Brands · Dell · Buffalo Technology

**Languages:** Go · Python · Bash · YAML · HCL (Terraform)
