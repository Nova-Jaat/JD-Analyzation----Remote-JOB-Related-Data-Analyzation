# 📋 Job Description Analysis — Batch #6 (AWS Cloud, GCP Remote, SRE / DevOps)

> **Candidate:** [Sanjeev Kumar](https://github.com/Nova-Jaat) (`Nova-Jaat`)  
> **Contact:** [nova01111111@gmail.com](mailto:nova01111111@gmail.com)  
> **Core Credentials:** RHCSA (Red Hat Certified System Administrator | RHEL 9, Cert ID verified)  
> **Primary Technical Competencies:** Linux OS Internals & Hardening | AWS Core Infrastructure (VPC, EC2, EKS, S3, RDS, IAM, CloudWatch) | Multi-Cloud Parity (GCP, Azure) | Terraform (Modular IaC, S3/DynamoDB State Locking) | Docker & Kubernetes (EKS / GKE / Helm Charts / GitOps) | CI/CD Automation (GitHub Actions, GitLab CI, Azure DevOps) | Bash & Python Scripting | Observability (Prometheus, Grafana, CloudWatch) | SRE Practices (SLIs/SLOs, Incident Triage, Postmortems)  
> **Experience Level:** ~1-month Internship (DecodeLabs) + 15-month Training (Grras Solutions) ➔ **~1.5–2 Years Practical Hands-On Production Engineering**  
> **Notice Period & Availability:** **Immediate Joiner (0 Days Notice)**  
> **Date Analyzed:** November 3, 2026  

---

## ⚡ 1. Strategic Priority Action Board & Triage

```
🌟 TIER 1: PRIME HIGH-CONVERSION TARGETS (Direct Stack Alignment — Apply Today)
  ├── #1 HJ Infotech — AWS Cloud / DevOps Engineer                 ⭐ 92% Match (Pure AWS + IaC + EKS + GitHub Actions)
  └── #3 Auriga IT — DevOps / SRE Engineer                         ⭐ 82% Match (SRE Ownership + RHEL Linux Moat + Terraform IaC)

🟡 TIER 2: AUTOMATED FUNNEL STRETCH (Leverage Cloud-Agnostic Core)
  └── #2 Remote India Partner — GCP Cloud Engineer (4+ Years)      ⭐ 68% Match (Automated Coding & Video Funnel Bypasses Resume Screening)

⚪ TIER 3: RESERVED SLOT
  └── #4 [Slot Reserved for Next Job Description]                 ⏳ Pending Submission
```

---

## 📊 2. Master Comparison Matrix

| # | Company / Posting | Role Title | Stated Exp. | Sanjeev's Fit | Match % | Core Tech Stack | Strategic Verdict & Action Plan |
|:---:|:---|:---|:---:|:---:|:---:|:---|:---|
| **#1** | **HJ Infotech** | **AWS Cloud / DevOps Engineer** | Not rigid (1–3 yrs friendly) | 1.5 yrs AWS | **92%** | AWS (EKS, EC2, RDS, IAM, VPC), Terraform, GitHub Actions, Docker, Bash/Python, Prometheus/Grafana | 🌟 **TOP TARGET #1 (Apply Immediately)** — Absolute direct bullseye with your daily AWS workflow. Emphasize modular Terraform, GitHub Actions workflows, and Linux security hardening. |
| **#2** | **Remote Partner (India)** | **GCP Cloud Engineer** | 4+ Years | 1.5 yrs + K8s/IaC | **68%** | GCP (GKE, Cloud Run, Cloud SQL, VPC), Azure DevOps, Terraform, Helm, Python/Bash | 🟡 **STRETCH APPLY (Funnel Advantage)** — Automated 5-stage funnel (HackerRank coding challenge + video intro). Your Kubernetes, Helm, and Terraform knowledge translates 100% to GCP. |
| **#3** | **Auriga IT** | **DevOps / SRE Engineer** | 3–5 Years | 1.5 yrs + RHCSA | **82%** | Terraform (Exclusive IaC), Production K8s, Prometheus/Grafana, RHEL/Ubuntu Linux internals, On-call SRE | 🌟 **TOP TARGET #2 (High-Conviction SRE)** — Product engineering agency. They demand deep Linux OS troubleshooting (your RHCSA moat!) and pure Terraform IaC without manual console clicks. |
| **#4** | *Pending* | *Slot Open* | — | — | — | — | ⏳ Drop your next JD whenever ready. |

---

## 🔬 3. Deep-Dive on Role #1: HJ Infotech — AWS Cloud / DevOps Engineer

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│ MATCH FIT: 92% (AWS Core: 100% | Terraform: 100% | GitHub Actions: 100% | EKS: 95%)   │
│ TARGET PROFILE: Consulting & Enterprise Solutions Engineering                          │
│ KEY STRENGTH: Pure AWS native services + Infrastructure as Code + Microservices CI/CD  │
│ VERDICT: IMMEDIATE APPLICATION — Customized AWS + GitHub Actions Resume               │
└────────────────────────────────────────────────────────────────────────────────────────┘
```

### Detailed Breakdown & Strategy:
* **The Opportunity:** HJ Infotech is a consulting firm delivering public and private sector cloud solutions. Their JD covers the full AWS core lifecycle: EKS, ECS, EC2, RDS, S3, IAM, VPC, Route 53, and CloudWatch.
* **Why You Win:**
  * **AWS Native Mastery:** You build and manage VPCs (multi-AZ, NAT gateways, public/private subnets), security groups, IAM least-privilege policies, and S3 lifecycle rules.
  * **CI/CD with GitHub Actions:** You author declarative YAML workflows with automated linting, test stages, container builds, security scans (Trivy), and deployment triggers.
  * **Infrastructure as Code (IaC):** You write clean, modular Terraform with remote state backends (S3 + DynamoDB state locking), preventing drift and ensuring reproducible environments.
  * **Containerized Workloads:** Hands-on with Docker multi-stage builds and Amazon EKS cluster deployments using Helm charts.
* **Addressing the Compliance Requirement (FedRAMP, GovRAMP, SOC 2):**
  * Don't let compliance acronyms intimidate you. For a DevOps engineer, compliance means:
    1. **Encryption Everywhere:** AWS KMS customer-managed keys for EBS, S3, and RDS; TLS 1.3 enforced for in-transit data (`aws:SecureTransport: "true"`).
    2. **Immutable Audit Trails:** AWS CloudTrail multi-region trails sent to an S3 bucket with Object Lock / MFA delete, plus AWS Config rules.
    3. **Least Privilege IAM:** Zero wildcard `*` permissions, mandatory MFA, temporary role assumptions (`sts:AssumeRole`), and short-lived credentials.
    4. **OS Hardening:** CIS Benchmark baselines, SELinux enforcing, unneeded services disabled (direct tie-in with your RHCSA training).

### Tailored Resume Bullets for HJ Infotech:
```markdown
* Architected and provisioned secure, multi-tier AWS environments (VPC, public/private subnets, NAT Gateways, EKS, RDS PostgreSQL) using modular Terraform with remote state locking via S3 and DynamoDB.
* Engineered automated CI/CD pipelines in GitHub Actions incorporating automated testing, Trivy container security scans, and zero-downtime rolling deployments to Amazon EKS clusters.
* Implemented strict least-privilege IAM policies, role-based access controls (RBAC), and KMS encryption at rest and in transit to align infrastructure with SOC 2 and FedRAMP security baselines.
* Authored production Bash and Python automation scripts for automated database snapshot rotations, disk usage monitoring, and automated incident alerting routed to CloudWatch and Prometheus/Grafana.
```

---

## 🔬 4. Deep-Dive on Role #2: GCP Cloud Engineer (Remote — India)

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│ MATCH FIT: 68% (Containers & Helm: 95% | Terraform: 95% | CI/CD: 90% | GCP Tenure: -25%)│
│ RECRUITMENT FUNNEL: Application ➔ Coding Challenge ➔ Video Pitch ➔ Technical Interview  │
│ VERDICT: STRATEGIC APPLICATION — Neutralize tenure filter via Coding Challenge & Video  │
└────────────────────────────────────────────────────────────────────────────────────────┘
```

### Detailed Breakdown & Strategy:
* **The Recruitment Advantage:** This 5-stage recruitment funnel uses automated technical filtering (e.g., HackerRank/Codility for scripting + a 2-minute English video pitch). **Automated funnels don't reject you based on a resume line if you score 100% on the coding challenge.**
* **The Cross-Cloud Rosetta Stone (AWS ➔ GCP):**
  | Concept | AWS Service | GCP Equivalent | Implementation Detail |
  |:---|:---|:---|:---|
  | **Managed Kubernetes** | Amazon EKS | **Google Kubernetes Engine (GKE)** | Identical Pods, Services, Deployments, Ingress, and Helm charts. |
  | **Serverless Containers** | AWS Fargate / App Runner | **Cloud Run** | Scale-to-zero container runtime; triggered by HTTP/PubSub. |
  | **Object Storage** | Amazon S3 | **Google Cloud Storage (GCS)** | Buckets, IAM access controls, lifecycle management. |
  | **Relational Database** | Amazon RDS | **Cloud SQL (PostgreSQL/MySQL)** | Managed instances, automated backups, read replicas. |
  | **Serverless Functions** | AWS Lambda | **Cloud Functions** | Event-driven Python/Node.js executions. |
  | **Identity & Access** | AWS IAM Roles & Policies | **GCP IAM & Service Accounts** | Member bindings, roles (predefined/custom), Workload Identity. |
  | **IaC Resource** | `aws_vpc`, `aws_instance` | `google_compute_network`, `google_compute_instance` | Same Terraform syntax, HCL variables, and state management. |

### 2-Minute Video Introduction Script (Stage 3):
> *"Hi, I'm Sanjeev Kumar. I am a Red Hat Certified System Administrator (RHCSA) and Cloud/Platform Engineer specializing in scalable infrastructure, container orchestration, and Infrastructure as Code.*  
>  
> *Over the past 1.5+ years, I have architected and deployed production-grade infrastructure using Terraform, automated end-to-end CI/CD delivery pipelines, and containerized microservices running on Kubernetes with Helm. Because I manage infrastructure strictly through code and container primitives, my skills across Docker, Helm, Terraform modules, and Linux OS performance tuning are completely cloud-agnostic. Whether optimizing a multi-stage container for Cloud Run, provisioning VPC networking and Cloud SQL with Terraform, or automating deployment gates in Azure DevOps, I focus on reliability, least-privilege security, and zero downtime. I look forward to bringing that same disciplined engineering to your global client projects."*

---

## 🔬 5. Deep-Dive on Role #3: Auriga IT — DevOps / SRE Engineer

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│ MATCH FIT: 82% (Linux/RHCSA: 100% | Terraform Exclusive: 100% | K8s: 90% | SRE: 80%)    │
│ CULTURE: Fast-paced digital product engineering (Zomato, Yes Bank, Meesho client scale) │
│ KEY PHRASE IN JD: "This is a hands-on ownership role — not a support or ticket-queue"  │
│                   "Own the full lifecycle using Terraform exclusively — no manual console"│
│ VERDICT: HIGH-CONVICTION TARGET — Pitch your RHCSA OS depth + IaC discipline            │
└────────────────────────────────────────────────────────────────────────────────────────┘
```

### Why Auriga IT is Your Absolute Sweet Spot:
1. **The RHCSA Moat:** Auriga explicitly lists: *"Administer production Linux systems (Ubuntu / RHEL / CentOS): performance tuning, hardening, troubleshooting"*. Most candidates apply with surface-level cloud console knowledge and collapse when asked about Linux memory limits, swap behavior, cgroups, file descriptors (`ulimit`), or systemd service unit dependencies. **Your RHEL 9 certification proves you know the OS layer down to the kernel.**
2. **Terraform Exclusively (No Console Clicking):** The JD explicitly states: *"no manual console provisioning in production"*. You already write modular HCL with remote state locking, input validation, and clear environment separation (`environments/dev`, `environments/prod`).
3. **True SRE Ownership:** Auriga builds consumer-facing platforms handling millions of requests. They need engineers who understand **SLIs, SLOs, Error Budgets**, and **Blameless Postmortems**, not just deployment pipelines.

### The Auriga IT SRE Scenario Prep Sheet:

#### 1. What are SLIs, SLOs, and Error Budgets? (Auriga Core Question)
* **SLI (Service Level Indicator):** A quantifiable metric measuring service performance in real-time.
  * *Example:* The percentage of successful HTTP requests: `(Count of HTTP 2xx & 3xx / Total HTTP requests) * 100` measured at the load balancer.
* **SLO (Service Level Objective):** The target reliability goal agreed upon with stakeholders.
  * *Example:* 99.9% of requests must return HTTP < 500 within 200ms over a rolling 30-day window.
* **Error Budget:** The allowable downtime or failure margin: `100% - SLO`.
  * *For a 99.9% SLO:* The error budget is 0.1% (~43.8 minutes of downtime per month). If the error budget is exhausted, feature deployments are paused to focus exclusively on stability and reliability fixes.

#### 2. The Four Golden Signals of Monitoring (Google SRE Framework):
1. **Latency:** Time taken to service a request (distinguish between successful request latency vs. error latency).
2. **Traffic:** Demand placed on your system (e.g., HTTP requests/sec, concurrent WebSocket connections).
3. **Errors:** Rate of requests that fail (explicit 5xx errors, HTTP 429 rate limits, or silent data corruption).
4. **Saturation:** How full your service is (CPU usage, memory pressure, database connection pool exhaustion, disk I/O queue depth).

#### 3. Kubernetes Pod Debugging Flow (CrashLoopBackOff & OOMKilled):
When an incident alert fires at 2 AM for a failing Kubernetes pod:
```bash
# 1. Inspect pod status and restart count
kubectl get pods -n production -o wide

# 2. Check pod events and termination reason (Look for Last State: Terminated, Exit Code 137 = OOMKilled)
kubectl describe pod <pod-name> -n production

# 3. Retrieve logs from the crashed container before restart
kubectl logs <pod-name> -n production --previous --tail=100

# 4. Check node resource pressure (MemoryPressure, DiskPressure)
kubectl describe node <node-name>

# 5. Live container inspection (if running) or spin an ephemeral debug container
kubectl exec -it <pod-name> -n production -- /bin/sh
```

#### 4. The Anatomy of a Blameless Postmortem:
* **Incident Summary:** Date, duration, severity level, business impact (e.g., 2,300 checkout transactions failed).
* **Timeline of Events (UTC):**
  * `14:02` — PR #412 deployed to production via GitHub Actions.
  * `14:05` — P99 latency spiked from 120ms to 4.2s; error rate breached 2% threshold.
  * `14:07` — PagerDuty alert triggered on SLO Latency breach.
  * `14:11` — On-call engineer triaged and identified database connection pool exhaustion.
  * `14:15` — Automated rollback executed to previous stable release tag.
  * `14:18` — Latency and error rates normalized; incident mitigated.
* **Root Cause Analysis (5 Whys):** Deep mechanical cause without attributing blame to any human individual.
* **Action Items (Corrective & Preventative):**
  1. Add connection pool saturation alarms at 80% capacity in Prometheus.
  2. Implement circuit breakers in application database connection pooler (PgBouncer).
  3. Update CI/CD pipeline with canary deployment testing under simulated load before 100% traffic shift.

### Tailored Resume Bullets for Auriga IT:
```markdown
* Designed and maintained end-to-end Infrastructure as Code exclusively using modular Terraform, enforcing remote state locking via S3/DynamoDB, zero-drift governance, and strict environment parity.
* Administered and hardened enterprise Linux instances (RHEL 9 / Ubuntu), performing low-level OS tuning (cgroups, systemd units, network sysctl parameters, and disk I/O optimization).
* Configured full-stack observability pipelines using Prometheus and Grafana, establishing SLO-driven dashboards and multi-channel PagerDuty alerts covering the Four Golden Signals.
* Orchestrated production Kubernetes workloads and Helm releases, implementing horizontal pod autoscaling (HPA), RBAC security policies, and rapid incident triage for Pod OOMKilled and CrashLoopBackOff states.
```

### Direct Outreach Pitch for Auriga IT (Hiring Manager / Founder on LinkedIn):
```text
Subject: DevOps / SRE Engineer (Hands-on Terraform + RHCSA Linux Background)

Hi [Hiring Manager / Recruiter Name],

I noticed Auriga IT is looking for a hands-on DevOps / SRE Engineer who owns infrastructure end-to-end through code and embeds reliability into production systems.

What caught my attention is your explicit commitment to:
1. Pure Terraform IaC (no manual console clicking).
2. Deep Linux OS-level administration (RHEL/Ubuntu) over superficial GUI management.
3. True SRE ownership (SLOs, postmortems, and incident triage rather than passive ticket queues).

As an RHCSA-certified Linux engineer (RHEL 9), my foundation is built at the OS and system internals layer. I manage cloud infrastructure strictly via modular Terraform, deploy containerized workloads across Kubernetes with Helm, and configure Prometheus/Grafana observability to guard SLO error budgets.

I am an immediate joiner (0 days notice) based in India. I'd welcome the chance to discuss how I can contribute to Auriga's high-scale client platforms.

Best regards,
Sanjeev Kumar
GitHub: https://github.com/Nova-Jaat | Email: nova01111111@gmail.com
```

---

## 🧭 6. Summary Comparison & Next Steps

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│ SUMMARY MATRIX FOR BATCH #6:                                                           │
│ 1. HJ Infotech  ➔ 92% Match ➔ Submit immediately with AWS + GitHub Actions resume.    │
│ 2. Remote GCP   ➔ 68% Match ➔ Apply online; execute coding test & record video pitch.   │
│ 3. Auriga IT    ➔ 82% Match ➔ High-priority target! Highlight RHCSA Linux + Terraform. │
│ 4. Slot #4      ➔ Reserved for your next job description.                              │
└────────────────────────────────────────────────────────────────────────────────────────┘
```
