# Bailey Fitchett

**Senior DevOps / Platform Engineer · Azure · Terraform · GitHub · Azure DevOps**

I build repeatable infrastructure and delivery workflows that teams can understand, maintain, and operate. My experience spans Azure landing zones, Terraform automation, source-control migrations, GitHub Advanced Security, and agentic solutions in GitHub.

**I'm seeking Senior DevOps and Platform Engineering opportunities.**

## Start here

Three independent engineering demonstrations covering AI-assisted Terraform review, infrastructure change and recovery, migration verification, and secure delivery. Each project links the problem it addresses to runnable examples and validation evidence.

**Featured: AI-assisted Terraform review**

A local model selects infrastructure review questions from a fixed catalogue. Python validates every response against Terraform evidence, while the deterministic policy retains control of the review decision. The case study follows two observed model failures through stricter prompts and response schemas.

**Measured result:** one local Qwen 2.5 3B run passed **12/12 synthetic evaluation cases**, recording **8,946 tokens** and **160.7 seconds of combined chat latency**. Separately, **13/13 adversarial validator probes** were rejected. These results measure contract compliance on a small corpus; broader model quality and reviewer time savings remain unmeasured.

[See the local AI review](https://github.com/baileynyx/azure-platform-foundation/blob/main/docs/ai/local-recording/README.md) · [Results and original evidence](https://github.com/baileynyx/azure-platform-foundation/blob/main/docs/ai/local-evaluation/README.md) · [Reviewer code](https://github.com/baileynyx/azure-platform-foundation/blob/main/ai_review.py) · [Run locally without an Azure subscription](https://github.com/baileynyx/azure-platform-foundation/blob/main/docs/ollama-review.md)

**Watch the [30-second migration walkthrough](https://github.com/baileynyx/github-migration-readiness#watch-the-30-second-evidence-walkthrough):** see a real local Git rehearsal detect a missing branch, an unexpected branch, a changed branch and a changed tag annotation. [Static summary](https://github.com/baileynyx/github-migration-readiness/blob/main/docs/assets/ref-demo/summary.png) · [Text version and captured results](https://github.com/baileynyx/github-migration-readiness/blob/main/docs/assets/ref-demo/transcript.md).

**Try the migration tool:** [Download v1.0.0 ZIP](https://github.com/baileynyx/github-migration-readiness/releases/download/v1.0.0/github-migration-readiness-1.0.0.zip) · [Package quickstart](https://github.com/baileynyx/github-migration-readiness/blob/v1.0.0/QUICKSTART.md) · [Release and checksum](https://github.com/baileynyx/github-migration-readiness/releases/tag/v1.0.0).

| Project | Engineering problem and evidence | Explore |
| --- | --- | --- |
| [Azure platform foundation](https://github.com/baileynyx/azure-platform-foundation) | **Validate AI review questions, review infrastructure changes and rehearse drift recovery.** Optional second-team networking, reports that flag planned deletions/replacements, and a local-file rehearsal that detects external changes, checks a saved recovery plan, restores original bytes and verifies cleanup. **17 networking Terraform mock tests and 74 Python tests**, plus real local Terraform plan and drift rehearsals. | [AI evaluation case study](https://github.com/baileynyx/azure-platform-foundation/blob/main/docs/ai/local-evaluation/README.md) · [Networking demo](https://github.com/baileynyx/azure-platform-foundation/blob/main/DEMO.md) · [Plan review](https://github.com/baileynyx/azure-platform-foundation/blob/main/docs/plan-review.md) · [Drift recovery walkthrough](https://github.com/baileynyx/azure-platform-foundation/blob/main/docs/drift-rehearsal.md) · [Passing CI evidence](https://github.com/baileynyx/azure-platform-foundation/actions/runs/34581159235) |
| [GitHub migration readiness](https://github.com/baileynyx/github-migration-readiness) | **Find migration gaps and verify that branches and tags match.** Read-only Azure DevOps collection, actionable assessments and ref comparison, including changed tag annotations. Published **v1.0.0 ZIP tested on Windows (PowerShell) and Linux (Bash)** with Python 3.12: **50 product tests pass from each extracted package**, alongside example commands and a real-Git rehearsal. Both platforms produced identical ZIPs. | [Published release](https://github.com/baileynyx/github-migration-readiness/releases/tag/v1.0.0) · [Collector walkthrough](https://github.com/baileynyx/github-migration-readiness/blob/main/docs/azure-devops-collector.md) · [Ref verification rehearsal](https://github.com/baileynyx/github-migration-readiness/blob/main/docs/ref-verification.md) · [Windows and Linux package evidence](https://github.com/baileynyx/github-migration-readiness/actions/runs/34513354414) |
| [Secure delivery reference](https://github.com/baileynyx/secure-delivery-reference) | **Verify build provenance before promotion and check recovery behavior.** Provenance-gated promotion and HTTP-verified recovery, backed by **29 tests**, a real-signature integration check and a completed fresh signed-build rehearsal. The case study explains a verifier failure, its fix and release evidence. | [Engineering case study](https://github.com/baileynyx/secure-delivery-reference/blob/main/docs/attestation-verification-case-study.md) · [Five-minute demo](https://github.com/baileynyx/secure-delivery-reference/blob/main/DEMO.md) · [Validation record](https://github.com/baileynyx/secure-delivery-reference/blob/main/VALIDATION.md) |

**Validation scope:** Azure configuration uses mocked providers; the plan and drift rehearsals use temporary local Terraform state and disposable local resources, with no Azure deployment. Migration collection uses simulated API responses, while ref verification uses disposable local Git repositories; live collection remains unvalidated and matching refs alone does not certify a migration. Delivery uses disposable loopback services, historical signature checks and a [verified fresh version 1.0.1 build](https://github.com/baileynyx/secure-delivery-reference/actions/runs/34453548353); no production deployment is claimed.

## Engineering experience

- Designed, wrote, and implemented infrastructure automation with Terraform.
- Designed and automated Terraform deployment of Azure Landing Zones.
- Migrated TFS repositories to GitHub and Azure DevOps.
- Migrated Azure DevOps and Bitbucket repositories to GitHub.
- Implemented GitHub Advanced Security and developed agentic solutions in GitHub.

## How I approach engineering

Make changes reproducible. Give failures useful explanations. Keep credentials away from untrusted code. Document recovery before it is needed.

Beyond infrastructure, I'm a songwriter and fiction writer; I enjoy bringing both structure and imagination to difficult problems.
