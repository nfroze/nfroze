# Noah Frost

**DevSecOps Engineer** | Ex-Police Officer → Security-First Infrastructure

I learned DevSecOps with AI, not despite it. 8 months, 15 projects, zero tutorials—built alongside Claude and ChatGPT to understand *why*, not just *what*. Police background means I question everything, including AI output.

## Homelab

Autonomous AI build system and Kubernetes cluster, both running on the same Mac.

I designed and built **Jarvis** — an agent that takes a webapp brief and delivers a live, deployed application end to end. It generates hero art from a LoRA model I fine-tuned, animates it into a cinemagraph, writes a full build spec, dispatches Claude Code to build the entire app, and deploys to AWS with Cloudflare SSL. One shot. No manual intervention. Five production security webapps have been built through this system.

Then I gave it a different brief: provision a Kubernetes cluster on the same Mac you run on, harden it, monitor it, and host a public build log documenting everything — served by the cluster itself.

**It did.**

K3s on Apple Silicon. Cloudflare Tunnel with zero inbound ports. 12 network policies, Pod Security Standards enforced across all namespaces, non-root pods, read-only rootfs, all capabilities dropped. Prometheus and Grafana running with 28 dashboards — publicly accessible. Jarvis queries the cluster via kubectl in real time.

→ **Webapps Hub:** [nfroze.co.uk](https://nfroze.co.uk)
→ **K8s Build Log:** [k3s.nfroze.co.uk](https://k3s.nfroze.co.uk)
→ **Live Grafana Dashboard:** [dashboard.nfroze.co.uk](https://dashboard.nfroze.co.uk)
→ **Jarvis GitHub:** [github.com/NFrozeCLAWDBOT](https://github.com/NFrozeCLAWDBOT)

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

15 projects built in 8 months. Each repo includes architecture breakdowns, key decisions, and screenshots of working deployments.

### MCP Implementations
| Project | What It Does |
|---------|--------------|
| [Slack MCP Assistant](https://github.com/nfroze/Slack-MCP-Assistant) | Claude Desktop ↔ Slack integration for natural language workspace queries |
| [MCP Security Incident Response](https://github.com/nfroze/MCP-Security-Incident-Response-System) | AI-powered GuardDuty investigation with automated EC2 isolation |
| [MCP IaC Security Remediation](https://github.com/nfroze/MCP-Powered-IaC-Security-Remediation) | Checkov findings → Claude analysis → Terraform fixes |
| [MCP Kubernetes Health Monitor](https://github.com/nfroze/MCP-Kubernetes-Health-Monitor) | Natural language cluster health queries on EKS with ArgoCD GitOps |

### DevSecOps & CI/CD
| Project | What It Does |
|---------|--------------|
| [DevSecOps Pipeline with SIEM](https://github.com/nfroze/End-to-End-DevSecOps-Pipeline-with-SIEM-Integration) | Full pipeline: SAST/DAST/SCA → EKS → GuardDuty → Splunk |
| [CI/CD Pipeline Comparison](https://github.com/nfroze/CI-CD-Pipeline-Comparison-Jenkins-vs-GitLab-CI) | Jenkins vs GitLab CI deploying to shared AWS infrastructure |
| [Portfolio CI/CD Pipeline](https://github.com/nfroze/Portfolio-CI-CD-Pipeline) | S3 + CloudFront + Route 53 with automated cache invalidation |

### Kubernetes & Observability
| Project | What It Does |
|---------|--------------|
| [GitOps with ArgoCD](https://github.com/nfroze/GitOps-Pipeline-with-ArgoCD-and-Full-Stack-Observability) | EKS + ArgoCD auto-sync + Prometheus/Grafana stack |
| [Kubernetes Observability Stack](https://github.com/nfroze/Kubernetes-Observability-Stack-with-ELK-and-Prometheus) | ELK + Fluentd + Prometheus on EKS with environment-specific sizing |

### Threat Modeling
| Project | What It Does |
|---------|--------------|
| [Healthcare Threat Model](https://github.com/nfroze/Healthcare-Threat-Model) | STRIDE analysis for HIPAA-compliant patient platform with 15 prioritised threats |

### Platform Engineering
| Project | What It Does |
|---------|--------------|
| [Serverless E-Commerce Platform](https://github.com/nfroze/Serverless-E-Commerce-Platform) | React + Lambda + DynamoDB + CloudFront, fully modular Terraform |
| [AI/ML Internal Developer Platform](https://github.com/nfroze/AI-ML-Internal-Developer-Platform) | Backstage + MLflow + ArgoCD on hybrid EKS/ECS with GPU cost tracking |

### AI Governance & FinOps
| Project | What It Does |
|---------|--------------|
| [AI FinOps Platform](https://github.com/nfroze/AI-FinOps-Platform) | Kafka streaming GPU/API costs with OpenCost and anomaly detection |
| [AI/ML Governance with Policy-as-Code](https://github.com/nfroze/AI-ML-Governance-with-Policy-as-Code) | Sentinel blocks bad Terraform; OPA Gatekeeper blocks untracked models |

### Multi-Cloud
| Project | What It Does |
|---------|--------------|
| [Multi-Cloud Infrastructure](https://github.com/nfroze/Multi-Cloud-Infrastructure-Orchestration) | AWS + Azure + GCP from single GitHub Actions workflow with Ansible config |

## Links

[![Portfolio](https://img.shields.io/badge/Portfolio-noahfrost.co.uk-000000?style=for-the-badge)](https://noahfrost.co.uk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nfroze-0A66C2?style=for-the-badge)](https://linkedin.com/in/nfroze)
[![K8s Build Log](https://img.shields.io/badge/K8s_Build_Log-k3s.nfroze.co.uk-326CE5?style=for-the-badge)](https://k3s.nfroze.co.uk)
[![Grafana](https://img.shields.io/badge/Live_Dashboard-dashboard.nfroze.co.uk-F46800?style=for-the-badge)](https://dashboard.nfroze.co.uk)

---

*Trained at Cyber Agoge DevSecOps Bootcamp under a Global CISO (KPMG, BAE Systems, UK Government)*