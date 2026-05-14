# Boundaries

Status: `scaffolded` locally after Phase 1 patch  
Repository: `Franzabner`  
Purpose: personal/company/Foundation/product/client/release boundary control

## Boundary Register

| Boundary area | Required rule |
| --- | --- |
| Personal surface | `Franzabner` is Francisco Abner Rivera's personal public engineering proof surface and navigation layer. |
| Company surface | YOSO-YAi LLC is the company entity responsible for company source, products, customer obligations, sealed IP, and company public surfaces. |
| Product surface | YOSOR is a product of YOSO-YAi LLC, not a separate legal entity and not a Foundation product. |
| Foundation surface | 218 Network Foundation is co-equal but legally and operationally distinct. Foundation work must not be used as personal or company marketing proof. |
| Client/app surface | Client-owned applications, including the client-owned certificate app, must not be presented as Franzabner personal products, YOSOR, or Foundation programs. |
| Forgejo | Forgejo is canonical private source where private or sealed source applies. |
| GitHub | GitHub is a public mirror, deployment source, portfolio surface, or open-source surface depending on repository classification; it is not canonical for private or sealed source. |
| Hugging Face | Hugging Face is a model/dataset/Space release surface only and not the canonical sealed model-development home. |
| Sealed material | Production CAD, KiCad source, BOMs, Gerbers, pin maps, firmware, topology, credentials, private corpora, weights, customer data, Foundation-private data, and operational logs remain non-public unless explicitly reviewed and transformed into public-safe derivatives. |
| AI build lane | Codex and other agents may assist execution, but they are not architectural authority and do not approve publication or claims. |

## Public / Private / Sealed Definitions

| Class | Meaning for this profile |
| --- | --- |
| Public | Content that can be published without exposing secrets, sealed IP, donor-sensitive information, customer-sensitive information, private model/data material, unreleased operational plans, or security-sensitive infrastructure details. |
| Private | Source or artifacts shared only inside the authorized operating group. Private material must not be linked as public proof. |
| Sealed | Source or artifacts requiring explicit human authorization before any excerpt, mirror, release, generated output, screenshot, or derivative summary leaves the sealed source. |
| Mixed | Material with both public and non-public parts. Public use requires path, branch, release, or derivative controls that make the boundary explicit. |

## Entity Discipline

| Entity or surface | Allowed role | Forbidden collapse |
| --- | --- | --- |
| Francisco Abner Rivera | Personal public engineering identity and proof navigation. | Do not make this profile the company, Foundation, client, or release authority. |
| YOSO-YAi LLC | Company entity and source/product authority where approved. | Do not describe it as Foundation parent, Foundation authority, charity program, or civic legitimacy source. |
| YOSOR | YOSO-YAi LLC product surface. | Do not describe it as a separate legal entity or Foundation product. |
| 218 Network Foundation | Independent Foundation with civic mission, governance transparency, donor expectations, and public trust obligations. | Do not use it as a CSR project, company marketing arm, YOSO-YAi sub-brand, product line, or personal proof shortcut. |
| Client-owned apps | Client/company delivery surfaces with explicit ownership boundaries. | Do not present them as Franzabner personal products, YOSOR, or Foundation programs. |

## Artifact Boundary

Examples, screenshots, diagrams, model cards, dataset cards, reports, logs, generated outputs, and demos inherit the boundary of their inputs until human review marks them public-safe.

No local or public file in this profile authorizes publication of:

- production CAD, KiCad source, BOMs, Gerbers, pin maps, firmware, rack topology, private facility layout, manufacturing package, or certified design material;
- credentials, tokens, hostnames, ports, endpoints, mesh details, private logs, private runbooks, internal workflows, or Forgejo internals;
- private corpora, weights, adapters, prompts, training logs, eval results, private model endpoints, or unreleased Hugging Face material;
- customer data, client source, client outcomes, donor data, student data, volunteer data, Foundation-private operations, or sealed YOSO-YAi source.

## Phase 1 Hold

The 15 umbrella repositories remain `planned` in Phase 1. Supporting narrow repositories keep their existing status until separate human review. This profile patch does not push, publish, release, pin, rename, archive, transfer, or change GitHub or Hugging Face metadata.
