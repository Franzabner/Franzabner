# Proof Index

Status: `scaffolded` locally after Phase 1 patch  
Repository: `Franzabner`  
Purpose: profile-level reading order and proof routing

## Reading Order

| Step | Destination | Purpose |
| ---: | --- | --- |
| 1 | `README.md` | Establish identity, technical lanes, status vocabulary, and boundary posture. |
| 2 | `BOUNDARIES.md` | Confirm personal, company, product, Foundation, client, Forgejo, GitHub, Hugging Face, private, and sealed boundaries. |
| 3 | `STATUS.md` | Confirm current status and next human review gate. |
| 4 | `PUBLIC_SURFACE.md` | Confirm what this profile may show and what remains private/not-public. |
| 5 | `franzabner-proof-stack` | Route claims to repo, artifact, status, boundary, validation method, evidence state, review state, and next action. |

## Proof-Control Rule

The profile may summarize public-safe engineering scope, but the proof-control repository owns the claim matrix. A public-facing claim should not be strengthened unless `franzabner-proof-stack` contains an evidence row, status label, boundary class, validation method, and human review state.

## Approved Architecture Route

| Final repo | Route from profile | Current status |
| --- | --- | --- |
| `Franzabner` | Current profile navigation layer. | `scaffolded`; public control surface, not release authority. |
| `franzabner-proof-stack` | Master proof index and claim-control spine. | `scaffolded`; public proof-control surface, not release authority. |
| [`modular-infrastructure-studies`](https://github.com/Franzabner/modular-infrastructure-studies) | Public scaffold route for modular infrastructure serviceability studies. | `scaffolded`; public scaffold only, not released. |
| [`cad-mechanical-design-lab`](https://github.com/Franzabner/cad-mechanical-design-lab) | Public scaffold route for synthetic CAD and mechanical serviceability studies. | `scaffolded`; public scaffold only, not released. |
| [`electrical-controls-architecture`](https://github.com/Franzabner/electrical-controls-architecture) | Public scaffold route for synthetic electrical/control narratives, sensor/actuator patterns, and validation review. | `scaffolded`; public scaffold only, not released. |
| [`embedded-hardware-lab`](https://github.com/Franzabner/embedded-hardware-lab) | Public scaffold route for synthetic embedded hardware, MCU/management-bus, firmware-boundary, and validation studies. | `scaffolded`; public scaffold only, not released. |
| [`engineering-simulation-lab`](https://github.com/Franzabner/engineering-simulation-lab) | Public scaffold route for synthetic engineering simulation assumptions, model boundaries, validation reports, and proof limits. | `scaffolded`; public scaffold only, not released. |
| [`data-model-infrastructure`](https://github.com/Franzabner/data-model-infrastructure) | Public scaffold route for synthetic data/model infrastructure, source capture, metadata, vector indexing, dataset versioning, fine-tuning boundaries, and release cards. | `scaffolded`; public scaffold only, not released. |
| `infrastructure-energy-studies` | Future umbrella route for energy conversion, storage, control, and validation studies. | `planned` |
| `civic-infrastructure-production-systems` | Future umbrella route for public-safe civic production studies without speaking as the Foundation. | `planned` |
| `engineering-standards-and-validation` | Future umbrella route for safety, commissioning, testing, and standards-aware validation. | `planned` |
| `engineering-security-boundary` | Future umbrella route for secrets, visibility, data, model, client, Foundation, and agent-permission boundaries. | `planned` |
| `engineering-deliverables-template` | Future umbrella route for professional engineering templates and handoff packages. | `planned` |
| `application-development-systems` | Future umbrella route for app architecture and product/client ownership boundaries. | `planned` |
| `immersive-access-systems` | Future umbrella route for spatial dashboards, HMI, digital twins, and controlled access studies. | `planned` |
| `automated-engineering-systems` | Future umbrella route for memory, Forgejo, n8n, provenance, and operator-dashboard workflow proof. | `planned` |
| `agentic-engineering-workforce` | Future umbrella route for Codex-style execution, review gates, tool boundaries, and human-controlled agents. | `planned` |

## Supporting Repo Rule

Existing narrow repositories are source context and supporting proof only. Phase 1 does not patch, archive, transfer, rename, publish, or upgrade supporting repos. Their future routing belongs in the proof stack and later umbrella execution plans.

## Link Gate

Before a repo link is promoted from supporting context to public proof, confirm:

- status uses `planned`, `scaffolded`, `published`, `released`, `paused`, `deprecated`, or `private/not-public`;
- artifact type is named;
- public/private/sealed boundary is explicit;
- validation method is stated;
- human review state is recorded;
- no released model, dataset, Space, deployment, certification, client, revenue, product-readiness, Foundation outcome, or autonomous production-agent claim is implied without evidence.
