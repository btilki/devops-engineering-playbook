# DevOps Engineering Playbook

**Production-ready learning resources for DevOps, GitOps, DevSecOps, Site Reliability Engineering (SRE), and Platform Engineering.**

> Learn by Building. Master by Practicing. Share by Teaching.

This repository is the central hub for my production-inspired cloud projects, practical engineering books, technical articles, and structured learning paths.

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

## Featured Projects

Three cloud boutique platforms plus a learning-by-building companion.

### 1. Boutique EKS GitOps (AWS)

Production-inspired GitOps on Amazon EKS: Git-driven delivery, Helm, and platform patterns for real environments.

- **Repository:** [btilki/boutique-eks-gitops](https://github.com/btilki/boutique-eks-gitops)
- **Cloud:** AWS
- **Focus:** GitOps, EKS, continuous delivery
- **Playbook notes:** [featured-projects/boutique-eks-gitops.md](./featured-projects/boutique-eks-gitops.md)

### 2. Boutique AKS DevSecOps (Azure)

Security-first delivery on Azure Kubernetes Service: shift-left scanning, policy, and DevSecOps workflows.

- **Repository:** [btilki/boutique-aks-devsecops](https://github.com/btilki/boutique-aks-devsecops)
- **Cloud:** Azure
- **Focus:** DevSecOps, AKS, policy as code
- **Playbook notes:** [featured-projects/boutique-aks-devsecops.md](./featured-projects/boutique-aks-devsecops.md)

### 3. Boutique GKE SRE (GCP)

Reliability and operations on Google Kubernetes Engine: observability, SLOs, and SRE practices.

- **Repository:** [btilki/boutique-gke-sre](https://github.com/btilki/boutique-gke-sre)
- **Cloud:** GCP
- **Focus:** SRE, GKE, observability
- **Playbook notes:** [featured-projects/boutique-gke-sre.md](./featured-projects/boutique-gke-sre.md)

### 4. Learn DevOps by Building

Companion learning material that reinforces the same engineering practices through structured building.

- **Repository:** [btilki/learn-devops-by-building](https://github.com/btilki/learn-devops-by-building)
- **Focus:** Hands-on learning paths and practice
- **Playbook notes:** [featured-projects/learn-devops-by-building.md](./featured-projects/learn-devops-by-building.md)

---

## Books

Practical books aligned with the projects and labs. Detailed indexes live under [`books/`](./books/).

| Book area | Audience | Themes |
|-----------|----------|--------|
| DevOps | Intermediate engineers | Containers, CI/CD, Terraform, Kubernetes |
| GitOps / Cloud platforms | Intermediate–advanced | EKS, Helm, Argo CD, delivery patterns |
| DevSecOps | Intermediate–advanced | Shift-left security, scanning, policy |
| SRE | Intermediate–advanced | Reliability, observability, operations |

See: [books/README.md](./books/README.md)

---

## Technical Articles

Focused technical writing (including Medium publications) mapped to projects and domains.

Browse the index: [articles/README.md](./articles/README.md)

Articles are grouped by theme (GitOps, DevSecOps, SRE, Platform Engineering) rather than by publication channel.

---

## Learning Paths

Suggested routes for engineers who want a structured progression.

```text
Containers → Kubernetes → Terraform / IaC
        → GitOps → Security (DevSecOps)
        → Observability / SRE → Platform Engineering
```

Path outlines:

- [DevOps Engineer](./learning-paths/devops-engineer.md)
- [GitOps Practitioner](./learning-paths/gitops-practitioner.md)
- [DevSecOps Engineer](./learning-paths/devsecops-engineer.md)
- [Site Reliability Engineer](./learning-paths/site-reliability-engineer.md)

Index: [learning-paths/README.md](./learning-paths/README.md)

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

1. This README (orientation)
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
├── learning-paths/           ← structured skill paths
├── architecture/             ← multi-cloud architecture notes
├── labs/                     ← hands-on lab entry points
├── roadmaps/                 ← longer-term skill roadmaps
├── cheatsheets/              ← quick reference sheets
└── interview-prep/           ← interview-oriented prompts & topics
```

> **Note:** A local `campaign/` directory may exist for LinkedIn drafts, outreach templates, and application tracking. It is private and not part of the published playbook.

---

## About the Author

**Birol Tilki** — DevOps / Platform-focused engineer building production-inspired platforms across AWS, Azure, and GCP, with emphasis on GitOps, DevSecOps, and SRE practices.

I learn by building real systems, deepen understanding through documentation and books, and share through technical articles and structured learning material.

---

## Connect

- **GitHub:** [github.com/btilki](https://github.com/btilki)
- **Featured projects:** links in the section above
- **LinkedIn:** add your profile URL here

---

## Support

If these resources help you in your DevOps journey, consider starring the repositories, sharing the articles, or connecting on LinkedIn.

---

*DevOps Engineering Playbook v1.0 — Learn by Building. Master by Practicing. Share by Teaching.*
