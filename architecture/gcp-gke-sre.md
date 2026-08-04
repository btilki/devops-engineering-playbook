# Architecture: GCP GKE SRE

**Project:** [boutique-gke-sre](https://github.com/btilki/boutique-gke-sre)

## Context

Reliability-oriented platform on a single private regional GKE cluster. Focus: SLOs, burn-rate alerting, PagerDuty routing, runbooks, plus GitOps and supply-chain controls. Infrastructure was decommissioned after validation; docs and screenshots remain.

## Components (outline)

- Private regional GKE cluster
- GitOps (Argo CD)
- Observability (OTel / Grafana path as documented upstream)
- SLOs and burn-rate alerts → PagerDuty
- Supply-chain / policy controls (Kyverno, related baselines)
- Workload Identity Federation for CI (keyless)
- Binary Authorization / Cloud Armor baseline (as documented)

## Diagram

Canonical overview lives upstream:

- [README (hero Mermaid)](https://github.com/btilki/boutique-gke-sre#what-this-is)
- [ARCHITECTURE.md](https://github.com/btilki/boutique-gke-sre/blob/main/ARCHITECTURE.md)
- [Architecture overview](https://github.com/btilki/boutique-gke-sre/blob/main/docs/architecture/overview.md)
- [Operations runbook](https://github.com/btilki/boutique-gke-sre/blob/main/docs/operations/operations-runbook.md)

## Related

- Featured project brief: [../featured-projects/boutique-gke-sre.md](../featured-projects/boutique-gke-sre.md)
- Articles: [G1](../articles/G1.md), [G2](../articles/G2.md), [G3](../articles/G3.md)
- Lab: SRE on GKE — see [../labs/](../labs/)
