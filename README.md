## 🔒 DevSecOps Projects

### 🌍 [Project 20: Multi-Cloud Orchestration](https://github.com/nfroze/Project-20-CloudGuard-Multi-Cloud-Orchestration)

- Built unified orchestration platform deploying infrastructure to **AWS, Azure, and GCP simultaneously in 12 minutes**
- Single `git push` triggers parallel deployment across all 3 clouds (vs 3+ days manually)
- **Ansible** automatically detects OS differences (RedHat vs Debian) and adapts nginx configuration without manual intervention
- **Datadog EU** provides single pane of glass monitoring - that "3" indicator proves all clouds healthy
- **Tech stack**: Terraform (multi-provider), Ansible (OS-adaptive), GitHub Actions (GitOps), Datadog (unified monitoring)
- Zero configuration drift across clouds - 100% consistency enforced through Infrastructure as Code
- Demonstrates real-world multi-cloud challenges: AWS shows IP-based hostname while Azure/GCP show proper names

### ⚖️ [Project 19: AI Governance Framework](https://github.com/nfroze/Project-19-AI-Governance-Framework)

- Built dual-layer AI governance framework blocking unauthorised GPU provisioning that could cost **£10K+/month**
- **HCP Terraform Sentinel** policies prevent expensive GPU instances (p3.2xlarge at £3.06/hr) before provisioning
- **OPA Gatekeeper** enforces ML model tracking with clear errors: "❌ ML MODEL DEPLOYMENT BLOCKED - Missing Labels"
- 100% ML model compliance with mandatory versioning, team attribution, and registry requirements
- **Tech stack**: HCP Terraform, Sentinel, AWS EKS, OPA Gatekeeper, GitOps with GitHub
- EU AI Act ready with complete audit trails - reduces compliance reporting from 2 weeks to 2 hours
- Demonstrated on t3.medium (£0.04/hr) - same policies would block production GPU instances

### 💰 [Project 18: AI FinOps Platform](https://github.com/nfroze/Project-18-AI-FinOps-Platform)

- Real-time Kubernetes cost optimisation platform catching AI anomalies in **<30 seconds** (not monthly bills)
- **Apache Kafka** streaming (3 brokers, 23 partitions) processing millions of GPU metrics and API token events
- Prevents £100K+ monthly overruns through instant detection of idle GPUs and runaway OpenAI API calls
- Intelligent topic partitioning: `gpu-utilization-events` (10), `ai-api-costs` (10), `cost-anomalies` (3)
- **Tech stack**: Strimzi Kafka, OpenCost, Prometheus, Grafana, AWS EKS, Terraform
- Event-driven architecture vs traditional polling - processing cost events as they happen
- Would achieve 50% GPU cost reduction and 40% API savings through real-time visibility

### 🏗️ [Project 17: AI Developer Platform](https://github.com/nfroze/Project-17-AI-Developer-Platform)

- Built self-service Internal Developer Platform reducing AI model deployment from **2 weeks to 30 minutes**
- Hybrid architecture: **AWS EKS** for complex orchestration, **ECS Fargate** for simple services (70% cheaper)
- **GitOps** with **ArgoCD** managing **Helm** deployments of Backstage, MLflow
- Real-time GPU cost tracking preventing budget overruns - saves £10-40K/month through intelligent resource management
- **Tech stack**: Terraform, Kubernetes, ArgoCD, Backstage (Spotify), MLflow, Node.js
- Simulated GPU workloads on standard instances for cost-effective demonstration
- Demonstrates platform engineering, FinOps, and smart architectural decisions for AI infrastructure

### 💻 [Project 16: Portfolio Pipeline](https://github.com/nfroze/Project-16-Portfolio-Pipeline)

- Automated CI/CD pipeline with **GitHub Actions** for portfolio site deployment
- Static website hosting on **AWS S3** with **CloudFront** CDN for global distribution
- Infrastructure managed with **Terraform** - imported existing resources under IaC control
- Git push triggers automatic deployment with cache invalidation in < 5 minutes
- **Tech stack**: S3, CloudFront, Route 53, GitHub Actions, Terraform
- Demonstrates real-world "manual first, then automate" infrastructure evolution
- Complete DevOps transformation of simple website with zero-downtime migration

### 🏰 [Project 15: SENTINEL](https://github.com/nfroze/Project-15-SENTINEL) (Coming Soon)

### 🔨 [Project 14: FORGE](https://github.com/nfroze/Project-14-FORGE) (Coming Soon)

### 🛡️ [Project 13: AEGIS](https://github.com/nfroze/Project-13-AEGIS)(Coming Soon)

### ☸️ [Project 12: MCP Meets K8s](https://github.com/nfroze/Project-12-MCP-Meets-K8s)

- **Pioneered one of the first Kubernetes MCP integrations** - Natural language cluster operations via Claude Desktop
- Built production-grade DevSecOps platform with **AWS EKS**, **GitOps** via **ArgoCD**, and full observability
- AI-powered troubleshooting: "What's broken in production?" → Instant analysis with remediation steps
- Complete security scanning pipeline: **Checkov** (IaC), **Semgrep** (SAST), **Gitleaks** (secrets), **Trivy** (containers)
- **Tech stack**: Terraform, Kubernetes, ArgoCD, Prometheus/Grafana, Node.js MCP server
- Natural language queries for Kubernetes operations
- Pioneering the future of AI-augmented DevOps operations

### 🚧 [Project 11: MCP IaC Security](https://github.com/nfroze/Project-11-MCP-Powered-IaC-Security-Remediation)

- Created **MCP server** that analyses Checkov findings and generates Terraform fixes
- Provides AI-powered analysis and remediation code for infrastructure vulnerabilities
- Natural language queries: "Fix my Terraform security issues" → Complete remediated code
- Integrates **GitHub Actions**, **Checkov**, and **Claude Desktop** for end-to-end automation
- **Tech stack**: Node.js, GitHub API, Checkov, Claude Desktop MCP integration
- Provides exact code fixes for 40+ security misconfigurations
- Demonstrates practical AI application for Infrastructure as Code security

### 🚨 [Project 10: MCP Security Ops](https://github.com/nfroze/Project-10-MCP-Security-Incident-Response-System)

- Built one of the **first MCP (Model Context Protocol)** implementations for security operations
- Gives AI direct access to **AWS GuardDuty** for automated incident investigation
- Analyses hundreds of security findings and generates executive reports rapidly
- Natural language queries: "Are we under attack?" → Complete analysis with recommendations
- **Tech stack**: Node.js, AWS GuardDuty, Claude Desktop MCP integration
- Demonstrates the future of AI-augmented Security Operations Centers
- Battle-tested against real SSH brute force and crypto mining attacks

### 🚀 [Project 9: GitOps Monitoring](https://github.com/nfroze/Project-9-GitOps-ArgoCD-Monitoring)

- Implemented production-grade **GitOps** workflow with **ArgoCD** on **AWS EKS**
- Deployed **Prometheus** and **Grafana** monitoring stack via Helm charts
- Achieved full cluster observability with real-time metrics and dashboards
- **Tech stack**: Terraform, AWS EKS, ArgoCD, Prometheus, Grafana, Helm
- Troubleshot complex CRD deployment issues using ServerSideApply
- Demonstrated real-world debugging skills when Prometheus initially failed to deploy
- **Completed in ~1 hour for ~$1** - proving cloud learning doesn't need to be expensive

### 🤖 [Project 8: Slack MCP Assistant](https://github.com/nfroze/Project-8-Slack-MCP-Assistant)

- Built an **MCP (Model Context Protocol)** server connecting Claude Desktop to Slack
- Enables natural language queries: "What did I miss while I was on vacation?"
- Fetches and summarizes Slack messages, filtering noise from important updates
- **Tech stack**: Node.js, Slack Web API, Claude Desktop MCP integration
- Use cases: vacation catch-up, executive summaries, team sentiment analysis
- Demonstrates cutting-edge AI integration with enterprise tools
- Open source implementation of Claude's newest protocol capabilities

### 🎯 [Project 7: Live Threat Modeling](https://github.com/nfroze/Project-7-Gaming-Platform-Threat-Modeling-Exercise)

- Identified privacy vulnerability on a major UK gaming platform during interview preparation
- Demonstrated attack chain from public winner data to potential account compromise
- Mapped OSINT techniques used by criminals to target high-value winners
- Focused on protecting elderly and vulnerable customers from social engineering
- Provided phased mitigation strategy with immediate zero-cost improvements
- Balanced security recommendations with business requirements
- Created concise executive-ready documentation for non-technical stakeholders

### 🌐 [Project 6: AI Chrome Extension](https://github.com/nfroze/Project-6-Full-Stack-Chrome-Extension-with-AI-Integration)

- Chrome extension providing AI-powered TLDR summaries and analysis of LinkedIn posts
- Full-stack implementation: **Chrome Extension API** + **Express.js** backend on **Vercel**
- Integrated **Claude 3.5 Sonnet** for intelligent post analysis and spam scoring
- **The $5 Challenge**: Live API budget tracking as users analyse LinkedIn content
- Clean error handling with fallback responses for edge cases
- Shows ability to ship complete products from idea to deployment

### 📦 [Project 5: DevSecOps Pipeline](https://github.com/nfroze/Project-5-End-to-End-DevSecOps-Transformation)

- Complete DevSecOps pipeline for Node.js app deployed to **Amazon EKS**
- Automated security scanning at every stage (SAST, DAST, SCA, IaC)
- **Security toolchain**: Semgrep, Trivy, Gitleaks, OWASP ZAP, Checkov
- Infrastructure as Code with **Terraform** (100% Checkov compliant)
- Runtime monitoring with **AWS GuardDuty** and **CloudWatch**
- Centralized security logging with **Splunk SIEM**
- Full CI/CD automation with **GitHub Actions**
- Implements security controls based on threat modeling from Project 4

### ⚠️ [Project 4: Threat Modeling](https://github.com/nfroze/Project-4-Threat-Modeling-Incident-Response)

- Simulates a full threat modeling workshop for a fictional enterprise-scale healthcare platform
- Includes HLD and DFD diagrams to map architecture, data flows, and trust boundaries
- Applies the STRIDE threat model to assess control gaps across system components
- Maps attacker TTPs using the MITRE ATT&CK Framework
- Uses the Cyber Kill Chain to break down the lifecycle of several simulated attacks
- Conducts an inherent risk assessment to prioritize threats based on likelihood and impact
- Simulates a NIST-aligned incident response plan based on one modeled attack scenario

### ☁️ [Project 3: IaC Security](https://github.com/nfroze/Project-3-Infrastructure-as-Code-IaC-Security)

- Used **Terraform** to provision secure AWS infrastructure (IAM, S3, EC2)
- Integrated **Checkov** for automated misconfiguration detection
- Automated terraform **init**, **plan**, and **apply** in a CI/CD pipeline using GitHub Actions
- Enforced security gate before cloud resources are deployed

### 🐳 [Project 2: Container Security](https://github.com/nfroze/Project-2-Image-and-Runtime-Application-Security)

- Built and scanned Docker images using **Trivy**
- Deployed secure containers to **Amazon ECS** with least privilege IAM roles
- Used a **Load Balancer** to maintain a static IP for external access and scanning
- Performed **DAST** using **OWASP ZAP** on the live ECS service

### 🛠️ [Project 1: Secure CI/CD](https://github.com/nfroze/Project-1-CI-CD-Pipeline-Security)

- Built a secure pipeline integrating:
 - SAST scanning (**Semgrep**)
 - SCA scanning (**npm audit**)
 - Secrets scanning (**Gitleaks**)
- Enforced fail-fast workflows to catch security issues early in development

---

## 🎯 Currently Seeking DevSecOps Opportunities

---

## 📚 Certifications

✅ **CompTIA Security+** (2025)
  
✅ **AWS Certified Cloud Practitioner** (2025)
  
✅ **HashiCorp Certified: Terraform Associate** (2025)

### In Progress:
- **AWS Certified Solutions Architect – Associate**

---

## 📬 Let's Connect  
🔗 [LinkedIn](https://www.linkedin.com/in/nfroze/)

---

> "From policing to pipelines — I build with security in mind from the very first line of code."