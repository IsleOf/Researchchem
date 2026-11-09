# Peptide branch schema (multi-level GraphRAG)

Each compound lives in `50-peptide-branches/<slug>/`.

| Level | File | Content |
|---|---|---|
| L0 | `../<family>.md` | Family hub linking its compounds |
| L1 | `index.md` | Summary, status, evidence tier (1-3), links to L2 notes |
| L2 | `mechanism.md` | Targets/receptors, pathways, half-life (pharmacology, not dosing) |
| L2 | `human-evidence.md` | Each human study: year, n, design, outcome, link |
| L2 | `animal-evidence.md` | Each animal/cell study: species, model, outcome, link |
| L2 | `risks.md` | Side effects, contraindications, interactions, hormone suppression |
| L2 | `regulatory.md` | Approval status by region, WADA, FDA compounding status |
| L3 | `claims-vs-evidence.md` | Marketing claim → what evidence shows → verdict |
| — | `graph.json` | Nodes + edges for this branch |

## Node IDs (shared IDs merge across branches)
- compound: `<slug>`  · family: `family:<name>`
- study: `<slug>:study:<short>` (attrs: year, species, n, design, outcome)
- target: `target:<receptor>` e.g. `target:ghsr`, `target:mc4r`, `target:kiss1r`
- effect: `effect:<name>` e.g. `effect:gh-release`, `effect:anxiolytic`
- risk: `risk:<name>` e.g. `risk:hpg-suppression`, `risk:nausea`
- claim: `<slug>:claim:<short>` · source: `src:<pmid-or-short>` (attr url)

## Edge relations
`member_of`, `targets`, `produces_effect`, `studied_in`, `supports`, `refutes`, `causes_risk`, `cited_by`, `related_to`, `claim_about`

Rules: no dosing protocols, no vendors or sourcing. Real citations only (PubMed/DOI/regulator URLs). Mark weak or uncertain evidence explicitly.
