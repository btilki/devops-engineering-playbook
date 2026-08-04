# Architecture: Azure AKS DevSecOps

**Project:** [boutique-aks-devsecops](https://github.com/btilki/boutique-aks-devsecops)

## Context

Security-integrated delivery on Azure Kubernetes Service. GitHub is the git source of truth; Azure DevOps runs CI (OIDC). Signed digests and Kyverno admission enforce what can run.

## Components (outline)

- Azure Kubernetes Service (AKS) — one cost-conscious cluster, `dev` / `stage` / `prod` namespaces
- Azure Container Registry (ACR)
- Azure DevOps pipelines (Trivy → cosign → digest promote)
- Argo CD GitOps
- Kyverno policies (digest / signature admission)
- Key Vault + secrets integration
- Observability baseline (metrics / Grafana path as documented upstream)

## Diagram

Canonical CI / GitOps flow is in the upstream README:

- [README — CI story](https://github.com/btilki/boutique-aks-devsecops#ci-story)
- [ARCHITECTURE.md](https://github.com/btilki/boutique-aks-devsecops/blob/main/ARCHITECTURE.md)
- [Threat model](https://github.com/btilki/boutique-aks-devsecops/blob/main/docs/security/threat-model.md)
- [CI pipeline setup](https://github.com/btilki/boutique-aks-devsecops/blob/main/docs/setup/09-ci-pipeline.md)

## Related

- Featured project brief: [../featured-projects/boutique-aks-devsecops.md](../featured-projects/boutique-aks-devsecops.md)
- Articles: [A1](../articles/A1.md), [A2](../articles/A2.md), [A3](../articles/A3.md)
- Lab: DevSecOps on AKS — see [../labs/](../labs/)
