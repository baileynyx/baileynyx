# Bailey Fitchett

**Senior DevOps / Platform Engineer · Azure · Terraform · GitHub · Azure DevOps**

I build repeatable infrastructure and delivery workflows that teams can understand, maintain, and operate. My experience spans Azure landing zones, Terraform automation, source-control migrations, GitHub Advanced Security, and agentic solutions in GitHub.

**I'm seeking Senior DevOps and Platform Engineering opportunities.**

## Start here

Three independent engineering demonstrations covering infrastructure change review, migration verification and secure delivery. Each project links the problem it addresses to runnable examples and validation evidence.

| Project | Engineering problem and evidence | Explore |
| --- | --- | --- |
| [Azure platform foundation](https://github.com/baileynyx/azure-platform-foundation) | **Extend shared networking and identify destructive changes before deployment.** Optional second-team networking with compatibility checks, plus Terraform plan reports that flag deletions and replacements. **17 Terraform mock tests and 19 Python tests**, with a real local Terraform plan rehearsal. | [Networking demo](https://github.com/baileynyx/azure-platform-foundation/blob/main/DEMO.md) · [Plan review walkthrough](https://github.com/baileynyx/azure-platform-foundation/blob/main/docs/plan-review.md) · [Passing CI evidence](https://github.com/baileynyx/azure-platform-foundation/actions/runs/34448629319) |
| [GitHub migration readiness](https://github.com/baileynyx/github-migration-readiness) | **Find migration gaps and verify that branches and tags match.** Read-only Azure DevOps collection, actionable assessments and ref comparison that detects missing, extra and changed refs, including changed tag annotations. **50 passing tests**, including a rehearsal with real Git and disposable local repositories. | [Collector walkthrough](https://github.com/baileynyx/github-migration-readiness/blob/main/docs/azure-devops-collector.md) · [Ref verification rehearsal](https://github.com/baileynyx/github-migration-readiness/blob/main/docs/ref-verification.md) · [Passing CI evidence](https://github.com/baileynyx/github-migration-readiness/actions/runs/34449910882) |
| [Secure delivery reference](https://github.com/baileynyx/secure-delivery-reference) | **Verify build provenance before promotion and check recovery behavior.** Provenance-gated promotion and HTTP-verified recovery, backed by **29 tests** and a real-signature integration check. The case study explains a verifier failure, its fix and regression evidence. | [Engineering case study](https://github.com/baileynyx/secure-delivery-reference/blob/main/docs/attestation-verification-case-study.md) · [Five-minute demo](https://github.com/baileynyx/secure-delivery-reference/blob/main/DEMO.md) · [Validation record](https://github.com/baileynyx/secure-delivery-reference/blob/main/VALIDATION.md) |

**Validation scope:** Azure configuration uses mocked providers; the plan rehearsal uses temporary local Terraform state and deploys no Azure resources. Migration collection uses simulated API responses, while ref verification uses disposable local Git repositories; live collection remains unvalidated and matching refs alone does not certify a migration. Delivery uses disposable loopback services and a historical signed build; a complete fresh manual release after the verifier fix remains pending.

## Engineering experience

- Designed, wrote, and implemented infrastructure automation with Terraform.
- Designed and automated Terraform deployment of Azure Landing Zones.
- Migrated TFS repositories to GitHub and Azure DevOps.
- Migrated Azure DevOps and Bitbucket repositories to GitHub.
- Implemented GitHub Advanced Security and developed agentic solutions in GitHub.

## How I approach engineering

Make changes reproducible. Give failures useful explanations. Keep credentials away from untrusted code. Document recovery before it is needed.

Beyond infrastructure, I'm a songwriter and fiction writer; I enjoy bringing both structure and imagination to difficult problems.
