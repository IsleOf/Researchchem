# Market & health overview branch schema

Each research area lives in `60-market/<area>/`.

| Level | File | Content |
|---|---|---|
| L0 | `index.md` | Area summary, what changed in 2025–26, links to L1 notes |
| L1 | `<topic>.md` | One note per topic in the area |
| L2 | `timeline.md` | Dated events/advances, newest first |
| L2 | `risks.md` | Health risks specific to this area |
| L3 | `open-questions.md` | Gaps, contested claims, what to watch |
| — | `graph.json` | Nodes + edges for this area |

## Node IDs (shared IDs merge across all branches)
- area: `area:<slug>` · topic: `topic:<slug>` · compound: `<slug>` (reuse existing: `nitazenes`, `medetomidine`, `retatrutide`, `alpha-pihp`, `bromazolam`, `btmps`, `xylazine`, `flmodafinil`, `3-mmc`, `tirzepatide`, `semaglutide`…)
- risk: `risk:<name>` · effect: `effect:<name>` · target: `target:<name>`
- org/system: `org:<slug>` e.g. `org:euda`, `org:unodc`, `org:fda`, `org:dea`, `org:wada`
- event: `event:<slug>` (attrs: date, what) · source: `src:<short>` (attr url)

## Edge relations
`in_area`, `related_to`, `causes_risk`, `monitored_by`, `regulated_by`, `preceded_by`, `cited_by`, `supports`, `refutes`

Rules: no dosing protocols, no synthesis routes or precursor info, no vendors/sourcing/marketplaces. Monitoring, forensic, regulatory and clinical literature only. Real citations. Mark contested or weak claims explicitly. Date everything.
