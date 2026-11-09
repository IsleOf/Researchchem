---
type: runbook
updated: 2026-11-09
---
# Weekly monitoring sweep — runbook

Run by the scheduled task `researchchem-weekly-sweep`. An agent executes this and commits the result.

## Scope
Monitoring sources only — see [[source-registry]]. **Do not** check vendor sites, marketplaces, seller channels, B2B chemical portals or any source that sells. Those are excluded by design; see the scope note at the bottom.

## Tier 1 — fast feeds (check every run)
| Source | What to extract |
|---|---|
| NIST RaDAR newsletter | Any "first detected" compound; note region and sample count |
| Drogart (SI) weekly | New cannabinoids and cathinones; new scaffolds especially |
| Toronto / Ontario Drug Checking | New opioid adulterants; non-opioid additions (cf. nefopam) |
| WEDINOS (Wales) | New entries; % samples not matching purchase intent |
| CFSRE public alerts | Any new alert since last run |
| High Alert (NZ), The Know (AU) | Regional alerts |

## Tier 2 — forward indicators (check every run)
| Source | What to extract |
|---|---|
| Federal Register — ECDD review notices | New substances added to the review slate → update [[ecdd-watchlist]] |
| WHO ECDD meeting agendas | Pre-review / critical review lists |
| National emergency scheduling notices (US DEA, UK ACMD/MDA, NL, SG, NZ) | **Strongest single predictor** of international review: a Party scheduling nationally is itself an ECDD trigger |

## Tier 3 — periodic (check monthly)
UNODC EWA · EUDA EWS updates · NDEWS · Euro-DEN Plus · NFLIS · regional EWS (Colombia, Uruguay, Central Asia)

## Output per run
Append to `weekly/<ISO-week>.md`:
1. **New first-time detections** — substance, class, jurisdiction, source, date
2. **Spread signals** — any substance newly flagged by a *second* independent jurisdiction (this is the pattern that preceded the nitazene wave)
3. **Regulatory moves** — national scheduling, ECDD additions
4. **Watchlist delta** — changes to [[ecdd-watchlist]] likelihood scores
5. **Nothing-found** — state it plainly; a quiet week is a real result, not a failed run

## Rules for the executing agent
- Real citations only; never invent a PMID, DOI or URL. Mark anything unconfirmed as **unverified**.
- No dosing, no synthesis routes, no precursor chemicals, no vendors or sourcing.
- Single-lab figures are not national prevalence — label them.
- Record the lag: note the data period, not just the publication date.
- If a source is unreachable, say so rather than substituting a weaker one.

## Why vendor channels are excluded
This repo exists to reduce harm from substances already in circulation. A feed of which new compounds are purchasable, and from where, serves acquisition rather than harm reduction, and would make the repo a sourcing tool. Detection data answers the question that matters for risk — what is actually in the supply — without that.

## Legitimate social-signal layer (not implemented)
Aggregate public-discussion monitoring is a published academic method: NDEWS and others use keyword counters over public drug-discussion forums, and cross-correlation analyses report that discussion of novel compounds can precede official forensic reports by **1–2 years**. ⚠️ Claim taken from the user's pasted search output; **unverified** — needs the primary paper. If implemented, it must count *substance-name frequency in aggregate* only. It must not collect vendors, sellers, prices, availability or sourcing.
