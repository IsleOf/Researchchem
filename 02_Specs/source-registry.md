---
type: source-registry
updated: 2026-11-09
---
# Source registry: where to look for drug-market and harm signals

Monitoring sources only. No vendors, marketplaces, sellers, or forums are listed. Each row marks whether its URL was seen in a search result this session (**verified**) or is carried over from the existing fast-sources note without a check (**unverified**). "Lag" is the typical delay between the event in the market and public reporting.

Columns: **ID** · **Name** · **Organisation** · **Region** · **URL** · **Cadence** · **Covers** · **Data type** · **Access** · **Lag** · **Status**

## How to use this registry

| Question | Check first | Then |
|---|---|---|
| What is in the supply **now**? | Drug-checking alert feeds: High Alert (NZ), The Know (AU), Toronto/Ontario, WEDINOS, Drogart, NIST RaDAR | Local checking services (checkit!, Saferparty, CanTEST, BCCSU dashboard) |
| Is substance X **spreading**? | Multi-jurisdiction flags in the fast services, then UNODC EWA / Tox-Portal for toxicology spread | NFLIS-Drug (US seizures), EUDA annual report for EU trends |
| What is **about to be controlled**? | WHO ECDD (critical reviews), Federal Register ECDD notices | UNODC EWA, CND scheduling, national emergency-scheduling notices |
| What are the **harms**? | Poison-centre / sentinel networks (Euro-DEN Plus), coroner and hospital alerts (Simcoe, Interior Health) | Wastewater (SCORE, NWDMP) for population-level use |
| Is a **new country** showing up? | UNODC EWA regional pilots, Global SMART Update | National EWS (Colombia, Uruguay, Panama, Central Asia) |

Rule of thumb: the fast services lag about **4–8 weeks** because naming a compound needs a reference standard. Annual reports lag **18–24 months**. Use the fast tier for "what is coming", the annual tier for "what has been established".

---

## (a) FAST: weekly, monthly, or event-based

| ID | Name | Organisation | Region | URL | Cadence | Covers | Data type | Access | Lag | Status |
|---|---|---|---|---|---|---|---|---|---|---|
| F-01 | NIST RaDAR newsletter | NIST (US) | US | https://content.govdelivery.com/accounts/USNIST/bulletins/416d5ef (bulletin; newsletter index not checked) | Monthly | First-time detections, new NPS (e.g. 9 new compounds Aug 2026) | Forensic lab | Email / web bulletin | ~4–8 wks | verified (bulletin); carried-over claims unverified |
| F-02 | Drogart | Drogart (Slovenia) | EU | not in this session's results | Weekly | New cannabinoids incl. THC-based semi-synthetic oximes (week 32 2026) | Community drug checking | Web | ~4–8 wks | unverified |
| F-03 | Toronto Drug Checking / Ontario | Toronto drug checking programme | Canada | not in this session's results | Weekly–monthly | Opioid adulterants, nefopam, ethylbromazolam | Community drug checking | Web | ~4–8 wks | unverified |
| F-04 | WEDINOS | WEDINOS (Wales) | UK | not in this session's results | Rolling + annual | Purchase-intent samples; orphine flags | Community drug checking | Web | ~4–8 wks | unverified |
| F-05 | CFSRE NPS Discovery / public alerts | Center for Forensic Science Research and Education | US / global | https://www.cfsre.org/nps-discovery | Ad hoc alerts | Novel psychoactive substances; DEA-relevant scheduling evidence | Forensic lab (open access) | Web | ~2–6 wks | verified |
| F-06 | checkit! | checkit! / Suchthilfe Wien | Austria | https://checkit.wien | Continuous service; annual report | Event and pharmacy drug checking; 2025: 368 event samples, 680 pharmacy samples | Community drug checking | Web / PDF annual reports | ~4–8 wks (service); 12+ mo (report) | verified |
| F-07 | Saferparty / DIZ Zurich | Drug Information Centre (DIZ) Zurich / Saferparty | Switzerland | https://en.saferparty.ch | Mobile lab ~monthly at events; substance alerts ad hoc | Party drugs, cocaine, cannabis (incl. cannabis checking since 2020) | Community drug checking | Web / alert database | ~2–6 wks | verified |
| F-08 | The Know (Prompt Response Network) | The Know, Australia | Australia | https://theknow.org.au | Ad hoc alerts | Republished Australian public drug alerts across states/territories | Alert aggregator | Web | days–weeks | verified |
| F-09 | CanTEST | Directions Health Services, Pill Testing Australia, CAHMA; funded by ACT Health | Australia (ACT) | https://www.cahma.org.au/services/cantest/ (monthly snapshots; latest seen Mar 2024) and cantest.com.au (not fetched) | Alerts ad hoc (20 community notices); snapshots monthly | Nitazenes (3 detections), novel substances (4 new globally) | Community drug checking | Web / PDF | ~2–6 wks | verified (CAHMA page); cantest.com.au unverified |
| F-10 | High Alert / KnowYourStuffNZ | DIANZ (KnowYourStuffNZ is a partner) | New Zealand | https://www.highalert.org.nz; https://knowyourstuff.nz | Ad hoc alerts; seasonal clinics | 3,943 samples at 165 events in 2024–25; eutylone in "MDMA"; Alpha-D2PV; nitazenes | Community drug checking + alerts | Web / email signup | days–weeks | verified |
| F-11 | BCCSU drug checking / drug-testing dashboard | BC Centre on Substance Use | Canada (BC) | https://www.bccsu.ca | Dashboard continuous; news releases ad hoc | Fentanyl and adulterant prevalence; BCCSU reports ~55% of BC drug testing | Community drug checking + dashboard | Web | ~2–6 wks | verified (org page); dashboard URL unverified |
| F-12 | Victoria pill testing notifications | Victorian Government (Premier's office releases) | Australia (VIC) | https://www.premier.vic.gov.au | Ad hoc press releases | 8 drug notifications at Pride Street Party since Aug 2025 (vs ~4/yr before testing) | Drug checking + alerts | PDF press releases | days–weeks | verified |
| F-13 | NSW festival drug checking | NSW Health (Alcohol and Other Drugs Programs) | Australia (NSW) | https://www.health.nsw.gov.au/aod/programs/Pages/drug-checking-services.aspx | Per festival season; permanent from Oct 2026 (up to 15 festivals/yr) | Festival samples; 12-month trial (>1,500 samples) | Drug checking | Web / news release | per event | verified |
| F-14 | Simcoe Muskoka medetomidine alert | Simcoe Muskoka District Health Unit | Canada (ON) | https://www.simcoemuskokahealth.org/docs/default-source/jfy-health-care-professionals/jfy-healthfax/20260122-medetomidine-ph-alert-final.pdf | Ad hoc | Medetomidine in local supply (Jan 2026) | Public-health alert (hospital/poison data) | PDF | days | verified (carried-over URL) |
| F-15 | Interior Health drug alert | Interior Health (BC) | Canada (BC) | https://www.interiorhealth.ca/sites/default/files/2026-02/interior-region-drug-alert-feb-11-2026.pdf | Ad hoc | Regional overdose/adulterant alerts (Feb 2026) | Public-health alert | PDF | days | verified (carried-over URL) |
| F-16 | Prevent Overdose RI Substance Spotlight | Prevent Overdose RI | US (RI) | https://preventoverdoseri.org/wp-content/uploads/2026/07/Substance-Spotlight-Foldable-Zine_2026_English.pdf | Periodic (zine) | Local substance spotlight | Community reporting | PDF | weeks–months | verified (carried-over URL) |
| F-17 | Federal Register ECDD notices | US Federal Register / DEA | US (forward) | https://www.federalregister.gov (ECDD-specific notices not found in this session) | Ad hoc | US notice of substances under review | Regulatory | Web | forward-looking | unverified |

## (b) PERIODIC: quarterly, biannual, or per-season

| ID | Name | Organisation | Region | URL | Cadence | Covers | Data type | Access | Lag | Status |
|---|---|---|---|---|---|---|---|---|---|---|
| P-01 | National Wastewater Drug Monitoring Program (NWDMP) | Australian Criminal Intelligence Commission (ACIC), with UQ and Adelaide | Australia | https://www.acic.gov.au/publications/national-wastewater-drug-monitoring-program-reports | Reports 22–25 span Dec 2023–Oct 2025 (roughly 2–3 per year; exact schedule unverified) | Methamphetamine, cocaine, heroin, MDMA; Report 25: 26.8 t consumed, 21% rise | Wastewater | PDF | ~2–4 months | verified |
| P-02 | UNODC Global SMART Update | UNODC Global SMART Programme | Global | https://www.unodc.org/LSS (SMART pages) | Biannual | NPS markets, ketamine, synthetic drugs | Forensic/market reporting | PDF | ~6 mo | verified (SMART update PDF in results); URL unverified as current |
| P-03 | UNODC Current NPS Threats | UNODC Laboratory and Scientific Section | Global | https://www.unodc.org/tox/ | Biannual | Seizure data combined with biological-fluid detections | Forensic lab + toxicology | PDF (public); dashboard restricted | ~6 mo | verified |
| P-04 | UNODC Tox-Portal / Tox-Dashboard | UNODC with IATF | Global | https://www.unodc.org/LSS/Page/NPS/tox | Continuous (registered users) | NPS toxicology: post-mortem, clinical, casework | Toxicology | Registered users only | ~months | verified (note: being merged into a new EWA portal) |
| P-05 | Euro-DEN Plus (via EUDA) | EUDA with sentinel centres | EU + Western Balkans / S. Neighbourhood | https://www.euda.europa.eu/publications/european-drug-report/2026/new-psychoactive-substances_en | Annual contribution to EDR; technical reports | 32 centres in 22 countries; 7.6% of ED presentations involved an NPS (2014–19) | Hospital / poison-centre | PDF | ~12–24 mo | verified (EDR chapter URL carried over) |
| P-06 | NDEWS drug-checking report | National Drug Early Warning System (US) | US | https://ndews.org/wordpress/files/2026/05/202604_NDEWS_SSD_Report_Overview_EP.pdf | Periodic | Drug-checking and surveillance summary (Apr 2026) | Early warning / drug checking | PDF | weeks–months | verified (carried-over URL) |
| P-07 | Euro SCORE / EUDA wastewater release | SCORE network and EUDA | Europe (115 cities, 25 countries) | https://www.euda.europa.eu/drugs-library/common-protocol-action-monitoring-illicit-drugs-wastewater_en (protocol); release mirrored at https://www.drogy-info.cz | Annual campaign (March release) | MDMA down, ketamine and cocaine up (spring 2025 sampling) | Wastewater | Web / press | ~9–12 mo | verified |
| P-08 | NSW festival evaluation | Independent evaluator for NSW Health | Australia (NSW) | https://www.health.nsw.gov.au/news/Pages/20260902_00.aspx (government release) | Once per trial | Fewer urgent hospital/ICU presentations (associated, not causal) | Evaluation | Web | ~6–12 mo | verified (release); full report not located |
| P-09 | Aegis NPS Insights dashboard | Aegis Sciences Corporation (commercial forensic lab) | US | https://www.aegislabs.com/npsinsights/ | Continuous; updated with menu changes | NPS detections in clinical urine/toxicology | Forensic / clinical toxicology | Web dashboard (was down for maintenance Aug 2026) | ~weeks | verified; commercial lab, not a retail source |
| P-10 | Echele Cabeza (Colombia) | Échele Cabeza | Latin America (Colombia) | https://www.echelecabeza.com | Continuous; annual data | 2,868 results in 2021 across Bogotá and festivals in 8 cities | Community drug checking | Web / PDF | months | verified (org URL from results) |
| P-11 | COPOLAD / CICAD early-warning programme | COPOLAD (EU–LatAm cooperation) with OAS-CICAD | Latin America | https://copolad.eu | Periodic workshops and reports | Early-warning systems in Argentina, Chile, Uruguay, Colombia | Policy / EWS | PDF | months | verified |
| P-12 | Uruguay National Drugs Board early-warning system | Junta Nacional de Drogas (Uruguay) | Latin America | https://www.gub.uy/junta-nacional-drogas | Periodic | 160 drug presentations in database | Early warning | Web | months | verified (news pages seen) |
| P-13 | CARICC / UNODC Central Asia EWS pilot | CARICC with UNODC | Central Asia | https://www.caricc.org | Pilot 2025–2027; workshops periodic | Synthetic drugs and NPS in Central Asia; national platform draft (Mar 2026) | Early warning | Web / PDF | months | verified |

## (c) ANNUAL / REFERENCE

| ID | Name | Organisation | Region | URL | Cadence | Covers | Data type | Access | Lag | Status |
|---|---|---|---|---|---|---|---|---|---|---|
| A-01 | DIMS annual report | Trimbos Institute (NL) | Netherlands | https://www.trimbos.nl/?p=295111 (2025 report); https://www.trimbos.nl/kennisbank/tri-41-014-annual-report-dims-2024/ | Annual (+ infographic May 2026) | 32–33 testing sites; ecstasy and cocaine dominate samples | Community drug checking | PDF / web | 12+ mo | verified |
| A-02 | checkit! annual report | checkit! (Vienna) | Austria | https://checkit.wien/en/drug-checking-annual-report-2025/ | Annual | 2025: 1,343 conversations; 368 + 680 samples | Community drug checking | PDF / web | ~9–12 mo | verified |
| A-03 | Energy Control technical report | Asociacion Bienestar y Desarrollo (Barcelona) | Spain | https://energycontrol.org/recursos/articulos-cientificos/ | Annual (Informe Tecnico 2025); >5,000 samples/yr | Ecstasy, cocaine, tusi; ~17,000 samples since 2017 | Community drug checking | PDF / web | ~12 mo | verified (page); report PDF unverified |
| A-04 | TEDI / C-EHRN European drug checking trends | EMCDDA-funded TEDI network | Europe | https://www.drugsandalcohol.ie/42851/1/2024_C-EHRN-TEDI_Monitoring_European-Drug-Checking-Trends-2018-2024.pdf | Periodic multi-year (2023, 2024 editions) | Pooled data 2018–2024 incl. Italy, Spain, UK, Zurich | Community drug checking (pooled) | PDF | ~12–24 mo | verified |
| A-05 | NFLIS-Drug | US DEA Diversion Control | US | https://www.nflis.deadiversion.usdoj.gov/nflisdata/docs/NFLISDrug_2021AnnualReport.pdf (2021 report; 2022 report referenced) | Annual + midyear | Seized drug cases from federal/state/local labs (712,130 cases in 2021) | Forensic lab (seizures) | PDF / public dataset | ~12–18 mo | verified |
| A-06 | UNODC Early Warning Advisory (EWA) | UNODC Global SMART | Global | https://www.unodc.org/LSS/Page/About | Continuous portal; NPS counts updated periodically | 1,200+ NPS from 141 countries (2023 figure; newer count not found); public part open, database restricted | Forensic / toxicology / seizure | Web (public), registered (database) | months | verified |
| A-07 | European Drug Report (EUDA) | EUDA | EU | https://www.euda.europa.eu/publications/european-drug-report/2026/new-psychoactive-substances_en | Annual (EDR 2026 published 9 Jun 2026) | NPS, synthetic stimulants, wastewater, drug checking | Mixed (regulatory, lab, hospital) | PDF / web | 18–24 mo | verified |
| A-08 | Harm Reduction Australia / Pill Testing Australia policy brief | HRA and PTA | Australia | https://www.harmreductionaustralia.org.au/hra-pill-testing-policy-brief/ | Ad hoc | Pill-testing policy and national harmonisation proposal (2026) | Policy / advocacy | PDF | n/a | verified; advocacy source, not data |
| A-09 | Synthetic-opioid threat assessment (Baltics) | EUDA | Baltic states | https://www.drugsandalcohol.ie/43620/1/EUDA_threat-assessment-report-on-synthetic-opioids-in-the-baltic-countries.pdf | Ad hoc | Limited drug-checking availability in Baltics | Threat assessment | PDF | 12–24 mo | verified |
| A-10 | UNODC NPS leaflet (reference) | UNODC | Global | https://unodc.org/documents/scientific/NPS-Leaflet_WEB_2020.pdf | Reference (2018, 2020 editions) | Background on NPS EWA | Reference | PDF | n/a | verified (reference only) |
| A-11 | Canberra / ACT pill testing (CAHMA) | CAHMA | Australia (ACT) | https://www.cahma.org.au/services/cantest/ | Monthly snapshots (latest found Mar 2024) | CanTEST summaries | Drug checking | Web | months | verified |
| A-12 | Scotland / sedative (clonazolam) warning | BBC news / Police Scotland | UK | https://bbcinsight.pages.dev/news/articles/cjdj70d7lvdo | Ad hoc | Clonazolam warning | News (secondary) | Web | days | carried-over; secondary, unverified |
| A-13 | Substance preprint: grey-market peptides | preprints.org | Global | https://www.preprints.org/manuscript/202604.1748 | Ad hoc | Purity and endotoxin of grey-market peptides (Apr 2026) | Preprint lab study | Web | months | carried-over; preprint, unverified |
| A-14 | Frontiers Pharmacology alpha-PiHP study | Frontiers in Pharmacology | Global | https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2025.1728824/full | Ad hoc | Human pharmacology of alpha-PiHP | Peer-reviewed study | Web | months | carried-over |

## (d) FORWARD-LOOKING: regulatory pipelines

| ID | Name | Organisation | Region | URL | Cadence | Covers | Data type | Access | Lag | Status |
|---|---|---|---|---|---|---|---|---|---|---|
| R-01 | WHO Expert Committee on Drug Dependence (ECDD) | WHO | Global | https://www.who.int/groups/ecdd/forty-ninth-ecdd-documents | Annual (**49th meeting HELD 19–22 Oct 2026** — confirmed on the WHO page 2026-11-09) | Critical reviews: cychlorphine (N-propionitrile chlorphine), desalkylgidazepam, ethylbromazolam, etomethazene, spirochlorphine; preliminary: etomidate, medetomidine. **Outcomes not yet published** — the page's "Meeting outcomes" headings ("WHO DG correspondence to UNSG", "49th ECDD summary assessments") are unlinked placeholders. **Re-check weekly.** Review PDFs are on `cdn.who.int`, which this session's network blocks | Regulatory | Web / draft reports to participants | forward (6–18 mo to CND vote) | verified |
| R-02 | WHO 49th ECDD provisional agenda (circular letter C.L.31.2026) | WHO | Global | https://cdn.who.int/media/docs/default-source/controlled-substances/49th-ecdd/49th-ecdd-provisional-agenda.pdf | Per meeting | Agenda and member-state notice (9 Jul 2026) | Regulatory | PDF | forward | verified (agenda PDF URL in results) |
| R-03 | UN CND scheduling decisions | UN Commission on Narcotic Drugs | Global | https://www.unodc.org/LSS/Announcement/Details/25b1a3ae-5a95-4bdf-b758-748ce856be68 | Annual (March) | Final scheduling under the conventions | Regulatory | Web | forward / final | verified (UNODC announcement) |
| R-04 | Federal Register ECDD / DEA temporary scheduling | US DEA / FR | US | https://www.federalregister.gov | Ad hoc | US notices, temporary scheduling of NPS | Regulatory | Web | forward | unverified (no ECDD notice found this session) |
| R-05 | Ecuador / Panama national EWS programmes | Ecuador Ministry of Health with EU; Panama SATPA | Latin America | https://www.salud.gob.ec/?p=114840 ; https://ministeriopublico.gob.pa/notas-de-prensa/procurador-participa-en-inauguracion-del-taller-de-experiencias-y-buenas-practicas-internacionales-sobre-sistemas-de-deteccion-de-drogas/ | Ad hoc | National EWS creation (Panama 2026; Ecuador roadmap 2026–27) | Regulatory / policy | Web | forward | verified (news pages) |

---

## Coverage gaps (this session)

- **Thin / not verified:** Africa (no national drug-checking or EWS source found); South and Southeast Asia beyond Central Asia; Nordic countries (no 2026 source found); Alberta (no government drug-checking programme found; Spectrum Drug Testing in Edmonton is the only service noted, URL unverified); France (not searched); Italy (only older studies found); Portugal (SICAD annual reports only; no current checking data found).
- **Not yet searched:** France, Germany, Belgium, Nordic national agencies directly, Japan/Korea/Taiwan, India, Brazil, Mexico, South Africa.
- **Excluded from the carried-over list as not monitoring sources:** the Benzinga/Reuters and GoodRx items (pharma market and news), the Wikipedia analogue list, the German Sport University doping notice (regulatory for sport, not drug-market monitoring) and HSToday (news summary). These are kept in the old `40-sources/sources.md` index but are not registry entries.
- **Unverified URLs:** Drogart, Toronto Drug Checking, WEDINOS, Alberta (Spectrum), CanTEST live site (cantest.com.au), BCCSU dashboard, Energy Control report PDF, Federal Register ECDD notices. Check each before citing.
