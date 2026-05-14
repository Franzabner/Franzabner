# Public Surface

Status: `scaffolded` locally after Phase 1 patch  
Repository: `Franzabner`  
Purpose: public surface inventory and exclusion rule set

## What This Profile May Show

| Public-safe surface | Allowed content |
| --- | --- |
| Identity | Francisco Abner Rivera as Founder of YOSO-YAi and Systems Architect building intelligent infrastructure from power to autonomy. |
| Navigation | Links to reviewed public-safe proof-control material, especially `franzabner-proof-stack`. |
| Status | Approved status labels: `planned`, `scaffolded`, `published`, `released`, `paused`, `deprecated`, and `private/not-public`. |
| Architecture | The approved 17-repo architecture as an architecture plan, with two Phase 2 public scaffold repos and remaining umbrella repos held at `planned` until created and reviewed. |
| Boundaries | Public/private/sealed rules for personal, company, product, Foundation, client, Forgejo, GitHub, Hugging Face, data/model, hardware, and agentic workflow material. |
| Public-safe artifacts | Synthetic examples, reviewed screenshots, reviewed templates, assumptions, validation notes, and proof matrices when approved for public use. |

## What This Profile Must Not Show

| Restricted material | Rule |
| --- | --- |
| Sealed YOSO-YAi LLC source | Do not expose source, product implementation, sealed IP, private architecture, private workflows, or unreleased product details. |
| Production hardware/CAD/electrical material | Do not expose production CAD, KiCad source, BOMs, Gerbers, pin maps, firmware, exact dimensions, manufacturing packages, production rack topology, or certification posture. |
| Private infrastructure | Do not expose topology, hostnames, ports, credentials, endpoints, private logs, private runbooks, Forgejo internals, Tailscale details, or operational dashboards. |
| Customer or client material | Do not expose customer data, client source, client workflows, client outcomes, customer infrastructure, or ownership-confusing app claims. |
| Foundation private material | Do not expose donor data, student data, volunteer data, Foundation-private operations, private governance records, or unapproved Foundation outcomes. |
| Model/data material | Do not expose private corpora, weights, adapters, training logs, eval results, endpoints, private prompts, or unreleased model/dataset/Space artifacts. |
| Unsupported claims | Do not claim live products, deployments, revenue, certification, released models, released datasets, Hugging Face Spaces, benchmarks, eval results, physical validation, or autonomous production agents without reviewed evidence. |

## External Surface Rules

| Surface | Public role | Phase 1 rule |
| --- | --- | --- |
| GitHub profile README | Public navigation and proof surface. | May route to reviewed public scaffold repos; do not change pins or profile metadata without separate approval. |
| GitHub repositories | Public mirror, deployment source, portfolio surface, or open-source surface depending on classification. | Do not treat GitHub as canonical private or sealed source; scaffolded repos are not released artifacts. |
| Forgejo | Canonical private source where private or sealed source applies. | Do not publish Forgejo internals or private topology. |
| Hugging Face | Model/dataset/Space release surface only. | Do not change metadata or imply a release without reviewed artifacts. |
| YOSO-YAi LLC surfaces | Company voice and product/source authority where approved. | Do not use Foundation voice to sell company work. |
| YOSOR | Product of YOSO-YAi LLC. | Do not describe YOSOR as independent or Foundation-owned. |
| 218 Network Foundation | Co-equal, legally and operationally distinct Foundation. | Do not use Foundation work as personal or company marketing proof. |
| Client-owned applications | Client or company delivery surfaces with ownership boundaries. | Do not present client apps as Franzabner personal products, YOSOR, or Foundation programs. |

## Publication Gate

Before this profile routes to public scaffold repos as proof surfaces, human review must confirm:

- status language is accurate;
- boundary language is complete;
- no supporting repo was silently upgraded;
- no repo is implied as released, deployed, certified, product-ready, or proof-complete;
- no GitHub metadata or Hugging Face metadata change is bundled into the patch;
- no private, sealed, client, Foundation-private, model-sensitive, or security-sensitive material appears.
