# Krantiyatra

**Citizen-centred governance. Evidence-informed participation. Public accountability.**

[Website](https://www.krantiyatra.org) · [Vision](VISION.md) · [Roadmap](ROADMAP.md) · [Research workflow](docs/RESEARCH_WORKFLOW.md) · [Architecture decisions](docs/ARCHITECTURE_DECISIONS.md) · [Demo and evidence](DEMO.md) · [People and contributions](CONTRIBUTORS.md)

> **Development status — 17 November 2026:** Early-stage project and public-facing repository documentation. This README describes a proposed open-source civic-governance direction; it does **not** claim that the features below are built, deployed, independently validated, or available as a downloadable platform. See [DEMO.md](DEMO.md) for verified demonstrations and current availability.

## The problem

People experience public problems locally, but the path from their concerns to research, collective deliberation, institutional decisions and implementation is often difficult to follow. A complaint can be closed without resolving a structural cause; a consultation can collect opinions without exposing the evidence or showing how responses changed a decision; published policy material can be inaccessible or hard to connect to places and people.

These are problems to investigate and test with communities and institutions, not claims that every existing system fails.

## Our response

**Krantiyatra** is a citizen-led policy research institution developing an **open-source civic participation and governance platform**. Its intended purpose is to help communities, researchers, civil society and public institutions turn public concerns into evidence-informed participation and traceable public action.

The proposed platform brings together:

- **Citizen concerns:** safe intake and screening, with clear distinctions between a service complaint and a researchable public-policy question.
- **Public knowledge:** understandable publications, accessible evidence, provenance and contextual resources.
- **Participation:** structured proposals, consultations, deliberation and collaborative policy development, subject to governance rules.
- **Geographic context:** issue and decision histories grounded in localities and civic jurisdictions, beginning with Bengaluru.
- **Institutional responses:** attributable replies, publicly understandable decisions, documented rationales and follow-up.
- **Accountability:** progress states and updates that let participants distinguish a promise, a decision, an implementation step and a verified outcome.

These are **intended capabilities, not a shipped feature list**. Their release order and technical design remain subject to user research, pilot findings and public governance standards.

## What makes this initiative distinct?

We are exploring whether participation can be more useful when citizen concerns, evidence, place, deliberation, decisions and implementation remain connected. We seek to **complement and learn from** mature civic platforms such as [Decidim](https://decidim.org/), rather than dismiss them. Decidim already supports proposals, participatory processes, budgeting, assemblies and accountability. The question is what additional value Krantiyatra can demonstrate through real deployment, especially for Indian local-governance contexts.

Read the [vision and comparison](VISION.md) for hypotheses and testable differentiators.

## Scope and product boundary

- **Krantiyatra.org:** public-facing institution, civic information, publications and the proposed open-source governance application.
- **Kranty:** a separate collaborative research product, developed privately. Krantiyatra may use its permitted research outputs or services, but the public Krantiyatra repository does not contain or imply release of Kranty's private source, user records, or internal infrastructure.

A public Krantiyatra deployment **must not depend on unauthorized access to private Kranty data**. Any integration will require a documented interface, consent and permissions.

## Example end-to-end journey (design scenario, not a deployed case)

A Bengaluru resident raises an issue about irregular waste collection. A screened public issue is linked to municipal boundaries, documented datasets and independently assessed evidence. Residents and researchers discuss causes and policy alternatives. A public institution may respond with a reasoned decision; milestones can then track progress and corrections. The visible record should show what was said, what was evidenced, what was decided and what happened next.

See the complete [illustrative workflow](docs/RESEARCH_WORKFLOW.md), including safeguarding and permissions.

## Development and participation

We are building the initial product direction and documentation. Research, UX, accessibility, governance, documentation, data work, engineering, quality assurance and community testing are all potential contribution areas. The repository will open external contribution pathways progressively, with clearly identified maintainers and issue labels.

See [CONTRIBUTORS.md](CONTRIBUTORS.md) for attribution rules. Existing team members are not publicly named without their approval.

## Current links

| Resource | Status |
| --- | --- |
| [krantiyatra.org](https://www.krantiyatra.org) | Official project domain; availability and feature completeness must be checked independently |
| Live civic governance MVP | **Not verified here**; do not describe it as deployed until demonstration evidence exists |
| [Demo record](DEMO.md) | Template for verified build URLs, screenshots and walkthroughs |
| [Roadmap](ROADMAP.md) | Proposed milestones, not feature-release commitments |
| Public license | **Pending decision**; repository visibility alone does not grant open-source rights |

## Principles

Human dignity and safety; accessible participation; explicit source provenance; transparency about uncertainty; plural viewpoints; meaningful local context; traceable institutional action; privacy by design; and human accountability for published conclusions. Popularity is not verification, and AI output is not independent evidence.

## Stewardship

**Founder and product vision:** [alantony106](https://github.com/alantony106) (founder attribution supplied for this repository; public display name may be updated by the founder). Individual contributions will be credited through commit history, reviewed pull requests and the consent-based contributor register.

The open-source licensing model, government deployment terms, maintainership and constitutional governance of this project will be published after review. There is currently no assertion that the public has redistribution rights to unreleased code.

## References and inspiration

- [Decidim: features](https://decidim.org/features)
- [Decidim: documentation](https://docs.decidim.org/)
- [Mozilla Foundation: 2027 fellowship call](https://www.mozillafoundation.org/en/what-we-do/grantmaking/fellowship/2027-call-for-applications/)

*Documentation version: public draft 0.1 — 17 November 2026.*
