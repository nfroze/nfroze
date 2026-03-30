# Noah Frost

**DevSecOps Engineer** | Ex-Police Officer · AI-Native Security Builder

I build secure infrastructure and AI-powered security tooling. 20+ projects across CI/CD security, Kubernetes, cloud infrastructure, zero trust, supply chain security, and AI governance — built alongside Claude and ChatGPT from day one. Police background means I question everything, including AI output.

## Homelab

Autonomous AI build system and production-hardened Kubernetes cluster, both running on the same Mac.

I designed and built **Jarvis** — an OpenClaw agent with its own AWS credentials, GitHub account, and CLI access to Claude Code. It takes a webapp brief and delivers a live, deployed application end to end: hero art from a custom LoRA model, cinemagraph animation, full build spec, autonomous code generation, and AWS deployment. One shot. No manual intervention. Five production security webapps have been built through this system:

| App | What It Does | Live |
|-----|-------------|------|
| [Sentinel](https://github.com/NFrozeCLAWDBOT/sentinel) | Vulnerability intelligence — fuses NVD, CISA KEV, and EPSS into composite risk scores | [sentinel.nfroze.co.uk](https://sentinel.nfroze.co.uk) |
| [Oracle](https://github.com/NFrozeCLAWDBOT/oracle) | Guided OWASP Top 10 for LLM Applications 2025 security assessment | [oracle.nfroze.co.uk](https://oracle.nfroze.co.uk) |
| [Bastion](https://github.com/NFrozeCLAWDBOT/bastion) | Dependency risk analysis with full transitive tree resolution and CycloneDX SBOM export | [bastion.nfroze.co.uk](https://bastion.nfroze.co.uk) |
| [Aegis](https://github.com/NFrozeCLAWDBOT/aegis) | AI regulatory compliance mapping across EU AI Act, UK GDPR, NIST AI RMF, and 3 more frameworks | [aegis.nfroze.co.uk](https://aegis.nfroze.co.uk) |
| [Verdant](https://github.com/NFrozeCLAWDBOT/verdant) | AWS security posture dashboard against CIS Foundations Benchmark | [verdant.nfroze.co.uk](https://verdant.nfroze.co.uk) |

Then I gave Jarvis a different brief: provision a Kubernetes cluster on the same Mac you run on, harden it, monitor it, and host a public build log — served by the cluster itself.

K3s on Apple Silicon. Cloudflare Tunnel with zero inbound ports. 12 network policies, Pod Security Standards enforced across all namespaces, non-root pods, read-only rootfs, all capabilities dropped. Prometheus and Grafana running with 28 dashboards — publicly accessible. Jarvis queries the cluster via kubectl in real time.

→ **Webapps Hub:** [nfroze.co.uk](https://nfroze.co.uk) · **K8s Build Log:** [k3s.nfroze.co.uk](https://k3s.nfroze.co.uk) · **Live Dashboard:** [dashboard.nfroze.co.uk](https://dashboard.nfroze.co.uk) · **Jarvis GitHub:** [github.com/NFrozeCLAWDBOT](https://github.com/NFrozeCLAWDBOT)

## Tech Stack

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

## Certifications

[![AWS](https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=for-the-badge)](https://www.credly.com/badges/your-badge)
[![Security+](https://img.shields.io/badge/CompTIA-Security+-EA3C3C?style=for-the-badge)](https://www.credly.com/badges/your-badge)
[![Terraform](https://img.shields.io/badge/HashiCorp-Terraform_Associate-7B42BC?style=for-the-badge)](https://www.credly.com/badges/your-badge)

## Projects

### Security Engineering
| Project | What It Does |
|---------|--------------|
| [Zero Trust Kubernetes Architecture](https://github.com/nfroze/Zero-Trust-Kubernetes-Architecture) | Cilium eBPF, SPIFFE/SPIRE workload identity, L7 micro-segmentation, WireGuard — NIST 800-207 aligned |
| [Supply Chain Security Pipeline](https://github.com/nfroze/Supply-Chain-Security-Pipeline) | Syft SBOM generation, keyless cosign signing, SLSA provenance, Kyverno admission control on EKS |
| [Secrets Management Vault](https://github.com/nfroze/Secrets-Management-Vault) | HashiCorp Vault HA on EKS — dynamic DB/AWS/PKI/Transit secrets, KMS auto-unseal, Vault Secrets Operator |
| [Agentic AI Security Testing](https://github.com/nfroze/Agentic-AI-Security-Testing) | Automated security probes against OWASP Top 10 for LLMs and Agentic AI — ECS Fargate, dual CI/CD (21 jobs) |

### DevSecOps & CI/CD
| Project | What It Does |
|---------|--------------|
| [End-to-End DevSecOps Transformation](https://github.com/nfroze/End-to-End-DevSecOps-Transformation) | Full pipeline: SAST/DAST/SCA/IaC scanning → EKS → GuardDuty/Security Hub/CloudTrail → Splunk Cloud SIEM |
| [AI/ML Governance with Policy-as-Code](https://github.com/nfroze/AI-ML-Governance-Policy-as-Code) | Sentinel blocks bad Terraform; OPA Gatekeeper blocks untracked models — EU AI Act risk mapping |
| [CI/CD Pipeline Comparison](https://github.com/nfroze/CI-CD-Pipeline-Comparison) | Jenkins vs GitLab CI deploying to shared AWS infrastructure — side-by-side operational comparison |
| [Portfolio CI/CD Pipeline](https://github.com/nfroze/Portfolio-CI-CD-Pipeline) | S3 + CloudFront + Route 53 with automated cache invalidation on every push |

### Kubernetes & Observability
| Project | What It Does |
|---------|--------------|
| [GitOps with ArgoCD](https://github.com/nfroze/GitOps-Pipeline-with-ArgoCD) | EKS + ArgoCD auto-sync and self-healing + Prometheus/Grafana observability |
| [Kubernetes Observability Stack](https://github.com/nfroze/Kubernetes-Observability-Stack) | ELK + Fluentd + Prometheus on EKS with environment-specific sizing |

### Threat Modeling
| Project | What It Does |
|---------|--------------|
| [Healthcare STRIDE Threat Model](https://github.com/nfroze/Healthcare-STRIDE-Threat-Model) | 15 prioritised threats mapped to HIPAA, MITRE ATT&CK, and OWASP — with working code mitigations |

### Platform Engineering
| Project | What It Does |
|---------|--------------|
| [3-Tier Serverless Application](https://github.com/nfroze/3-Tier-Serverless-Application) | React + Lambda + DynamoDB + CloudFront — fully modular Terraform, one Lambda per CRUD operation |
| [AI/ML Developer Platform](https://github.com/nfroze/AI-ML-Developer-Platform) | Backstage + MLflow + ArgoCD on hybrid EKS/ECS with GPU cost tracking |

### AI Governance & FinOps
| Project | What It Does |
|---------|--------------|
| [AI FinOps Platform](https://github.com/nfroze/AI-FinOps-Platform) | Strimzi Kafka streaming GPU/API costs with OpenCost and anomaly detection on EKS |

### Multi-Cloud
| Project | What It Does |
|---------|--------------|
| [Multi-Cloud Orchestration](https://github.com/nfroze/Multi-Cloud-Orchestration) | AWS + Azure + GCP from single GitHub Actions workflow with Ansible config and Datadog observability |

## Links

[![Portfolio](https://img.shields.io/badge/Portfolio-noahfrost.co.uk-000000?style=for-the-badge)](https://noahfrost.co.uk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nfroze-0A66C2?style=for-the-badge)](https://linkedin.com/in/nfroze)
[![K8s Build Log](https://img.shields.io/badge/K8s_Build_Log-k3s.nfroze.co.uk-326CE5?style=for-the-badge)](https://k3s.nfroze.co.uk)
[![Grafana](https://img.shields.io/badge/Live_Dashboard-dashboard.nfroze.co.uk-F46800?style=for-the-badge)](https://dashboard.nfroze.co.uk)

---

*Trained at Cyber Agoge DevSecOps Bootcamp under a Global CISO (KPMG, BAE Systems, UK Government)*