# DevOps Engineering Playbook

**Production-ready learning resources for DevOps, GitOps, DevSecOps, Site Reliability Engineering (SRE), and Platform Engineering.**

> Learn by Building. Master by Practicing. Share by Teaching.

This repository is the central hub for my production-inspired cloud projects, practical engineering books, technical articles, and structured learning paths.

---

## Start here

**New here?**

| If you are… | Do this |
|-------------|---------|
| **Recruiter / hiring manager** | 1) [Featured Projects](#featured-projects) → 2) [Learning Matrix](#learning-matrix) → 3) one [Technical Article](./articles/) → 4) [Books](#books) |
| **Engineer learning** | Open the [Learning Matrix](#learning-matrix), pick a row, follow **Read → Build → Practice** |
| **Comparing clouds** | [Architecture Gallery](#architecture-gallery) + articles [X1](./articles/X1.md) / [X2](./articles/X2.md) |

---

## Mission

Help engineers move beyond toy tutorials by learning how real multi-cloud platforms are designed, automated, secured, and operated.

This playbook connects:

- **Featured projects** — production-inspired platforms on AWS, Azure, and GCP
- **Books** — deeper explanations and hands-on practice
- **Technical articles** — focused write-ups you can share and reuse
- **Learning paths** — clear routes from fundamentals to platform engineering

---

## Why this repository?

Most portfolios list repositories. This one explains how they fit together.

| Without a playbook | With this playbook |
|--------------------|--------------------|
| Scattered repos | One narrative across AWS, Azure, and GCP |
| Projects without context | Projects mapped to books, articles, and labs |
| “I used Kubernetes” | GitOps, DevSecOps, and SRE practiced end to end |
| Hard for recruiters to navigate | A single entry point for technical depth |

If you are a recruiter, hiring manager, or engineer evaluating my work, start here — then dive into the featured projects.

---

## Engineering Domains

| Domain | Focus |
|--------|--------|
| **DevOps** | Automation, CI/CD, Infrastructure as Code |
| **GitOps** | Argo CD, Helm, Git-driven deployments |
| **DevSecOps** | Shift-left security, policy as code, supply-chain controls |
| **SRE** | Reliability, observability, incident readiness |
| **Platform Engineering** | Developer experience, internal platforms, paved roads |

---

## Learning Matrix

**Signature view of this playbook:** pick what you want to learn, then follow Read → Build → Practice.

| I want to learn… | Read | Build | Practice |
|------------------|------|-------|----------|
| **GitOps** | [DevOps book](./books/devops.md) (D11–D12) | [Boutique EKS GitOps](https://github.com/btilki/boutique-eks-gitops) | [E1](./articles/E1.md), [E2](./articles/E2.md), [E3](./articles/E3.md) |
| **DevSecOps** | [DevSecOps book](./books/devsecops.md) | [Boutique AKS DevSecOps](https://github.com/btilki/boutique-aks-devsecops) | [A1](./articles/A1.md), [A2](./articles/A2.md), [A3](./articles/A3.md) |
| **SRE** | [SRE book](./books/sre.md) | [Boutique GKE SRE](https://github.com/btilki/boutique-gke-sre) | [G1](./articles/G1.md), [G2](./articles/G2.md), [G3](./articles/G3.md) |
| **Platform / multi-cloud** | [Platform book](./books/platform.md) | All boutique platforms + [playbook](./) | [X1](./articles/X1.md), [X2](./articles/X2.md) |
| **DevOps foundations** | [DevOps book](./books/devops.md) | [learn-devops-by-building](https://github.com/btilki/learn-devops-by-building) | Sampler in [SERIES.md](https://github.com/btilki/learn-devops-by-building/blob/main/SERIES.md) |

Full matrix notes: [learning-paths/learning-matrix.md](./learning-paths/learning-matrix.md)

---

## Featured Projects

Three cloud boutique platforms plus a learning-by-building companion.

| Project | Focus | Cloud | What you’ll learn | Brief |
|---------|-------|-------|-------------------|--------|
| [Boutique EKS GitOps](https://github.com/btilki/boutique-eks-gitops) | GitOps | AWS | Digest-only delivery, Argo CD, Terraform, progressive delivery (no mesh required) | [notes](./featured-projects/boutique-eks-gitops.md) |
| [Boutique AKS DevSecOps](https://github.com/btilki/boutique-aks-devsecops) | DevSecOps | Azure | Supply-chain security, Kyverno, Trivy, Cosign, GitHub + Azure DevOps | [notes](./featured-projects/boutique-aks-devsecops.md) |
| [Boutique GKE SRE](https://github.com/btilki/boutique-gke-sre) | SRE | GCP | SLIs/SLOs, burn-rate alerting, PagerDuty, observability, keyless CI | [notes](./featured-projects/boutique-gke-sre.md) |
| [Learn DevOps by Building](https://github.com/btilki/learn-devops-by-building) | Learning | Multi | Workshop chapters with a shared Problem→Build→Observe spine | [notes](./featured-projects/learn-devops-by-building.md) |

### 1. Boutique EKS GitOps (AWS)

Production-inspired GitOps on Amazon EKS: Git-driven delivery, Helm, and platform patterns for real environments.

- **Repository:** [btilki/boutique-eks-gitops](https://github.com/btilki/boutique-eks-gitops)
- **Hard rule:** CI never deploys — digests land via Git; Argo CD reconciles
- **Playbook notes:** [featured-projects/boutique-eks-gitops.md](./featured-projects/boutique-eks-gitops.md)

### 2. Boutique AKS DevSecOps (Azure)

Security-first delivery on Azure Kubernetes Service: shift-left scanning, policy, and DevSecOps workflows.

- **Repository:** [btilki/boutique-aks-devsecops](https://github.com/btilki/boutique-aks-devsecops)
- **Hard rule:** Unsigned / non-compliant images should not reach the cluster
- **Playbook notes:** [featured-projects/boutique-aks-devsecops.md](./featured-projects/boutique-aks-devsecops.md)

### 3. Boutique GKE SRE (GCP)

Reliability and operations on Google Kubernetes Engine: observability, SLOs, and SRE practices.

- **Repository:** [btilki/boutique-gke-sre](https://github.com/btilki/boutique-gke-sre)
- **Hard rule:** Deployed ≠ reliable — SLOs, paging, and runbooks required
- **Playbook notes:** [featured-projects/boutique-gke-sre.md](./featured-projects/boutique-gke-sre.md)

### 4. Learn DevOps by Building

Companion workshop books that reinforce the same engineering practices through structured building.

- **Repository:** [btilki/learn-devops-by-building](https://github.com/btilki/learn-devops-by-building)
- **Playbook notes:** [featured-projects/learn-devops-by-building.md](./featured-projects/learn-devops-by-building.md)

---

## Books

Workshop books from [learn-devops-by-building](https://github.com/btilki/learn-devops-by-building). Detailed indexes live under [`books/`](./books/).

| Book | Who is this for? | Themes |
|------|------------------|--------|
| [DevOps Engineering](./books/devops.md) | Intermediate engineers building delivery foundations (strong juniors welcome via sampler) | CI/CD, IaC, Kubernetes, GitOps, multi-cloud |
| [DevSecOps](./books/devsecops.md) | Intermediate engineers embedding security into delivery | Secrets, supply chain, policy, identity |
| [SRE](./books/sre.md) | Intermediate–advanced engineers owning reliability | SLOs, alerting, incidents, chaos, DR |
| [Platform Engineering](./books/platform.md) | Intermediate–advanced engineers building internal platforms | Golden paths, environments, governance, DX |

See: [books/README.md](./books/README.md) · [SERIES.md](https://github.com/btilki/learn-devops-by-building/blob/main/SERIES.md)

---

## Technical Articles

Focused technical writing mapped to projects and domains. Full index: [articles/README.md](./articles/README.md)

| ID | Theme | Est. read | Project |
|----|-------|-----------|---------|
| [E1](./articles/E1.md)–[E3](./articles/E3.md) | GitOps | ~7–10 min each | EKS |
| [A1](./articles/A1.md)–[A3](./articles/A3.md) | DevSecOps | ~7–10 min each | AKS |
| [G1](./articles/G1.md)–[G3](./articles/G3.md) | SRE | ~8–12 min each | GKE |
| [X1](./articles/X1.md)–[X2](./articles/X2.md) | Multi-cloud / platform | ~8–12 min each | All |

---

## Learning Paths

Suggested routes for engineers who want a structured progression.

```text
Junior / early DevOps
        ↓
Containers
        ↓
Kubernetes
        ↓
Terraform / IaC
        ↓
GitOps
        ↓
Security (DevSecOps)
        ↓
Observability / SRE
        ↓
Platform Engineering
```

Path outlines:

- [DevOps Engineer](./learning-paths/devops-engineer.md)
- [GitOps Practitioner](./learning-paths/gitops-practitioner.md)
- [DevSecOps Engineer](./learning-paths/devsecops-engineer.md)
- [Site Reliability Engineer](./learning-paths/site-reliability-engineer.md)
- [Learning Matrix](./learning-paths/learning-matrix.md)

Index: [learning-paths/README.md](./learning-paths/README.md) · Roadmaps: [roadmaps/](./roadmaps/)

---

## Architecture Gallery

Reference architectures for the three boutique platforms — same design language across clouds.

| Cloud | Platform | Notes |
|-------|----------|--------|
| AWS | EKS + GitOps | [architecture/aws-eks-gitops.md](./architecture/aws-eks-gitops.md) |
| Azure | AKS + DevSecOps | [architecture/azure-aks-devsecops.md](./architecture/azure-aks-devsecops.md) |
| GCP | GKE + SRE | [architecture/gcp-gke-sre.md](./architecture/gcp-gke-sre.md) |

Index: [architecture/README.md](./architecture/README.md)

---

## Hands-on Labs

Labs map directly to the featured repositories.

| Lab | Cloud | Difficulty | Project |
|-----|-------|------------|---------|
| GitOps on EKS | AWS | Intermediate | [boutique-eks-gitops](https://github.com/btilki/boutique-eks-gitops) |
| DevSecOps on AKS | Azure | Advanced | [boutique-aks-devsecops](https://github.com/btilki/boutique-aks-devsecops) |
| SRE on GKE | GCP | Advanced | [boutique-gke-sre](https://github.com/btilki/boutique-gke-sre) |

Lab guides: [labs/README.md](./labs/README.md)

---

## Recommended Reading Order

1. This README — especially [Start here](#start-here) and [Learning Matrix](#learning-matrix)
2. [Featured projects](./featured-projects/) matching your cloud interest
3. Matching [architecture](./architecture/) note
4. Related [learning path](./learning-paths/)
5. Supporting [book](./books/) chapters and [articles](./articles/)
6. Hands-on work in the upstream repository

---

## Technology Stack

### Cloud

- AWS — Amazon EKS
- Azure — Azure Kubernetes Service (AKS)
- Google Cloud — Google Kubernetes Engine (GKE)

### Containers & delivery

- Docker
- Kubernetes
- Helm
- Argo CD

### Infrastructure as Code

- Terraform

### Observability

- Prometheus
- Grafana
- Loki

### Security

- Trivy
- Falco
- Kyverno

Stack notes will expand under each featured project page.

---

## Repository map

```text
devops-engineering-playbook/
├── README.md                 ← you are here
├── featured-projects/        ← project briefs + links
├── books/                    ← book indexes
├── articles/                 ← technical article index
├── learning-paths/           ← structured skill paths + learning matrix
├── architecture/             ← multi-cloud architecture notes
├── labs/                     ← hands-on lab entry points
├── roadmaps/                 ← longer-term skill roadmaps
├── cheatsheets/              ← quick reference sheets
└── interview-prep/           ← interview-oriented prompts & topics
```

> **Note:** A local `campaign/` directory may exist for LinkedIn drafts, outreach templates, and application tracking. It is private and not part of the published playbook.

---

## FAQ

**Why three cloud platforms instead of one?**  
One application family, three lenses: GitOps (EKS), DevSecOps (AKS), SRE (GKE). Multi-cloud here means comparable engineering questions — not logo collecting.

**Which project should I start with?**  
Match the job you want: AWS/GitOps → EKS; Azure/security → AKS; GCP/reliability → GKE. Unsure → [Learning Matrix](#learning-matrix).

**Can I use these projects for learning?**  
Yes. Follow each repo’s docs and licenses. Infra may be torn down; the Git history, ADRs, and runbooks are the lasting artifacts.

**Are the books free?**  
The workshop materials in [learn-devops-by-building](https://github.com/btilki/learn-devops-by-building) are published under that repository’s license (CC BY 4.0) — see upstream README.

**How are articles connected to the repositories?**  
Each article ID (E/A/G/X) maps to a project and theme in [articles/](./articles/). The [Learning Matrix](#learning-matrix) shows Read → Build → Practice in one view.

**Is the infrastructure still running?**  
Pilots were validated then decommissioned where noted in each project README. Expect docs and screenshots, not vanity DNS.

---

## About the Author

**Birol Tilki** — DevOps / Platform-focused engineer building production-inspired platforms across AWS, Azure, and GCP, with emphasis on GitOps, DevSecOps, and SRE practices.

I learn by building real systems, deepen understanding through documentation and books, and share through technical articles and structured learning material.

---

## Connect

- **GitHub:** [github.com/btilki](https://github.com/btilki)
- **Featured projects:** links in the section above
- **LinkedIn:** [linkedin.com/in/birol-tilki-48731326](https://www.linkedin.com/in/birol-tilki-48731326/)

---

## Support

If these resources help you in your DevOps journey, consider starring the repositories, sharing the articles, or connecting on LinkedIn.

---

*DevOps Engineering Playbook **v1.1** — Start Here + Learning Matrix — Learn by Building. Master by Practicing. Share by Teaching.*
