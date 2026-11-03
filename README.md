<div align="center">

# Hi, I'm Vanika 👋

### Senior SRE · Cloud Platform Engineer
**Kubernetes · AWS · Terraform · Observability · Automation**

I build and operate **reliable, secure, observable, and cost-efficient cloud platforms** across development, staging, and production environments.

*"Reliability is not just keeping systems up. It's making them easier to operate, safer to change, faster to troubleshoot, and cheaper to run."*

[![Portfolio](https://img.shields.io/badge/Portfolio-e--vanika.github.io-6E40C9?style=for-the-badge&logo=safari&logoColor=white)](https://e-vanika.github.io/Vanika-Portfolio)
[![GitHub](https://img.shields.io/badge/GitHub-E--Vanika-181717?style=for-the-badge&logo=github)](https://github.com/E-Vanika)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vanika%20E-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vanika-e)
[![Email](https://img.shields.io/badge/Email-vanikaraj1%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vanikaraj1@gmail.com)
[![Open to Relocation](https://img.shields.io/badge/Relocation-Open-success?style=for-the-badge)](#)

</div>

<br>

## 🚀 Engineering Impact at a Glance

| Area | Impact |
|---|---|
| 🌎 Cloud Operations | Operated and improved platforms across **30+ Dev, Stage & Production environments** |
| ⚙️ Infrastructure Automation | **~80%** less deployment effort via Terraform/Terragrunt + GitHub Actions |
| 🧩 IaC Standardisation | **~60–70%** less infra code duplication through Terragrunt migration & reusable modules |
| 🔄 CI/CD Engineering | **~50–70%** less CI/CD maintenance across **10+ business-critical platforms** |
| 🔐 Cloud Security | **~80–90%** lower credential-management overhead via OIDC, no long-lived AWS keys |
| ☸️ Kubernetes Reliability | **~90%** less manual intervention via recovery automation & self-healing |
| 🔭 Observability | **~80%** less troubleshooting effort via logging, Grafana & alerting improvements |
| 💰 Cost Optimisation | **~33%** infrastructure cost savings via right-sizing, cache modernisation, RI governance |
| 🚨 Incident Response | First-responder on-call, ~2–3 min alert acknowledgement, triage & mitigation |
| 🌐 Disaster Recovery | Designed & tested active-passive, cross-region recovery with automated RDS snapshot replication |

*These outcomes are backed by production work and my documented experience.*

<br>

## 💼 Professional Experience

### Comcast — Development Engineer III
**Apr 2023 – Present** · *Site Reliability Engineering · Cloud Platform Engineering*

- Operated and improved cloud platforms across **30+ environments**, ramping onto on-call quickly and becoming a go-to person for platform support within a short tenure
- Took single-handed, end-to-end ownership of the **core-optical platform** — infrastructure, GitOps, CI/CD, secrets, monitoring, and a CronJob → Deployment scalability refactor — from provisioning through production
- Led major portions of a business-critical **Prod/Dev/Stage regional migration**: RDS, ElastiCache, and MemoryDB backup/restore, S3 replication, DNS cutover, node scaling, and post-migration cleanup
- Designed, built, and tested an **active-passive disaster-recovery pipeline** — evaluated three RDS replication strategies, selected cross-region snapshot copy, and automated it end-to-end with a Python/Terraform-deployed Lambda
- Delivered **~33%** cache infrastructure cost savings through a Redis → Valkey migration across Dev, Stage, and Production
- Performed critical **EKS upgrades (1.28/1.29 → 1.31 → 1.32)** and **RDS PostgreSQL upgrades (15.4 → 16.4)** across multi-region production platforms, each backed by a documented SMOP
- Standardised **GitHub Actions** across repositories, replacing long-lived PATs with OIDC/GitHub App authentication, and built reusable workflows for Slack PR notifications, release notes, and drift validation
- Automated secrets and credential rotation using **HashiCorp Vault and AWS Secrets Manager**; led the CrowdStrike rollout that replaced Uptycs across environments
- Built and shared an **AI-assisted SRE skills platform** and a **service-flow/architecture-discovery agent** with the wider organisation, presenting the initiative to VP-level leadership and using it to independently resolve production incidents
- Maintained **~2–3 minute** on-call alert acknowledgement; consistently rated a strong, reliable performer and recognised as embedded SRE for the application

### ATOS — DevOps Engineer
**Nov 2019 – Apr 2023**

- Provisioned cloud infrastructure using Terraform; managed Dev, QA, and Production environments
- Built and optimised Docker images; managed Kubernetes workloads on Azure
- Supported end-to-end CI/CD build and release processes across teams

<br>

## 🧠 What I Do as an SRE

- Design and operate **production-grade AWS platforms**
- Build reliable **Kubernetes / Amazon EKS** environments
- Automate infrastructure with **Terraform and Terragrunt**
- Build secure **GitHub Actions CI/CD** pipelines
- Implement **OIDC, IAM, Vault, and secrets-management** patterns
- Build **Grafana dashboards, alerts, and operational visibility**
- Investigate incidents and perform root-cause analysis
- Design and test **disaster-recovery and multi-region strategies**
- Improve platform reliability through automation and self-healing
- Identify infrastructure waste and drive **cloud cost optimisation**
- Standardise engineering approaches across repositories and environments
- Build operational tooling with **Python and Bash**
- Partner with developers, QA, security, and platform teams during delivery and incidents

<br>

## ⚡ Why This Profile Is Different

Most SRE profiles say:

> AWS + Kubernetes + Terraform + Grafana

**Mine shows the engineering problems behind those technologies.** I work across the full reliability loop:

```text
BUILD → DEPLOY → OBSERVE → DETECT → INVESTIGATE → RECOVER → AUTOMATE → OPTIMIZE
                                       ↑
                               AI-assisted operations
```

My work combines **production SRE + platform engineering + automation + observability + cloud security + disaster recovery + AI-assisted operations**.

<details>
<summary><b>📊 Selected Engineering Impact (click to expand)</b></summary>
<br>

| Engineering Outcome | What I Delivered |
|---|---|
| 🏗️ **80% less deployment effort** | Terraform/Terragrunt + GitHub Actions across 30+ environments |
| 🧩 **60–70% less IaC duplication** | Terragrunt migration + reusable infrastructure patterns |
| 🔄 **50–70% less CI/CD maintenance** | Workflow standardisation and reusable GitHub Actions |
| 🔐 **80–90% lower credential overhead** | OIDC authentication + removal of long-lived AWS credentials |
| ☸️ **~90% less manual K8s intervention** | Recovery automation, health checks, self-healing patterns |
| 🔭 **~80% less troubleshooting effort** | Logging, Grafana, alerting and observability improvements |
| 💰 **~33% infrastructure cost savings** | Valkey migration, right-sizing, RI governance, lifecycle controls |
| 🤖 **40–60% less incident investigation** | AI-assisted SRE platform for operational investigation |
| 🗺️ **70–80% less architecture discovery effort** | AI-powered service-flow and incident-intelligence tooling |

</details>

<br>

## 🤖 SRE + AI Engineering Edge

I'm particularly interested in the next generation of SRE:

> **AI should not replace the SRE. AI should increase the SRE's operational context.**

That means turning scattered operational knowledge into something engineers can query, correlate, and act on.

**My AI/SRE work includes:**

`AI-assisted SRE skills platform` `AI agents for AWS, K8s, CI/CD & databases` `AI-assisted incident investigation` `AI-powered service-flow discovery` `Grafana abnormality analysis` `Git commit/PR change correlation` `Jira ↔ deployment correlation` `Slack incident-history search` `MCP-based knowledge integration` `AI-assisted architecture generation`

<details>
<summary><b>🤖 AI for SRE — Selected Work (click to expand)</b></summary>

### 1. AI Markdown Registry / SRE Skills Platform
An AI-assisted operational knowledge and skills platform designed to make SRE expertise reusable — covering AWS infrastructure investigation, Kubernetes workload/event context, CI/CD workflow analysis, RDS investigation, and internal wiki/knowledge-base search. Packaged for install with `uv`, designed for adoption across VS Code, IntelliJ, Windsurf, and OpenCode.

### 2. 🗺️ Service Flow Analyzer
Turns a complex application into an understandable service/dependency map without forcing an engineer to manually explore every repository and system:

```text
Git / Repositories → AI Agent → Architecture + Dependency Analysis
        → Service Flow → Operational Knowledge → Wiki Publishing
```

Included an AI agent for service-flow generation, architecture briefs, dependency understanding, and automatic publishing to the internal wiki — demonstrated to leadership and recognised as AI pioneer work.

### 3. 🔌 Wiki Search MCP Server
Built to make organisational knowledge accessible to AI tooling:

```text
Engineer → AI Assistant → MCP → Wiki Search → Historical Knowledge → Answer / Incident Context
```

Enabled internal tools to connect to wiki knowledge and powered a Slackbot capable of retrieving and summarising incident history.

### 4. 🔭 AI Incident Intelligence
Built around the question: *"What changed, what is broken, have we seen this before, and where should I look next?"*

Capabilities: `investigate_recent_changes`, GitOps commit/PR analysis, Jira ticket extraction, image-tag change detection, Grafana dashboard querying, AWS service/dependency context, Slack + historical incident search.

This shifts observability from a simple `Metric → Alert` flow into a full investigation chain: **Metric → Alert → Recent Changes → Deployment Correlation → Grafana Context → Incident History → Likely Investigation Path.**

</details>

<br>

## ✍️ Writing & Technical Deep Dives

I write about production Kubernetes and platform-engineering patterns — the operational reasoning behind the architecture, not just the how-to.

- 📄 **[Production-Grade Amazon EKS Architecture: What Good Looks Like](https://medium.com/@vanikaraj1/production-grade-amazon-eks-architecture-what-good-looks-like-092eeeaffea1)** *(Medium)* — a 14-part blueprint for taking an EKS cluster from default settings to a resilient, self-healing platform: multi-AZ network and ingress design, API-server lockdown, compute-model selection, policy-as-code and multi-tenancy, storage, failure-tolerant design, independent app/infra scaling, FinOps, observability, GitOps, safe deployment strategies, continuous upgrades, disaster recovery, and AI-assisted incident resolution with automated RCAs.
- 📄 **[Why You Should Stop Letting EKS Pods Depend on Node IAM Roles](https://www.linkedin.com/pulse/why-you-should-stop-letting-eks-pods-depend-node-iam-roles-vanika-e-udmhc/)** *(LinkedIn)* — on the security risk of pods inheriting the underlying node's IAM role, and why IRSA / EKS Pod Identity should replace that pattern for least-privilege, auditable AWS access.

<br>

## 📂 Personal Projects

*Four public projects, one thread: product thinking backed by production SRE discipline—GitOps, IaC, observability, security, safe AI, and reliable delivery.*

### ✦ [Monika Glam Up](https://monika-glamup.vercel.app/) — AI-Enabled Service Platform

A live bridal-services platform with a grounded AI concierge, private enquiries, public reviews, administrator-managed content, and an MCP interface. The same maintained Next.js codebase also serves **Crafts by Vani** and **Mamo Self Care** while keeping each experience distinct.

```text
Visitor → Next.js experience → grounded AI concierge → service knowledge
                         ↘ private enquiry → Google Sheets workflow
One codebase → Monika Glam Up | Crafts by Vani | Mamo Self Care
```

**What it proves:** I can carry an AI-enabled product from domain design and retrieval through customer experience, integrations, deployment controls, and day-two operations.

**Stack:** Next.js · RAG · MCP · Google Sheets · Supabase · Vercel

**Source:** [github.com/E-Vanika/morphos-core](https://github.com/E-Vanika/morphos-core)

---

### ⚡ [Zippy Kiddo](https://zippy-kiddo.129-225-85-54.sslip.io) — Safety-Aware Activity Recommender

A privacy-conscious recommendation product that helps parents find practical activities for children aged 3–12 using age, time, setting, energy, supervision, and materials already available.

- Deterministic eligibility and safety rules remain authoritative
- A compact trained ranker improves ordering and falls back safely when unavailable
- Checksum-pinned model artifacts and quality gates make the ML lifecycle traceable
- Terraform, Ansible, immutable images, readiness checks, rollback, and external smoke tests operate the OCI deployment

**What it proves:** useful ML can improve a product without becoming the authority for safety, and a small service can still have a disciplined model and release lifecycle.

**Stack:** FastAPI · ML ranking · OCI · Terraform · Ansible · GHCR

**Source:** [github.com/E-Vanika/zippy-kiddo](https://github.com/E-Vanika/zippy-kiddo)

---

### 🧪 [Single-VM SRE Platform](https://github.com/E-Vanika/solo-sre-project) — Reliability Engineering Lab

A production-like reliability system running on one resource-constrained OCI VM. It makes the operational controls visible without overstating what a single-node architecture can guarantee.

- **Safe delivery:** immutable Git-SHA images, serialized deployments, readiness gates, deterministic rollback, and external revision checks
- **Reliability management:** a realistic 99.0% SLO, error budget, multi-window burn-rate policy, escalation guidance, and runbooks
- **Observability:** RED application metrics, USE host metrics, Grafana dashboards, and OpenTelemetry traces across services
- **Resilience evidence:** controlled process, CPU, memory, and disk failure drills plus a documented blameless postmortem
- **Honest boundary:** two application processes provide process redundancy—not host or availability-zone redundancy

**What it proves:** reliability is a set of explicit controls, evidence, and trade-offs—not a Kubernetes logo or an inflated availability claim.

**Stack:** Terraform · Ansible · Docker · Caddy · OpenTelemetry · Grafana

---

### 💼 [Vanika Portfolio](https://github.com/E-Vanika/Vanika-Portfolio) — Personal Site, Built Like Production Software

🔗 **Live:** [e-vanika.github.io/Vanika-Portfolio](https://e-vanika.github.io/Vanika-Portfolio)

A personal engineering portfolio treated as a real deliverable, not a static page — the CI/CD discipline is the point.

- Pull-request quality gates and pre-release validation
- Concurrency controls and least-privilege GitHub Actions permissions
- Dependabot automation for dependency hygiene
- Dependency-free Python accessibility validation
- Automated link validation

**What it proves:** production-minded engineering habits applied even to a "just a website" project.
**Stack:** GitHub Actions · Python · Accessibility tooling

<br>

## 🏗️ Selected Production Engineering Work

<details>
<summary><b>☸️ Kubernetes & EKS Platform Engineering</b></summary>
<br>

- Performed critical EKS upgrades across Dev, Stage, and Production, including multi-region migrations from Kubernetes **1.28/1.29 → 1.31 → 1.32**
- Created EKS clusters and supporting infrastructure through Terraform
- Implemented Kubernetes health and recovery mechanisms; investigated pod eviction and workload reliability issues
- Implemented GitOps repository structures for Flux reconciliation
- Implemented Robusta for Kubernetes event monitoring and deployed KRR for resource-optimisation recommendations

**SRE focus:** availability · recoverability · safe upgrades · operational visibility · capacity management
</details>

<details>
<summary><b>🌎 Multi-Region Disaster Recovery</b></summary>
<br>

Designed and tested an active-passive DR approach for production workloads:
1. Evaluated multiple RDS data-copy strategies and tested them in staging
2. Selected cross-region automated snapshot copy
3. Provisioned target-region infrastructure through Terraform and bootstrapped Flux
4. Built a Python AWS Lambda to copy automated RDS snapshots cross-region, deployed via Terraform
5. Restored and tested the latest snapshot in the target region, documenting the recovery process

**Result:** a repeatable recovery path covering AWS infrastructure → Kubernetes → GitOps → database recovery → application readiness.
</details>

<details>
<summary><b>🔭 Observability & Incident Intelligence</b></summary>
<br>

- Built consolidated dashboards mapped to critical application alerts and Grafana panels
- Created CloudWatch alerts, periodic alert-state summaries, and Slack alert routing
- Added pod-restart monitoring and Grafana dashboards for IAM, IP, and infrastructure metrics
- Investigated and fixed Fluent Bit / Helm chart issues affecting log delivery reliability
- Responded to production alerts on-call with ~2–3 minute acknowledgement, tracked incident/JIRA follow-ups, and documented learnings for future responders
</details>

<details>
<summary><b>⚙️ Infrastructure as Code (Terraform & Terragrunt)</b></summary>
<br>

**Terraform** used to provision and manage EKS, RDS, RDS Proxy, ECR, S3, IAM, VPC/networking, secrets infrastructure, Lambda, monitoring, and multi-region DR infrastructure.

**Terragrunt** migration led to improve DRY infrastructure design, environment consistency, reusability, and multi-environment management.

**State & drift management:** resolved Terraform state consistency issues, implemented drift-detection workflows, automated validation/testing, and standardised infrastructure repositories.
</details>

<details>
<summary><b>🔄 CI/CD & GitHub Actions</b></summary>
<br>

- Built GitHub Actions pipelines for infrastructure and application delivery; standardised workflows across repositories
- Implemented **OIDC-based AWS authentication**, replacing long-lived PATs with GitHub App/OIDC patterns
- Built image build/push pipelines to ECR, release-note automation, and drift-validation workflows
- Created automation APIs for triggering GitHub Actions and automated RDS scaling operations

**Reliability principles:** least privilege · repeatability · immutable delivery · automated validation · reduced manual operations
</details>

<details>
<summary><b>🔐 Security & Secrets Management</b></summary>
<br>

- Implemented GitHub Actions OIDC authentication and removed long-lived AWS credentials from CI/CD
- Automated secrets creation using **HashiCorp Vault** and Terraform; used AWS Secrets Manager for platform secrets
- Removed unused IAM users, hardened permissive security groups, remediated open SSH access and permissive SQS policies
- Supported CrowdStrike rollout and migration away from Uptycs as part of a security tooling transition
</details>

<details>
<summary><b>💰 Cloud Cost Optimisation</b></summary>
<br>

- Delivered **~33% cache-engine cost reduction** through Redis → Valkey migration
- Right-sized infrastructure after regional migration; investigated daily cloud-cost spikes
- Removed unused load balancers, ElastiCache resources, and SQS queues
- Addressed RDS Reserved Instance expiry risks and S3 lifecycle-policy gaps
- Used KRR recommendations for resource optimisation

**Principle:** optimise based on evidence, not blindly on resource size.
</details>

<details>
<summary><b>🗄️ Database & Data Platform Reliability</b></summary>
<br>

**Amazon RDS / PostgreSQL:** upgraded PostgreSQL 15.4 → 16.4, tested extension compatibility and Global Writer Endpoint behaviour, implemented failover-handling changes, deployed RDS Proxy, migrated infrastructure to Terragrunt, and built cross-region snapshot-copy automation for DR.

**Cache platforms:** worked with ElastiCache and MemoryDB, migrated Redis workloads to Valkey, and used resource/workload analysis to drive cost optimisation.
</details>

<details>
<summary><b>🚀 Application Platform Engineering — Core Optical Platform</b></summary>
<br>

- Provisioned AWS infrastructure via Terraform; created Kubernetes namespaces through GitOps
- Structured Flux repositories for Dev, Stage, and Production; provisioned RDS clusters
- Built CI/CD to build and push application images to ECR
- Converted an inventory workload from CronJob to Deployment for improved scalability, deployed successfully to Production
- Investigated production API failures, resolved pod eviction issues, and fixed CloudWatch log delivery problems
</details>

<br>

## 🤖 Automation & Operational Tooling

A major part of my SRE approach is replacing repetitive operational work with automation:

- Python automation for AWS resource discovery
- Lambda automation for periodic CloudWatch alert summaries and cross-region RDS snapshot replication
- Workflow inventory collection across repositories and GitHub Actions workflow-trigger APIs
- Automated RDS scaling, release-note generation, Grafana dashboard backups, and KRR resource reports
- Automated secrets-management workflows and operational alert routing

<br>

## 🧰 Technology Stack

| Category | Technologies |
|---|---|
| **Cloud** | AWS · Microsoft Azure · Oracle Cloud Infrastructure |
| **Kubernetes & Platform** | Kubernetes · Amazon EKS · Helm · FluxCD · ArgoCD · Istio · Kong |
| **Infrastructure as Code** | Terraform · Terragrunt · GitOps |
| **CI/CD** | GitHub Actions · GitHub Apps · OIDC |
| **Observability** | Prometheus · Grafana · CloudWatch · Robusta · KRR · Fluent Bit |
| **Security & Networking** | HashiCorp Vault · AWS Secrets Manager · IAM · KMS · OIDC · CrowdStrike · WireGuard |
| **Databases & Data Services** | RDS PostgreSQL · RDS Proxy · ElastiCache · MemoryDB · Valkey · ECR · S3 |
| **Automation** | Python · Bash · AWS Lambda |

<br>

## 📈 Reliability Engineering Mindset

```text
Detect → Understand → Mitigate → Recover → Find Root Cause → Automate the Fix → Prevent Recurrence → Measure the Improvement
```

My goal is not simply to close incidents. **The goal is to make the next incident less likely, easier to detect, faster to diagnose, and safer to recover from.**

<br>

## 🎓 Education & Certifications

| Degree | Institution | Score |
|---|---|---|
| Master of Computer Applications (MCA) | Anna University | 91% |
| B.Sc. Computer Science | Meenakshi Academy of Higher Education and Research University | 86% |
| HSC (Computer Science) | Tamil Nadu State Board | 89% |
| SSLC | Tamil Nadu State Board | 93.4% |

- **Microsoft Certified: Azure Fundamentals (AZ-900)**
- **Microsoft Certified: Azure Administrator (AZ-104)** *(Issued Dec 2022 · Expired Dec 2023)*
- **Accolade Champagne Award** — Recognised for building a complete production-ready cloud environment from scratch in ~1–2 days

<br>



---

<div align="center">

## 🤝 Let's Connect

**SRE · Kubernetes · AWS · Terraform · Platform Engineering · Observability · Cloud Security · Automation · Disaster Recovery · Networking**

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Site-6E40C9?style=for-the-badge&logo=safari&logoColor=white)](https://e-vanika.github.io/Vanika-Portfolio)
[![Email](https://img.shields.io/badge/Email-vanikaraj1%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vanikaraj1@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vanika%20E-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vanika-e)
[![GitHub](https://img.shields.io/badge/GitHub-E--Vanika-181717?style=for-the-badge&logo=github)](https://github.com/E-Vanika)

*If you're reviewing this for an SRE / Platform Engineering role, start with the Professional Experience, Kubernetes, Disaster Recovery, Observability, IaC, CI/CD, Security, and Cost Optimisation sections above — they show operational problems turned into repeatable, automated, measurable engineering solutions.*

</div>
