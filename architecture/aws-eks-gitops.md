# Architecture: AWS EKS GitOps

**Project:** [boutique-eks-gitops](https://github.com/btilki/boutique-eks-gitops)

## Context

Git-driven delivery on Amazon EKS for a production-inspired boutique platform. **CI never deploys** — pipelines produce digest-only merge requests; Argo CD reconciles from Git.

## Components (outline)

- Amazon EKS cluster (single cluster, `dev` / `stage` / `prod` namespaces)
- Git as source of truth (digest pins under `gitops/envs/`)
- Helm charts for Online Boutique services
- Argo CD (app-of-apps + ApplicationSet; manual sync for prod)
- GitLab CI: build → Trivy → cosign → digest MR
- Kyverno, External Secrets, NetworkPolicy baseline
- Prometheus, Loki, Grafana, Alertmanager

## Diagram

Canonical Mermaid diagram and narrative live in the upstream README and docs:

- [README (hero diagram)](https://github.com/btilki/boutique-eks-gitops#boutique-eks-gitops)
- [docs/ARCHITECTURE.md](https://github.com/btilki/boutique-eks-gitops/blob/main/docs/ARCHITECTURE.md)
- [Deployment flow](https://github.com/btilki/boutique-eks-gitops/blob/main/docs/architecture/05-deployment-flow.md)
- [ADR: digest-only GitOps](https://github.com/btilki/boutique-eks-gitops/blob/main/docs/adr/0001-digest-only-gitops.md)

## Related

- Featured project brief: [../featured-projects/boutique-eks-gitops.md](../featured-projects/boutique-eks-gitops.md)
- Articles: [E1](../articles/E1.md), [E2](../articles/E2.md), [E3](../articles/E3.md)
- Lab: GitOps on EKS — see [../labs/](../labs/)
