# Researchchem – second brain

A harm-reduction knowledge graph that tracks emerging novel psychoactive substances and grey-market peptides (most made in China). It covers four areas: weight loss, wakefulness, stimulants and depressants.

**Start here:** [00-index/MOC.md](00-index/MOC.md) · latest digest: [weekly/2026-W45.md](weekly/2026-W45.md)

## Layout
| Folder | What |
|---|---|
| `00-index/` | Map of Content (entry point) |
| `10-categories/` | One hub note per category, ranked table |
| `20-compounds/` | Atomic note per compound: status, risks, links, sources |
| `30-concepts/` | Cross-cutting ideas (quality, drug checking, polydrug risk) |
| `40-sources/` | Bibliography |
| `50-peptide-branches/` | Multi-level peptide branches (L0 family → L3 studies), per-branch graph.json |
| `weekly/` | Dated digests |
| `graph/graph.json` | Node/edge export for GraphRAG |

Notes use YAML front-matter and `[[wikilinks]]`, so the folder opens as an Obsidian vault (graph view works out of the box).

## Scoring
- **trend_signal 1–5:** how strongly 2026 monitoring and market reports flag it.
- **risk 1–5:** severity of known harms (5 = overdose deaths reported).

## Scope
Information only: status, risks and sources. No dosing, sourcing or vendor info. If you or someone you know uses: test your drugs, don't use alone, carry naloxone.
