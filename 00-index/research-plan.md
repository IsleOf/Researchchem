---
type: research-plan
updated: 2026-11-09
horizon: 2026-11 → 2027-02
---
# Research plan

Ordered by **what unblocks the most downstream work**, not by topic interest. Each phase states its bottleneck, concrete tasks, and a success test.

---
## Phase 0 — Unblock primary sources `[blocking everything]`

**The problem.** Almost every citation in this repo was taken from search-result extracts, not read in full. PubMed, PMC, CDC, fda.gov, EUDA and CFSRE were all unreachable from the sessions that built it. That is the single biggest quality constraint: it is why 48 citations are marked unverified and why figures like per-arm discontinuation rates could not be pinned down.

**Tasks**
1. Verify whether the `Researchchem literature` environment (created mid-build, allows PubMed/PMC/clinicaltrials.gov/FDA/EMA/NEJM/Lancet/JAMA/doi.org) actually resolves those hosts now. The proxy had not picked it up when it was created.
2. If it does not, request the specific hosts: `pubmed.ncbi.nlm.nih.gov`, `pmc.ncbi.nlm.nih.gov`, `www.cdc.gov`, `www.fda.gov`, `www.euda.europa.eu`, `www.cfsre.org`, `www.federalregister.gov`, `www.who.int`.
3. Re-run the highest-value verifications first (see Phase 1).

**Success test:** a session can fetch a PubMed abstract and an EUDA PDF directly.
**Until then:** every new claim keeps its explicit unverified mark. Do not quietly upgrade confidence.

---
## Phase 1 — Clear the 40 high-priority gaps `[credibility]`

High priority = **a reader could be misled**. Source: [[gaps]].

**Tasks, in order**
1. **Figures that travel without their caveats.** Verify per-arm numbers where only the headline is sourced: Adunsky 2011 MK-677 CHF counts; the cathinone reduced-EF percentages (E-MJM 2024, n=294); TRIUMPH discontinuation rates.
2. **Regulatory facts with a wrong or missing document number.** The DEA 7-OH/MGM temporary scheduling order (its own FR number); flubromazolam and etizolam scheduling status; the WADA 2026 list text for hydrafinil.
3. **The WHO 49th ECDD meeting** (19–22 Oct 2026, reportedly critical reviews of five slate substances). If real, several watchlist entries have already moved past the comment stage and [[ecdd-watchlist]] is stale.
4. **The MMWR 74(15) medetomidine erratum** — content and correct issue number unresolved.
5. **Contested claims** (18 logged): resolve or mark as genuinely disputed with both sides cited.

**Success test:** high-priority count in [[gaps]] below 10, and every remaining one states *why* it cannot be closed.

---
## Phase 2 — Close structural coverage holes `[completeness]`

### 2a. Unbuilt peptide branches
Kisspeptin-10, HCG and oxytocin were never written. Scope tightly to avoid the dose-dense material that stalled the first attempt: **receptor pharmacology, approval status, harms, and the HPG-suppression concept** — no administration regimens. HCG's FDA/AMA weight-loss ineffectiveness finding is the highest-value single item.

### 2b. Classes with no coverage at all
Audit found these entirely absent:
- **Ketamine and dissociatives** — UNODC flags ketamine supply and use as *globally expanding*; an EU EMPACT situation report exists (Mar 2026). Arguably the largest single omission. Add methoxetamine, 2-FDCK, deschloroketamine.
- **Tryptamines** — [[psychedelics]] currently covers phenethylamines only. 4-AcO-DMT, 4-HO-MET, DMT, 5-MeO-DMT, and the synthetic tryptamine NPS group.
- **Nitrous oxide** — major EU prevalence; B12/neurological harm is well documented and distinctive.
- **GHB/GBL and GABAergic sedatives** — the depressants area notes them as a negative finding, which is itself unverified.
- **Synthetic cannabinoids as a first-class category** — currently only inside market-structure; the "kush" story alone warrants it.

### 2c. Regional thinness
Source registry has no national source for Africa; South/Southeast Asia, Latin America, Nordics are thin. India produced **no 2026 NPS data at all** despite appearing in EU data as a precursor and bulk-cathinone source. Target: Trimbos (NL), SICAD (PT), national EWS for Brazil, Mexico, South Africa, Japan, Korea, India.

**Success test:** every substance class in the UNODC EWA taxonomy has at least a stub note; ≥3 non-US/EU national sources added.

---
## Phase 3 — The medicines-in-new-formats thesis `[novel, highest value]`

**The observation.** [[etomidate]] broke the model the rest of this repo is built on. It is not a designer analogue — it is a **licensed medicine in a new delivery format**. No clandestine chemistry, no precursor chain, no novel structure. Early-warning infrastructure is built to detect *new molecules*; it is poorly pointed at *old molecules in new packaging*.

**The hypothesis:** this is a distinct and growing pathway, and it is systematically under-detected.

**Candidate cases already visible in this repo**
| Substance | Origin | Format |
|---|---|---|
| Etomidate | Hospital anaesthetic | Vapes ("space oil"/"K-pods"), tablets sold as oxycodone |
| Nefopam | Non-opioid analgesic | Adulterant in fentanyl supply |
| Medetomidine / xylazine | Veterinary sedatives | Adulterants |
| Tianeptine | Antidepressant (EU/Asia) | "Gas-station heroin" retail |
| Gabapentinoids | Prescription | Diverted, overdose-contributory |
| 7-OH | Isolated plant constituent | Vape shops, gas stations — bypassed research-chemical channels entirely |

**Tasks**
1. Systematic scan: which licensed or veterinary medicines have appeared in illicit formats 2020–2026? Include promethazine, quetiapine, loperamide, dextromethorphan, phenibut.
2. Characterise the **detection penalty**: how much longer does a known medicine take to be flagged, versus a novel structure? Hypothesis — longer, because labs already have the standard but nobody is looking for it in that matrix.
3. Test the **format** axis separately from the molecule axis: vapes, counterfeit pharmaceutical tablets, gas-station retail. Format innovation reaches new populations faster than a new molecule can, because it bypasses the "who seeks this drug" filter.
4. Write it up as a concept note and, if it holds, as the repo's main analytical contribution.

**Success test:** a defensible answer to "is this pathway growing, and is it under-detected?" with cases and dates.

---
## Phase 4 — Sharpen forecasting `[capability]`

1. **Score the W46 forecast** when its window closes on 9 Dec. Eight predictions with stated falsifiers; record hits and misses honestly in the note. A forecast method that is never scored is astrology.
2. **Quantify the detection lag.** For 10–15 substances, measure: first community/drug-checking detection → first forensic publication → first national control → international review. This converts "3–9 months" from folklore into a measured distribution, and makes every future forecast calibrated.
3. **Resolve the social-signal question.** The pasted claim that public discussion precedes forensic reports by 1–2 years is either the best leading indicator available or an artefact. Find the primary paper (NDEWS-adjacent literature). If the method is real, specify an implementation that counts **aggregate substance-name frequency only** — no vendors, prices, availability or sourcing. See the scope note in [[sweep]].
4. **Build the lag-adjusted view:** for each class, state what the monitoring record would look like *today* if a substitution began on date X. Makes absence-of-evidence legible.

**Success test:** a measured lag distribution, and a scored forecast.

---
## Phase 5 — Long-latency harms `[the repo's blind spot]`

Every source this repo uses detects **acute** harm: overdoses, poisonings, hospital presentations. Nothing in the monitoring infrastructure catches a harm arriving a decade later with no obvious cause — which is exactly the shape unregulated long-term use would produce.

**Candidates:** 5-HT2B agonism and valvular heart disease (2C-T series, and the fen-phen precedent); IGF-1 elevation and cancer epidemiology; chronic copper load from injected GHK-Cu; adrenal suppression from repeated etomidate; telomerase/ALT findings for Epitalon.

**Task:** write a concept note on *why these are structurally invisible*, and what study design would be needed. This is the most honest thing the repo can say about long-term risk, and it currently says nothing.

---
## Execution notes
- Phase 0 gates Phases 1 and 2's quality; Phases 3–5 can run in parallel.
- Use cheap models for mechanical work (registry building, gap cataloguing, reformatting); reserve stronger models for the first research pass on a new area and for citation verification, where the earlier cheap passes produced more unverified marks.
- Standing rules for every phase: no dosing, no synthesis routes, no precursor chemistry, no vendors or sourcing, real citations only, mark unverified explicitly.

Related: [[gaps]] · [[sweep]] · [[source-registry]] · [[2026-W46-forecast]] · [[ecdd-watchlist]]
