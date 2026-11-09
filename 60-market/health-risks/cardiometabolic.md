---
type: note
area: area:health-risks
level: L1
updated: 2026-11-08
---
# Cardiometabolic harms

Up: [[health-risks/index]]

Heart-rate, blood-pressure, myocardial and glucose effects cut across every class in this knowledge base. Two distinct patterns: **acute sympathomimetic injury** (stimulants) and **chronic drift in cardiometabolic parameters** (incretins, GH secretagogues, melanocortins). The second pattern is the one that is invisible without monitoring, and grey-market use is by definition unmonitored.

See also: [[health-risks/organ-specific]] · [[polydrug-risk]]

## Stimulant cardiomyopathy and myocardial injury

**Mechanism.** Synthetic cathinones raise synaptic dopamine, serotonin and noradrenaline by reuptake inhibition and/or transporter-mediated release. The cardiac consequences follow from sustained catecholamine excess: tachycardia, hypertension, increased myocardial oxygen demand against coronary vasoconstriction, arrhythmogenesis, and — with repeated or prolonged exposure — catecholamine-mediated myocyte injury and cardiomyopathy.

**The best single dataset.** Groenewegen et al., *Cardiovascular Toxicology* 2024 — two case reports plus a retrospective review of Dutch Poisons Information Centre records (2012–2022) plus a scoping review ([PMID 38411851](https://pubmed.ncbi.nlm.nih.gov/38411851/) · [PMC10937789](https://pmc.ncbi.nlm.nih.gov/articles/PMC10937789) · [Springer](https://link.springer.com/article/10.1007/s12012-024-09832-x)):
- **222 single-agent cardiotoxicity cases** in the poison-centre dataset, **63% involving 3-MMC**.
- Literature review: 30 articles, 40 cases. Reported events included **cardiac arrest (n=28)**, ventricular tachycardia (n=4), **STEMI (n=2)**, NSTEMI (n=2), cardiomyopathy (n=1), myocarditis (n=2).
- Common presenting features: tachycardia, hypertension, palpitations, chest pain.
- **Important limitation stated by the authors:** exposure was largely self-reported without analytical confirmation; urine screening used immunoassays, with chromatographic confirmation only in the two index case reports. Co-ingestions of cocaine, amphetamine-type stimulants, heroin or GHB were excluded, so this is a filtered, not a representative, sample.

**Interpretation.** Cardiac arrest dominating the literature-review case mix is a reporting-bias artefact — severe cases get written up. The poison-centre arm (n=222) is the better denominator-adjacent figure. What is well supported: cathinone cardiotoxicity is real, ranges from palpitations to arrest, and clusters around 3-MMC in European data. What is not supported: any dose-response or incidence estimate.

Relevant compounds in this repo: [[3-mmc]] · [[2-mmc]] · [[alpha-php]] · [[alpha-pihp]]

Note the compounding factors specific to grey-market stimulants: unknown potency per unit mass (so an unintended 10× exposure is a routine event), no analytical confirmation of identity, and frequent co-exposure that the case literature deliberately excludes but real use does not.

## GLP-1 / incretin heart-rate elevation

Heart-rate increase is a **consistent, class-wide, pharmacologically expected** effect of GLP-1 receptor agonism, not an adverse signal unique to grey-market copies. It matters here because it is the parameter most likely to be clinically relevant in someone with undiagnosed cardiac disease and no prescriber.

| Population | Finding | Source |
|---|---|---|
| Non-diabetic, overweight/obese (pairwise + network meta-analysis of RCTs) | vs placebo: liraglutide ~**+2.4 bpm**; semaglutide ~**+3.4 bpm** (95% CI 1.69–5.01, imprecise); orforglipron 36 mg largest at **MD +9.29** (95% CI 4.45–13.86); tirzepatide 5 mg smallest at **MD +0.52** (95% CI −2.71 to 3.78) | [PMC12918571](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12918571/) |
| Type 2 diabetes, tirzepatide (meta-analysis, 8 articles) | **MD +1.82 bpm** (95% CI 0.75–2.89) vs combined control; dose-dependent, largest at 15 mg | reported in the same literature; combined-control design is a limitation |
| Type 2 diabetes, exenatide/liraglutide (earlier class meta-analysis) | **+1.86 bpm** (95% CI 0.85–2.87) vs placebo, with significant between-study heterogeneity | [PMC3563145](https://pmc.ncbi.nlm.nih.gov/articles/PMC3563145) |

- Magnitude is modest — low single-digit bpm on average — but **long-acting agents produce a more pronounced and sustained increase across day and night**, so the 24-hour burden exceeds what a clinic measurement suggests.
- **No meta-analysis directly comparing semaglutide with tirzepatide on heart rate was located.** The cross-table comparison above mixes populations and designs; do not read it as a ranking.
- Investigational agents in this repo ([[retatrutide]], [[survodutide]], [[cagrilintide]], [[mazdutide]]) have not been characterised for heart rate outside sponsor trials, and grey-market copies have no characterisation at all.
- Interacting consideration: this effect sits on top of any stimulant use. Co-use of a GLP-1 agonist and a cathinone is an additive chronotropic load that neither literature addresses. **Mark as inference.**

Separate but related: the 2024 FDA alert documented **acute pancreatitis and gallstones** among adverse events after 5–20× compounded semaglutide overdoses, plus dehydration and syncope — see [[health-risks/injection-and-contamination]].

## GH-secretagogue-driven insulin resistance and glucose rise

The clearest controlled human evidence in this whole area, and it is unambiguously unfavourable.

**Nass et al. 2008** — 2-year randomised, double-blind trial of oral MK-677 (ibutamoren) 25 mg daily in healthy older adults ([PMID 18981485](https://pubmed.ncbi.nlm.nih.gov/18981485/) · [PMC2757071](https://pmc.ncbi.nlm.nih.gov/articles/PMC2757071/)):
- Enhanced pulsatile GH secretion and significantly increased fat-free mass over 12 months.
- **Fasting glucose rose by a mean 0.3 mmol/L (5 mg/dL), P = 0.015, and insulin sensitivity decreased.**
- **Cortisol rose 47 nmol/L (95% CI 28–71), P = 0.020** — i.e. the agent is not axis-selective.
- The authors stated the trial's duration and sample size were insufficient to evaluate functional endpoints.

**Chapman et al. 1996** — short-term MK-677 in healthy elderly: **fasting glucose rose from 5.4 ± 0.3 to 6.8 ± 0.4 mmol/L at 4 weeks (P < 0.01 vs baseline)** ([PMID 8954023](https://pubmed.ncbi.nlm.nih.gov/8954023/)). A larger short-term effect than the 2-year trial, which is consistent with partial adaptation but is a single small study.

**Mechanism.** GH is a counter-regulatory hormone: it raises hepatic glucose output and induces lipolysis, and the resulting free fatty acid flux impairs peripheral insulin-mediated glucose disposal. A sustained (non-pulsatile-equivalent) GH/IGF-1 elevation therefore pushes toward insulin resistance by design. This is the mechanistic basis for `risk:insulin-resistance`, and it applies to the ghrelin-mimetic secretagogues and GHRH analogues as a class — [[ipamorelin]] · [[cjc-1295]] — not only to MK-677. The existing finding in this repo that MK-677 "added lean mass, did not cut visceral fat, and worsened insulin sensitivity" is consistent with the primary data above.

**Contested / unverified:**
- The Adunsky et al. 2011 hip-fracture trial of MK-677 (*Arch Gerontol Geriatr*, [PubMed 21067829](https://www.pubmed.gov/21067829/)) was **terminated early for a congestive heart failure safety signal** per its abstract. The per-arm CHF counts quoted on peptide wikis (4/62 vs 1/61) are **not confirmed**; do not cite them until checked against the full text.
- One ageing-research wiki reports fasting glucose and insulin unchanged with worsened oral glucose tolerance in a separate study. This conflicts with the trials above; treat as unreliable.

Also in the GH axis: **fluid retention** (`risk:water-retention`) is a dose-limiting GH-axis effect and is mechanistically the same sodium-retention/extracellular-volume effect that makes GH axis stimulation a concern in anyone with borderline cardiac or renal reserve.

## Medetomidine: bradycardia and hypotension (and the withdrawal reversal)

[[medetomidine]] is a veterinary alpha-2 adrenergic agonist now adulterating the illicit opioid supply. Its cardiovascular profile is the mirror image of the stimulant picture and is **not reversed by naloxone**.

**Acute intoxication — Chicago, May 2024** (MMWR 74(15):258–265, 1 May 2025, doi 10.15585/mmwr.mm7415a1 · [PMC12045484](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12045484/) · [CDC](https://www.cdc.gov/mmwr/volumes/74/wr/mm7415a1.htm)):
- **12 confirmed, 26 probable, 140 suspected** medetomidine-involved overdoses across three West Side Chicago hospitals, 11–17 May 2024 — the largest reported cluster of confirmed medetomidine-involved overdoses.
- Among confirmed/probable cases: **hypertension 36 (95%), bradycardia 33 (87%)**, altered mental status 32 (84%), pinpoint pupils 32 (84%).
- **Most patients with confirmed cases had no or only partial response to naloxone.** A poison-centre summary gives 11 of 12 confirmed patients with little or no naloxone response.
- **Fentanyl was identified in every drug sample and blood specimen containing medetomidine** — so this is always a polydrug presentation.
- Heart rates as low as **32 bpm** are reported in the alpha-2 clinical literature, and atropine was frequently required in this cluster.
- **Discrepancy flagged:** a secondary source states bradycardia was "refractory to naloxone in 92% of cases". That figure was **not confirmed in the MMWR text**; do not reuse it.

**Withdrawal — the more dangerous syndrome.** Two MMWR reports, both 1 May 2025:
- **Philadelphia**, Sep 2024 – Jan 2025: **165 patients** across three health systems hospitalised for fentanyl withdrawal complicated by **profound autonomic dysfunction — severe hypertension and tachycardia**. Described as life-threatening and requiring substantial escalation of care beyond typical opioid or xylazine withdrawal. Reported complications: **posterior reversible encephalopathy syndrome (PRES)** and **non-ST-elevation myocardial infarction**. The syndrome was resistant to medications previously effective for fentanyl and xylazine withdrawal but responded to dexmedetomidine — a hospital-only drug. MMWR 74(15):266–268 ([PMC12045483](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12045483/) · [CDC](https://www.cdc.gov/mmwr/volumes/74/wr/mm7415a2.htm)). **Note: CDC has published an erratum for this report — check it before quoting specific numbers.** A Philadelphia health alert cites 91% ICU admission and 24% intubation from this series; **those percentages were not verified against the MMWR text**.
- **Pittsburgh**, Oct 2024 – Mar 2025: **23 adult patients** who used illegally manufactured opioids, analogous severe withdrawal. MMWR 74(15):269–271 ([CDC](https://www.cdc.gov/mmwr/volumes/74/wr/mm7415a3.htm)). A secondary summary giving "ten cases" is wrong; **use 23**.

**Withdrawal signs per CDC HAN:** tachycardia >100 bpm, severe hypertension, fluctuating alertness, tremor, chest pain, intractable nausea and vomiting; onset **within hours of last use, peaking 18–36 hours later** ([CDC HAN 00527](https://www.cdc.gov/han/php/notices/han00527.html)). Later jurisdictional advisories add end-organ damage ([Philadelphia](https://hip.phila.gov/health-alerts/responding-to-overdose-and-withdrawal-involving-medetomidine) · [NYC HAN Advisory 2, 2026](https://www.nyc.gov/assets/doh/downloads/pdf/han/advisory/2026/han-advisory-2-medetomidine-withdrawal.pdf)).

**The public-health point:** a person can present with a hypertensive, tachycardic, PRES-complicated emergency **because they stopped using**, from an adulterant they never chose and that no fentanyl test strip detects ([[drug-checking]]). This is a reason to seek care, not to manage at home.

## Melanocortin agonists and blood pressure

Melanocortin receptor agonism produces a **transient blood-pressure rise with a reciprocal heart-rate fall** after each dose. The approved reference product gives the quantified version.

**Bremelanotide (Vyleesi) prescribing information** ([label](https://www.drugs.com/pro/vyleesi-injection.html) · [label text](https://medlibrary.org/lib/rx/meds/vyleesi/page/4/)):
- Transiently increases blood pressure and reduces heart rate after each dose.
- Maximal mean increases in trials: **+6 mmHg systolic, +3 mmHg diastolic**, peaking **2–4 hours post-dose**, usually returning to baseline **within 12 hours**.
- Effects increase if doses are taken closer together — the label limits to one dose per 24 hours.
- Cardiovascular risk should be assessed before and during treatment and blood pressure well controlled; **not recommended in patients at high risk for cardiovascular disease**.
- Nausea is the most common adverse reaction; nausea, flushing, injection-site reactions, headache and vomiting each occurred in ≥4% (`risk:nausea`, `risk:flushing`, `risk:injection-site-reaction`). A secondary site's "~40% nausea" figure exceeds the label rates — **treat with caution**.

Applied to the grey market: [[pt-141]] is this same molecule sold without the label, the 24-hour interval, the cardiovascular screening or a known concentration. Melanotan II is a **non-selective** melanocortin agonist, so it hits MC1R/MC3R/MC4R together — the same reason it causes pigmentation also means it carries the pressor effect (`risk:transient-hypertension`). The 6/3 mmHg figure is for a controlled dose of a characterised product; it is not transferable to an unknown quantity of unknown material.

## Sources
- [Groenewegen et al. 2024, cathinone cardiotoxicity (PMID 38411851)](https://pubmed.ncbi.nlm.nih.gov/38411851/)
- [GLP-1 heart rate network meta-analysis (PMC12918571)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12918571/)
- [Earlier GLP-1 class heart-rate meta-analysis (PMC3563145)](https://pmc.ncbi.nlm.nih.gov/articles/PMC3563145)
- [Nass et al. 2008, 2-year MK-677 trial (PMID 18981485)](https://pubmed.ncbi.nlm.nih.gov/18981485/)
- [Chapman et al. 1996, MK-677 in healthy elderly (PMID 8954023)](https://pubmed.ncbi.nlm.nih.gov/8954023/)
- [MMWR 74(15):258–265 — medetomidine overdoses, Chicago](https://www.cdc.gov/mmwr/volumes/74/wr/mm7415a1.htm)
- [MMWR 74(15):266–268 — suspected medetomidine withdrawal, Philadelphia](https://www.cdc.gov/mmwr/volumes/74/wr/mm7415a2.htm)
- [MMWR 74(15):269–271 — Pittsburgh series](https://www.cdc.gov/mmwr/volumes/74/wr/mm7415a3.htm)
- [CDC HAN 00527 — medetomidine](https://www.cdc.gov/han/php/notices/han00527.html)
- [Vyleesi (bremelanotide) prescribing information](https://www.drugs.com/pro/vyleesi-injection.html)
