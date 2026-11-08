---
type: note
area: area:health-risks
level: L1
updated: 2026-11-08
---
# Endocrine suppression and axis disruption

Up: [[health-risks/index]]

> **Scope note.** This note describes pharmacology and documented clinical consequences. It deliberately contains **no protocols** — no dosing, no cycling, no "recovery", "restart" or post-exposure regimens. Interventions after axis suppression are prescription endocrinology requiring laboratory monitoring and a clinician. Where the literature mentions specific agents used clinically, they are named only to describe what the evidence base is, not how to use them.

## The general principle: negative feedback

Every one of the three major axes — hypothalamic-pituitary-gonadal (HPG), -thyroid (HPT), -adrenal (HPA) — and the GH/IGF-1 axis is a closed loop with negative feedback. The hypothalamus releases a releasing hormone, the pituitary releases a trophic hormone, the peripheral gland releases the end hormone, and the end hormone (or its metabolite) inhibits both the hypothalamus and the pituitary.

Exogenous administration of anything that acts at or downstream of the pituitary therefore has a structurally predictable consequence: **the body reads the exogenous signal as its own output and turns down endogenous production.** Three corollaries follow, and they are the entire basis of this note:

1. **Suppression is not a side effect; it is the loop working correctly.** It does not require a high dose, an impure product, or misuse.
2. **The endogenous gland atrophies under suppression.** Testicular Leydig cell and seminiferous tubule mass, adrenal zona fasciculata mass, and pituitary cell responsiveness all decline with disuse. Reversal is therefore not instantaneous when the exogenous input stops — the hardware has to be rebuilt.
3. **The time constant for recovery is set by the slowest tissue in the chain**, which is usually not the hormone level. Gonadotropins can normalise while spermatogenesis has not.

### Continuous vs pulsatile stimulation: receptor desensitisation

This is the single most important pharmacological concept in the area, because it is why "more signal" can produce *less* effect.

Many hypothalamic and pituitary receptors are **physiologically driven by pulses, not by tonic exposure**. GnRH reaches the pituitary in discrete pulses roughly every 60–120 minutes; GHRH and ghrelin signalling onto somatotrophs is likewise episodic, producing the characteristic nocturnal GH pulse train.

G-protein-coupled receptors exposed to a **continuous** agonist signal undergo the standard desensitisation cascade: phosphorylation by GRKs, β-arrestin recruitment, uncoupling from G protein, internalisation, and (with sustained exposure) downregulation of receptor number. The downstream cell stops responding.

The canonical clinical demonstration is **GnRH agonist pharmacology**: a GnRH *agonist* given continuously produces an initial flare of LH/FSH and sex steroids, then — after roughly 1–3 weeks of continuous receptor occupancy — profound and sustained gonadotropin suppression. That is why continuous GnRH agonism is used therapeutically to *suppress* the gonadal axis in prostate cancer and precocious puberty. The agonist is a suppressant because the stimulation is continuous.

**Direct implications for this knowledge base:**
- Long-acting or albumin-bound analogues convert a pulsatile physiological signal into a continuous one. The repo's existing finding that **"CJC-1295" is two molecules**, where the DAC form binds albumin Cys34 and has a half-life of ~6–8 days ([[cjc-1295/mechanism]]), is exactly this problem: a ~week-long half-life applied to a receptor system built for ~hourly pulses. Whether that produces sustained stimulation or progressive desensitisation in humans is **not established**; the published human data do not answer it.
- The repo's other existing finding — that in the human CJC-1295 study **the IGF-1 rise did not correlate with any GH parameter** (Ionescu 2006, [[cjc-1295/human-evidence]]) — is consistent with the loop not behaving as the marketing model assumes, though it has other possible explanations.
- Ghrelin-mimetic secretagogues ([[ipamorelin]], MK-677) face the same question. The 2-year MK-677 trial maintained an effect on fat-free mass over 12 months, which argues against complete tachyphylaxis of that endpoint ([PMID 18981485](https://pubmed.ncbi.nlm.nih.gov/18981485/)) — but that is one agent, one endpoint, one trial.
- **Mark clearly:** desensitisation is a well-established receptor-level phenomenon and a well-established clinical phenomenon for GnRH. Its extent for the specific grey-market peptides here is **inferred from class pharmacology, not measured**.

## HPG axis suppression

`risk:hpg-suppression`

**Mechanism.** Androgens and their aromatised metabolite oestradiol inhibit hypothalamic GnRH pulse generation and pituitary gonadotroph output. LH falls → Leydig cell testosterone production falls. FSH falls → Sertoli cell support of spermatogenesis fails. Because intratesticular testosterone concentrations required for spermatogenesis are far higher than circulating concentrations, **exogenous androgen can maintain a normal serum testosterone while spermatogenesis collapses** — the person feels unaffected and is infertile.

In the grey-market context the relevant exposures are androgen-adjacent and gonadotropin-adjacent agents: exogenous androgens, SARMs, hCG (an LH analogue, which suppresses endogenous LH by raising testosterone while directly stimulating the Leydig cell), and anything producing sustained oestrogenic or androgenic feedback.

**The clinical evidence on reversibility is weaker and worse than commonly assumed.**

| Study | Design | Finding |
|---|---|---|
| Scoping review, *Endocrine Connections*, Oct 2023 ([PMID 37728476](https://pubmed.ncbi.nlm.nih.gov/37728476/) · [PMC10620455](https://pmc.ncbi.nlm.nih.gov/articles/PMC10620455/)) | Scoping review of physical, psychological and biochemical recovery from anabolic-steroid-induced hypogonadism (ASIH) | Recovery depends on age and degree of exposure. Near-complete testosterone recovery over months; complete gonadotropin recovery expected over 3–6 months. Testicular size and spermatogenesis may take **months to years**. **Gynaecomastia is unlikely to resolve.** Psychological recovery data **insufficient and conflicting**. Authors call for prospective studies. |
| Systematic review, *Andrologia*, 2021 | 179 AAS users identified; 168 with hypogonadism clearly attributable to AAS | **Only 38 had fully known outcomes, and in just 4 was the hypogonadism completely reversible with HPG axis recovery.** Authors concluded full recovery is difficult in most cases. |

**How to read these two together.** They look contradictory and are not. The 2023 scoping review describes the *expected trajectory* in people who do recover; the 2021 systematic review describes *how rarely complete documented recovery is actually demonstrated* in the published case literature (4 of 38 with known outcomes). Both are observational, both are subject to severe selection bias in opposite directions — case reports over-represent non-recovery, while clinic series over-represent people who present and are followed. **There are no robust prospective controlled data on natural recovery.** That is the honest summary.

The reviews note that hCG and SERMs are used clinically in an attempt to accelerate axis recovery; **no controlled trial data establishing how well this works were located**, and this is prescription endocrinology. A 2025 Irish Endocrine Society meta-analysis abstract on gonadal recovery after non-medical AAS use exists but only as an abstract ([abstract](https://www.endocrine-abstracts.org/ea/0115/ea0115p3)) — pooled findings unavailable.

**Fertility implications.**
- Azoospermia or severe oligozoospermia is the expected consequence of sustained gonadotropin suppression, and some individuals **remain azoospermic** after cessation per the review literature.
- The recovery time constant for spermatogenesis is set by the ~74-day spermatogenic cycle plus the time to restore Sertoli/Leydig function — so even an uncomplicated recovery is a multi-month process, and the reviews describe up to years.
- Because serum testosterone recovers faster than spermatogenesis, **a normal testosterone result does not indicate restored fertility.** Semen analysis is the only measure of that.
- No data were located on fertility outcomes in people exposed to grey-market GH secretagogues or Khavinson-type peptides; this is an unstudied question, not a reassuring one.
- Female HPG suppression and the effects of these agents on ovulatory function are **essentially unstudied** in this population.

## Thyroid axis

- **Mechanism of suppression.** Exogenous thyroid hormone (T4 or T3, including unlabelled T3 in "metabolic" grey-market products) suppresses TSH directly. Suppressed TSH with suppressed endogenous output means the thyroid gland is dependent on the exogenous supply; abrupt interruption of an unreliable supply produces hypothyroidism with a lag set by T4's ~7-day half-life.
- **Documented harms of thyroid-hormone excess**, whether from deliberate use or from an adulterated product: atrial fibrillation, accelerated bone loss, muscle wasting, heat intolerance, and in extremis thyroid storm. These are standard endocrinology, not novel findings.
- **GH axis interaction.** GH administration increases peripheral T4→T3 conversion and can unmask central hypothyroidism; this is why thyroid function is monitored in supervised GH therapy. In unsupervised use it is not monitored at all. **Mark as established mechanism, not as a documented grey-market case series.**
- No systematic data on thyroid-hormone contamination of grey-market "metabolic" products were located in this research. The TGA's finding of undeclared semaglutide in a product sold as retatrutide ([[health-risks/injection-and-contamination]]) establishes that undeclared active hormones do occur.

## Cortisol and the HPA axis

- **Non-selectivity of secretagogues.** The 2-year MK-677 trial found **cortisol rose 47 nmol/L (95% CI 28–71), P = 0.020** ([PMID 18981485](https://pubmed.ncbi.nlm.nih.gov/18981485/)). Ghrelin-receptor agonism is not confined to the somatotroph axis; it has ACTH/cortisol and prolactin effects. A product marketed as acting on one axis acts on several.
- **Sustained cortisol elevation** is mechanistically additive with the GH-driven insulin resistance described in [[health-risks/cardiometabolic.md]] — both push glucose up, both promote central adiposity and both impair collagen and bone turnover. The combination is not characterised in any trial.
- **Exogenous glucocorticoid suppression.** Any product containing or adulterated with a glucocorticoid suppresses the HPA axis; the clinically dangerous consequence is **adrenal crisis** on abrupt withdrawal or during intercurrent illness, because the atrophied adrenal cannot mount a stress response. This is the mechanism that makes an unlabelled steroid in an unregulated product a potentially lethal problem rather than a cosmetic one. Adrenal crisis is a medical emergency — see [[health-risks/emergency-recognition]].

## GH / IGF-1 axis consequences

- **What stimulating the axis does.** GH acts partly directly and partly via hepatic IGF-1. IGF-1 in turn exerts negative feedback on GH secretion. Sustained exogenous stimulation therefore raises IGF-1 and suppresses endogenous GH pulsatility — the axis is driven, not augmented.
- **Documented metabolic consequences** (see [[health-risks/cardiometabolic.md]] for the primary data): fasting glucose rise, reduced insulin sensitivity, fluid retention (`risk:water-retention`, `risk:insulin-resistance`).
- **Acromegalic-pattern effects** from sustained GH/IGF-1 excess in the clinical literature: soft-tissue overgrowth, arthropathy, carpal tunnel syndrome, left ventricular hypertrophy, and in acromegaly proper, increased colorectal neoplasia. Whether grey-market secretagogue use reaches concentrations or durations sufficient to produce these is **not established** — it is the reason the concern exists, not evidence that it has occurred.
- **IGF-1 and cancer epidemiology** is handled separately in [[health-risks/cancer-and-long-term]] (`risk:igf1-cancer-theoretical`), because the inferential chain there is long and easy to overstate.
- **The pulsatility question** (above) means it is genuinely unknown whether long-acting GHRH analogues produce physiological-pattern GH exposure or a continuous non-physiological one with different long-term consequences. This is a real gap, not a rhetorical one.

## Cross-cutting

- Suppression is **silent**. There is no symptom that reliably announces a falling LH, a suppressed TSH or an atrophying adrenal. The only way to detect it is laboratory monitoring with a clinician, which grey-market use structurally lacks.
- The product-quality problem compounds the endocrine problem: an undeclared active hormone ([[grey-market-quality]]) means someone can be suppressing an axis they do not know they are touching.
- Anyone who has had sustained exposure to an axis-active agent and has symptoms — fatigue, loss of libido, mood change, inability to conceive, or any acute illness with dizziness/collapse — needs an actual endocrine assessment, not a regimen.

## Sources
- [ASIH recovery scoping review, Endocrine Connections 2023 (PMID 37728476)](https://pubmed.ncbi.nlm.nih.gov/37728476/)
- [ASIH systematic review, Andrologia 2021 (doping.nl record)](https://www.doping.nl/filter/doc:7362/Anabolic%20androgenic%20steroid-induced%20hypogonadism%2C%20a%20reversible%20condition%20in%20male%20individuals%3F%20A%20systematic%20review)
- [Nass et al. 2008, 2-year MK-677 trial — glucose, insulin sensitivity, cortisol (PMID 18981485)](https://pubmed.ncbi.nlm.nih.gov/18981485/)
- [Gonadal recovery after non-medical AAS use — 2025 meta-analysis abstract](https://www.endocrine-abstracts.org/ea/0115/ea0115p3)
- [TGA safety advisory — unapproved peptide products](https://www.tga.gov.au/node/575382)
