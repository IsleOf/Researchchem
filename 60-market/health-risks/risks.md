---
type: risks
area: area:health-risks
level: L2
updated: 2026-11-08
---
# Consolidated risk register

Up: [[health-risks/index]]

Cross-cutting health risks ranked by **severity × likelihood**. This is a deliberate editorial ranking, not a validated score — it exists so that the register does not read as a flat list in which an injection-site reaction looks equivalent to an abscess.

**Severity (S):** 1 self-limiting · 2 needs clinical attention · 3 hospitalisation / lasting organ effect · 4 life-threatening or permanent · 5 frequently fatal.
**Likelihood (L):** 1 theoretical, no human cases · 2 case reports only · 3 documented repeatedly in case series or poison-centre data · 4 common in the exposed population · 5 near-universal / structural.
**Evidence (E):** **D** demonstrated in humans · **N** non-human (animal/in vitro) · **T** theoretical/mechanistic only.

## Tier 1 — highest priority (S×L ≥ 12)

| Risk node | S | L | S×L | E | Basis |
|---|---|---|---|---|---|
| `risk:no-human-safety-data` / `risk:no-long-term-safety-data` | 4 | 5 | **20** | D | Structural, and near-universal across non-approved compounds: no long-term follow-up, no carcinogenicity, no reprotoxicity, often no human PK, no pharmacovigilance able to detect a delayed signal. Its severity rating is for the *unbounded* harms it conceals. [[health-risks/cancer-and-long-term]] |
| `risk:product-quality` / `risk:unregulated-product-quality` | 4 | 5 | **20** | D | Apr 2026 preprint: **41.6–71.1% quality failure**, **~15% measurable endotoxin**, purity uncorrelated with endotoxin. Routine certificates test identity + HPLC purity only — not sterility, endotoxin, elemental impurities, residual solvent or aggregates. [[health-risks/injection-and-contamination]] · [[grey-market-quality]] |
| `risk:product-mislabelling` | 4 | 4 | **16** | D | TGA: serious reaction to a product **sold as retatrutide** that contained **undeclared semaglutide and no retatrutide**. Bromazolam sold as alprazolam (MMWR Feb 2023). The person does not know which pharmacology they took. |
| `risk:polydrug-depressant-stacking` (see [[polydrug-risk]]) | 5 | 4 | **20** | D | Fentanyl present in **every** medetomidine-containing sample and specimen in the Chicago cluster. Opioid + benzodiazepine + alpha-2 + alcohol is the dominant fatality pattern, and no single antidote covers it. |
| `risk:alpha2-withdrawal-emergency` | 5 | 3 | **15** | D | MMWR Philadelphia: **165 hospitalised**, severe hypertension/tachycardia, **PRES and NSTEMI**, resistant to standard fentanyl/xylazine withdrawal treatment, responded only to dexmedetomidine (hospital-only). Pittsburgh: 23 patients. Undetectable by fentanyl/benzo test strips. [[health-risks/cardiometabolic]] |
| `risk:endotoxin-pyrogenic-reaction` | 3 | 4 | **12** | D | ~15% endotoxin positivity in sampled grey-market peptides (preprint); TGA reports of SIRS and generalised hypersensitivity. Clinically indistinguishable from early sepsis at the bedside. |
| `risk:dosing-error-nonstandard-concentration` | 4 | 3 | **12** | D | FDA 26 Jul 2024: patients drew **5–20× the intended dose** of compounded semaglutide; hospitalisations, acute pancreatitis, gallstones; prolonged observation needed given the ~1-week half-life. Harm mechanism was arithmetic, not toxicology. |
| `risk:hpg-suppression` | 3 | 4 | **12** | D | Negative feedback is the loop working correctly, not a side effect. 2021 systematic review: of 38 ASIH cases with fully known outcomes, **only 4 showed complete reversibility with axis recovery**. Gynaecomastia unlikely to resolve; spermatogenesis months to years; some remain azoospermic. [[health-risks/endocrine-suppression]] |

## Tier 2 — substantial (S×L 6–11)

| Risk node | S | L | S×L | E | Basis |
|---|---|---|---|---|---|
| `risk:soft-tissue-infection-abscess` | 3 | 3 | 9 | D | Repeated non-sterile injection. SSP survey baseline: 2 in 3 lifetime SSTI, 4 in 10 hospitalised for the most recent. Alpha-2 adulterants add a necrotic (not primarily infectious) wound pattern — 2026 scoping review, PMID 42007753. Deep sequelae: endocarditis, osteomyelitis, epidural abscess. |
| `risk:benzodiazepine-withdrawal-seizure` | 5 | 2 | 10 | D(class)/T(analogues) | Benzodiazepine withdrawal is one of only two withdrawal syndromes that routinely kill. Unknown potency and abrupt supply interruption make designer-benzodiazepine dependence worse than the user expects. MMWR Feb 2023 documented status epilepticus in the bromazolam cluster — but **the authors did not attribute it to bromazolam intoxication or withdrawal**. Class-inferred for these analogues. |
| `risk:cardiomyopathy-myocardial-injury` (stimulants) | 4 | 2 | 8 | D | Groenewegen 2024: 222 poison-centre single-agent cardiotoxicity cases (63% 3-MMC); literature cases included cardiac arrest n=28, STEMI n=2, cardiomyopathy n=1, myocarditis n=2. Severe end over-represented by reporting bias; no incidence estimate exists. |
| `risk:rhabdomyolysis-aki` | 4 | 2 | 8 | D(class)/T(cathinone-specific) | Hyperthermia + agitation + rigidity → myoglobinuric AKI and hyperkalaemia. Very well established for sympathomimetics as a class; **no cathinone-specific rhabdomyolysis case series was located** — class inference, marked as such. |
| `risk:insulin-resistance` | 3 | 3 | 9 | D | Nass 2008 (2-year RCT): fasting glucose **+0.3 mmol/L, P = 0.015**, insulin sensitivity decreased. Chapman 1996: glucose 5.4→6.8 mmol/L at 4 weeks. Mechanistically intrinsic to GH-axis stimulation, so expected rather than idiosyncratic. |
| `risk:immunogenicity` / `risk:immunogenicity-impurities` | 3 | 2 | 6 | D(regulatory)/T(grey-market) | FDA's 2021 peptide guidance states peptide-related impurities and aggregates **may pose immunogenicity risks**. Grey-market handling (unvalidated lyophilisation, unrefrigerated shipping, freeze-thaw, agitation, wrong diluent) promotes aggregation; endotoxin acts as adjuvant. **No published case of cross-neutralisation of an endogenous hormone from a grey-market peptide was located.** |
| `risk:anaphylaxis-hypersensitivity` | 5 | 2 | 10 | D | TGA reports of **severe allergic reactions and generalised hypersensitivity** with unapproved peptides. Injected peptide + impurities + aggregates are credible immunogens. Biphasic reactions mean apparent recovery is not recovery. [[health-risks/emergency-recognition]] |
| `risk:hypoglycaemia` | 4 | 2 | 8 | D | Follows directly from the two documented failures: 5–20× dosing errors, and undeclared incretin in a product sold as something else. Neuroglycopenia is **routinely mistaken for intoxication** in this population. Prolonged because of the long half-life. |
| `risk:cortisol-hpa-disruption` | 3 | 2 | 6 | D | Nass 2008: **cortisol +47 nmol/L, P = 0.020** — the secretagogue class is not axis-selective. Separately, any undeclared glucocorticoid creates adrenal-crisis risk on interruption. |
| `risk:hyperpigmentation` | 2 | 4 | 8 | D | MC1R agonism is the intended mechanism. 38% rate recorded for PT-141 in this repo; approved bremelanotide label notes focal hyperpigmentation **was not confirmed to resolve in all patients** after discontinuation — potentially permanent. |
| `risk:transient-hypertension` (melanocortins) | 2 | 3 | 6 | D | Bremelanotide label: **+6 mmHg systolic / +3 mmHg diastolic**, peaking 2–4 h, resolving usually within 12 h; increases with closer dosing; **not recommended at high cardiovascular risk**. Unknown-quantity grey-market material removes every control the label relies on. |
| `risk:naion-ocular` | 4 | 1–2 | 6 | D | EMA PRAC Jun 2025: NAION a **"very rare"** side effect of semaglutide, **up to 1 in 10,000**, ~**two-fold** relative risk in T2D. Label change only — not a withdrawal or contraindication. **Novo Nordisk disputes causality.** Permanent vision loss, no established treatment, hence high severity on low likelihood. |
| `risk:hepatotoxicity` | 3 | 2 | 6 | D(signal)/T(eugeroics) | TGA/CMO flagged abnormal LFTs and acute liver injury with unapproved peptides. **Counter-evidence for the eugeroics:** DILIN (899 DILI cases) and ALFSG (1,198 ALF cases) attributed **none** to modafinil/armodafinil. Adrafinil-specific hepatic claims appear **only on consumer/supplement sites** — unverified. |

## Tier 3 — real but lower-ranked, or theoretical

| Risk node | S | L | S×L | E | Basis |
|---|---|---|---|---|---|
| `risk:cardiovascular-ae` (GLP-1 heart rate) | 2 | 4 | 8 | D | Class-wide, pharmacologically expected: semaglutide ~+3.4 bpm, liraglutide ~+2.4 bpm, orforglipron 36 mg +9.29, tirzepatide 5 mg +0.52 vs placebo. Modest on average, sustained day and night with long-acting agents. Matters most in undiagnosed cardiac disease with no prescriber. |
| `risk:nausea` | 2 | 4 | 8 | D | Most common adverse reaction for melanocortin agonists (≥4% per label) and dose-limiting for incretins. Clinically relevant here mainly as a route to dehydration and pre-renal AKI at supratherapeutic exposure. |
| `risk:water-retention` | 2 | 3 | 6 | D | Dose-limiting GH-axis effect; sodium retention / extracellular volume expansion. Matters where cardiac or renal reserve is borderline. |
| `risk:injection-site-reaction` | 1 | 4 | 4 | D | Reported across every injectable in this area. Low severity — but it is also the presentation that gets dismissed when it is actually early cellulitis or abscess. |
| `risk:particulate-solvent-contamination` | 3 | 1–2 | 4 | T | ICH Q3C residual solvents and USP <787>/<788> particulate limits apply to licensed products and not to RUO material; grey-market certificates rarely report residual solvent or counter-ion at all. **No case series quantifying harm located** — a testing gap, not a finding. |
| `risk:heavy-metals-elemental-impurities` | 3 | 1 | 3 | T | ICH Q3D does not apply to RUO material and routine certificates would not detect elemental impurities. **No peer-reviewed dataset quantifying heavy metals in grey-market peptide vials was located.** Vendor-adjacent claims (e.g. "73% of 1,200+ samples") are unverified — do not reuse. |
| `risk:igf1-cancer-theoretical` | 4 | 1 | 4 | D(link 1) → T(conclusion) | **Demonstrated:** endogenous IGF-1 top vs bottom quintile — breast **OR 1.28** (17 prospective studies, confined to ER-positive, OR 1.38) and prostate **OR 1.29** (17 prospective studies). **Demonstrated:** secretagogues raise IGF-1. **Theoretical:** that this translates into cancer risk — no cohort, trial or registry of cancer incidence in this exposed population exists. [[health-risks/cancer-and-long-term]] |
| `risk:theoretical-proliferative` (angiogenic peptides) | 4 | 1 | 4 | N→T | BPC-157 angiogenesis via VEGFR2–PI3K–Akt–eNOS and Src–caveolin-1–eNOS is **animal-model** evidence. The anti-VEGF oncology drug class demonstrates the pathway matters in human tumours. But reviewed sources state **no evidence shows BPC-157 causing cancer in humans or initiating tumours in animals**; the concern is **promotion of existing disease**, and no carcinogenicity or cohort study exists. |
| `risk:theoretical-oncogenic` (telomerase/ALT) | 4 | 1 | 4 | N | Al-Dulaimi 2025: Epitalon lengthened telomeres in **breast-cancer cell lines via ALT** — in vitro, independent of the originating group. Telomerase reactivation is a cancer hallmark. **But** some rodent data show *fewer* tumours (Anisimov 2003), so the in vivo direction is unknown. Two opposing non-human bodies of evidence. |
| `risk:genomic-uncertainty` | 3 | 1 | 3 | N | Prostamax raised **sister-chromatid exchange**, a classic genotoxic-stress marker, presented by its developers as rejuvenation. The contested part is what the finding *means*, not its size. |
| `risk:trial-death-unestablished-causality` | 5 | 1 | 5 | D | CJC-1295 phase 2 halted in 2006 after a participant died; **causality never established**, and the trial result was never published. Listed because an unexplained death plus non-publication is itself an information risk. |
| `risk:unpublished-trial-data` | 2 | 3 | 6 | D | The larger ipamorelin trial (NCT01280344, n=320) was never published. Systematically biases the apparent safety record toward the favourable. |
| `risk:delayed-diagnosis` | 3 | 4 | 12 | D | **Under-weighted everywhere.** Routine immunoassays detect none of these compounds; most of the case literature relies on self-reported exposure; several syndromes mimic each other. The medetomidine clusters were missed because nobody knew to look. Arguably belongs in Tier 1. |

## How the ranking should be read

1. **The top of the register is not pharmacology.** The four highest-scoring entries are all about the *product and the information environment* — quality, mislabelling, missing safety data, polydrug exposure — not about any molecule's receptor effects. That is the central finding of this area.
2. **Severity and likelihood pull in opposite directions for the cancer risks.** They are high-severity, likelihood-1 entries. They belong in the register and they do not belong at the top of it. Marketing understates them; critics overstate them.
3. **Withdrawal appears twice as a Tier 1–2 emergency** (alpha-2 and benzodiazepine). Stopping is not automatically the safe direction.
4. **Several entries are class inferences, labelled as such** (rhabdomyolysis for cathinones, withdrawal seizures for designer benzodiazepines, thyroid interaction for GH agents). They are included because the mechanism is solid; they are labelled because the specific evidence is not.
5. `risk:delayed-diagnosis` scores 12 and is ranked in Tier 3 only because it is a meta-risk. In practice it multiplies every other row.

Open and contested items: [[health-risks/open-questions]]
