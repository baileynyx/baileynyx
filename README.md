# Bailey Fitchett

**Senior DevOps / Platform Engineer · Azure · Terraform · GitHub · Azure DevOps**

I build repeatable infrastructure and delivery workflows that teams can understand, maintain, and operate. My experience spans Azure landing zones, Terraform automation, source-control migrations, GitHub Advanced Security, and agentic solutions in GitHub.

**I'm seeking Senior DevOps and Platform Engineering opportunities.**

## Start here

Three independent engineering demonstrations covering infrastructure change review, migration verification and secure delivery. Each project links the problem it addresses to runnable examples and validation evidence.

**Start with the [30-second migration walkthrough](https://github.com/baileynyx/github-migration-readiness#watch-the-30-second-evidence-walkthrough):** see a real local Git rehearsal detect a missing branch, an unexpected branch, a changed branch and a changed tag annotation. [Static summary](https://github.com/baileynyx/github-migration-readiness/blob/main/docs/assets/ref-demo/summary.png) · [Text version and captured results](https://github.com/baileynyx/github-migration-readiness/blob/main/docs/assets/ref-demo/transcript.md).

| Project | Engineering problem and evidence | Explore |
| --- | --- | --- |
| [Azure platform foundation](https://github.com/baileynyx/azure-platform-foundation) | **Extend shared networking and identify destructive changes before deployment.** Optional second-team networking with compatibility checks, plus Terraform plan reports that flag deletions and replacements. **17 Terraform mock tests and 19 Python tests**, with a real local Terraform plan rehearsal. | [Networking demo](https://github.com/baileynyx/azure-platform-foundation/blob/main/DEMO.md) · [Plan review walkthrough](https://github.com/baileynyx/azure-platform-foundation/blob/main/docs/plan-review.md) · [Passing CI evidence](https://github.com/baileynyx/azure-platform-foundation/actions/runs/34448629319) |
| [GitHub migration readiness](https://github.com/baileynyx/github-migration-readiness) | **Find migration gaps and verify that branches and tags match.** Read-only Azure DevOps collection, actionable assessments and ref comparison that detects missing, extra and changed refs, including changed tag annotations. **50 tests passing on each of Windows (PowerShell) and Linux (Bash)** with Python 3.12, plus a standalone real-Git rehearsal on both platforms. | [Collector walkthrough](https://github.com/baileynyx/github-migration-readiness/blob/main/docs/azure-devops-collector.md) · [Ref verification rehearsal](https://github.com/baileynyx/github-migration-readiness/blob/main/docs/ref-verification.md) · [Windows and Linux CI evidence](https://github.com/baileynyx/github-migration-readiness/actions/runs/34485143067) |
| [Secure delivery reference](https://github.com/baileynyx/secure-delivery-reference) | **Verify build provenance before promotion and check recovery behavior.** Provenance-gated promotion and HTTP-verified recovery, backed by **29 tests**, a real-signature integration check and a completed fresh signed-build rehearsal. The case study explains a verifier failure, its fix and release evidence. | [Engineering case study](https://github.com/baileynyx/secure-delivery-reference/blob/main/docs/attestation-verification-case-study.md) · [Five-minute demo](https://github.com/baileynyx/secure-delivery-reference/blob/main/DEMO.md) · [Validation record](https://github.com/baileynyx/secure-delivery-reference/blob/main/VALIDATION.md) |

**Validation scope:** Azure configuration uses mocked providers; the plan rehearsal uses temporary local Terraform state and deploys no Azure resources. Migration collection uses simulated API responses, while ref verification uses disposable local Git repositories; live collection remains unvalidated and matching refs alone does not certify a migration. Delivery uses disposable loopback services, historical signature checks and a [verified fresh version 1.0.1 build](https://github.com/baileynyx/secure-delivery-reference/actions/runs/34453548353); no production deployment is claimed.

## Engineering experience

- Designed, wrote, and implemented infrastructure automation with Terraform.
- Designed and automated Terraform deployment of Azure Landing Zones.
- Migrated TFS repositories to GitHub and Azure DevOps.
- Migrated Azure DevOps and Bitbucket repositories to GitHub.
- Implemented GitHub Advanced Security and developed agentic solutions in GitHub.

## How I approach engineering

Make changes reproducible. Give failures useful explanations. Keep credentials away from untrusted code. Document recovery before it is needed.

Beyond infrastructure, I'm a songwriter and fiction writer; I enjoy bringing both structure and imagination to difficult problems.
