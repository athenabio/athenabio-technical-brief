# technical-brief
Ovarian Biology Data - Technical Brief 

**Intro**

The AthenaBIO Ovarian Biology Data project is a 5-year, $30M philanthropic fund. It will produce the open reference data, standards and validated measures that are lacking in ovarian research. These foundations will then enable disease modeling and drug development for the era of AI.

AthenaBIO has done a private call for submissions, selected and conducted due diligence on 15 leading ovarian-biology labs across the US and the world. It will maintain a shared knowledge structure, keep the labs on shared protocols and metadata standards, run common reference samples to allow inter-comparability across labs and create an open science infrastructure while also supporting focused research in the field. It will also support research and data collection efforts halted by NIH cuts. Ethical, technical, and administrative aspects of this effort make it a difficult undertaking, but a worthwhile one to advance research not only in female but human health.  

AthenaBIO, a 501(c)(3) (pending), is the centralized infrastructure that runs diligence, coordination, and data harmonization and generates open science data sets focused on ovarian biology. 

We are seeking an anchor donor and a coalition of co-funders. Capital milestone against development stage gates below.

**Why us:** the AthenaDAO alumni team successfully implemented a novel funding mechanism and deployed more than $1.5M into women's health R&D. From 450 projects diligenced over 4 cohorts, it negotiated 4 IP deals, 1 academic spin-out, and has a global academic and industry network focused on the field of ovarian aging and health. Researchers funded have been published, received NIH awards, as well as brokered pharma deals post-funding by the team. 

**The bottleneck**
Ovarian biology has no validated biomarkers, no standardized clinical endpoints and no reference dataset. Private markets will not build these, because no single sponsor can capture their value.
**- No surrogate endpoints.** There is no accepted measure of oocyte quality for ovarian aging. That makes trials slow, costly and hard to justify.
**- Low-quality data and data scarcity. **While we improve capturing large population menopause and transition data, which is going to take a long time, it is still hard to have access to whatever currently exists, which is very poor quality. 
**- No screening infrastructure. **OVARIA, a program we funded, found candidate ovarian-aging targets in UK Biobank data. It must now build its own in vitro screening system, because none exists.
**- Incentive alignment. **Academic institutions and labs are not incentivized to build for open science due to current funding and granting structures. 
Validated biomarkers and shared reference data behave like public goods, given it will be an open science tool. They are expensive to make, useful to everyone, and impossible to monetize alone. Philanthropy is the funder that fits.

**Goal and milestones**

**Genesis - A foundation  multimodal ovarian dataset**
The first project would build a uniformly processed, community-shareable multimodal atlas of the aging human ovary by drawing on an existing biobank of cryopreserved tissue from 161 donor ovaries spanning ages 12-19

_Tissue from organ donors without known gynecological pathology is extremely valuable._

Tissue samples (post-mortem donors) from both cortical and medullary compartments would be run through a single standardized pipeline to minimize batch effects: cryosections would be assigned to adjacent-section assays, including high-resolution single-cell spatial transcriptomics to preserve follicle-, stromal-, and vascular-niche architecture, along with H&E and multiplexed immunostained histology to anchor molecular states to tissue morphology. 

Cells/nNuclei isolated from matched tissue would undergo joint or paired single-cell (scRNA-seq), single-nucleus (snRNA-seq) and chromatin (sn/scATAC-seq) sequencing methodsmodels to link gene expression with chromatin accessibility and gene regulatory programs, and a mass spectrometry-based proteomic arm (bulk or spatially resolved by laser microdissection of cortex versus medulla) would capture the protein-level and extracellular matrix changes, such as fibrosis and inflammaging, that transcripts alone often miss.

Study design would balance age, batch, and compartment across runs, including shared reference controls and bridging samples with rigorous QC, so that modalities can be registered into a common coordinate framework at the donor, sample, and cell level. Because the cohort is dense across the 20s through the 40s, when follicle depletion and the transition toward menopause accelerate, the dataset would capture continuous aging trajectories rather than a few age extremes, with the smaller adolescent and >50 groups serving as important anchors. 

Deposited with open, FAIR-compliant data access, processed objects, and detailed protocols, the resource could serve both hypothesis-driven questions (e.g., which cell states, regulatory programs, or stromal changes track ovarian reserve loss) and the pretraining of a multimodal foundation model of ovarian aging, in which the paired modalities support cross-modal imputation, age-trajectory inference, and biomarker discovery.

With this first clear early Genesis deliverable, we will have a foundation to test the feasibility of the larger vision and to build iteratively. By year 2, we will have the largest single ovarian multimodal dataset available and a first version of a common standard for recording ovarian data.  By year 5, the goal is to deliver open ovarian data sets, annotated with menopausal status and reproductive history following a single standard, validated candidates, biomarkers, standardized endpoints and screenable model systems.

<img width="628" height="294" alt="Screenshot 2026-11-10 at 7 26 44 AM" src="https://github.com/user-attachments/assets/efc62952-b957-4a9f-b807-3b0be1627188" />

Fund roadmap · 3 phases, 2 gates

**Year-5 deliverables:**
- Genesis tissue reference released, with a hidden test set for AI models (ovarian biology benchmark) in use by outside groups
- Menopause-timing loci mapped to the ovarian cell types and regulatory regions where they act
- Tissue-derived blood biomarkers, validated in longitudinal cohorts (e.g., SWAN), with a qualification plan in progress
- Preclinical models scored against human ovarian aging, outcome by outcome, for predictive validity
- Metadata standard adopted by funded labs and mapped to SWAN and UK Biobank standards

**Levers**

Five functioning levers. Labs keep their autonomy and stay where they are; AthenaBIO adds the coordination that no single lab can supply alone. Each lever comes with a commitment we can be held to before the first sample is collected.

| Lever | What the fund does | What it produces | How we hold ourselves to it |
|---|---|---|---|
| Regranting | Funds about 15 ovarian-biology labs for 1–4 years, selected through our diligence pipeline | Omics data, biological samples, targeted moonshot projects | Every funded project states its question, its primary endpoint and its power calculation before money is released |
| Shared standards | Sets common collection, annotation and QC protocols across all labs | Data that can be pooled and compared across sites | One standard applies to every sample, in every lab (from day one) |
| Pooled resources | Negotiates shared access to CROs, biobanks and model systems | Lower cost and faster timelines per lab | Projects that can’t reach power alone, can be combined across labs under the shared protocol (harmonization) |
| Open data release | Hosts and releases harmonized datasets under one open license | AI-ready reference data for any researcher | Data is released on a fixed schedule after QC, and is not held until a paper/report comes out |
| Translation bridge | Flags assets and IP for downstream companies, while keeping data and tools open | Spinouts and licenses that draw private capital | Data and tools stay open, and only discrete inventions are licensed |

**What AI-ready means, without fixing a sample count**
Every dataset will meet six criteria:  standardized (generated under the shared protocols), fully annotated (every sample carries the complete metadata), adequately powered (sample size set or pools samples across labs), longitudinal where possible, linked to clinical outcomes (fertility, menopause timing, disease diagnosis), and open-access. 

Additionally, we will also build an ovarian biology benchmark from Genesis. Data from 30 of the 161 donors will be withheld, and we will define tasks such as predicting spatial gene expression from tissue images, inferring protein levels and estimating ovarian reserve. External teams can submit models, which we run on the withheld donors and score against standard baselines. Because these donors’ data are never released, no model can be trained on them, making the benchmark an honest test of how well AI models capture ovarian biology.

Without this fund, ovarian data will keep being collected lab by lab, on incompatible protocols, and much of it will never be released. The fund's distinct contribution is coordination across labs, validated biomarkers and endpoints, and open release. No single lab or atlas project is set up to deliver those.

| Existing effort | What it covers | What it leaves out that this fund delivers |
|---|---|---|
| Human Cell Atlas reproductive work<br>(Human female reproductive system cell atlas v1; young vs aged ovary atlases: biorxiv.org/content/10.64898/2026.06.10.731198.full.pdf | Over 2M cells across ovary, fallopian tube, uterus, cervix and vagina, integrated with spatial and chromatin data. Ovary-specific aging atlases compare four ovaries from women aged 23-29 with four from aged 49-54<br><br>The metadata accompanying the atlas preprint includes only four donor-related metavariables: ‘Developmental stage’ (fetal = 52 donors, paediatric = 16, pubertal = 10, postpubertal = 1, adult = 22), ‘Age’ (1st trimester = 36 donors; 2nd trimester = 16; 1–10 y.o. = 10; 10–15 y.o. = 13; 19–28 y.o. = 8; 30–35 y.o. = 6; 35–40 y.o. = 3; 40–46 y.o. = 4; 55–56 y.o. = 2), ‘Menstrual stage’ (unknown for all ovarian donors), and ‘Clinical diagnosis’. Anatomical sampling site is specified (frequently this is not the case). | Cross- sectional reference maps from a few donors per age. No longitudinal follow-up, no clinical outcome and no biomarker or endpoint qualification.<br><br>No reproductive hormone levels and cycle length are collected, so reproductive staging cannot be detailed or accurate according to the STRAW +10 criteria. Additionally, assignment of ‘perimenopause’ requires menstrual irregularity and/or vasomotor symptom data, as per the European Society of Endocrinology clinical guideline. |
| UK Biobank and the ReproGen consortium<br>https://www.ukbiobank.ac.uk/<br>https://www.reprogen.org/ | Genetics and self-reported reproductive history at scale.<br>ReproGen meta-analysed over 200,000 women and found 290 loci linked to menopause timing. | Ovarian tissue or molecular data. Genetics explains only about 12% of the variation in menopause timing, so the rest has to be found in tissue biology. |
| Study of Women’s Health Across the Nation (SWAN)<br>https://agingresearchbiobank.nia.nih.gov/studies/swan/details | NIH-funded longitudinal cohort following women through the menopause transition, with serum hormones and health outcomes. | Blood and survey data only. No ovarian tissue, no single-cell or spatial omics, and no open omics release. |
| Private women's health companies (Gameto, Oviva, Celmatix, cycle-tracking apps) | Proprietary preclinical, clinical, genetic and wearable data. | Not open, mostly not tissue-level and nor harmonized across sources. |
| ARPA-H<br>https://arpa-h.gov/explore-funding/initiatives-and-sprints/sprint-for-womens-health<br>https://www.businesswire.com/news/home/20241023366586/en/Celmatix-Selected-to-Receive-%243.5-Million-Award-from-ARPA-Hs-Sprint-for-Womens-Health | Includes a topic on prioritizing ovarian health, funding companies such as Celmatix, which is targeting anti-müllerian hormone to extend ovarian function, and Gameto, whose $10M award supports an implantable ovarian organoid for menopause.<br>https://wewillcure.com/insights/womens-health/investment/gameto-awarded-usd10m-arpa-h-funding | Product development by individual companies, no shared reference data, and the data it generates stays with each company. |
| PRiSM (Precision, Sex-Based Medicine) at MIT<br>https://prism.mit.edu/ | A multi-scale, multi-modal project integrating available data sets in with their first model focused on ovaries being released in early 2027. | Working with existing data sets rather than capturing any new data. |

We will also  fund work that would not happen otherwise. Labs that lost NIH funding are eligible, but only for work that fits the shared standards and data plan.
Key Roles, Governance, Accountability

**Roles**
General Manager (Founder and operating lead)
Scientific lead (RNA biologist with specialized training in neuroscience and computational biology)
Ovarian Biology Lead (Reproductive Genetics)
Due Diligence Lead (Cardiovascular pharmacology)
Scientific Chair (Genesis Lead) 
Software Engineer
Computational Biologist/ Data Scientist
Project Manager


**Lab selection.** Labs enter through our diligence pipeline, then external review by advisors with no conflict of interest. Each lab signs onto the shared data protocol as a condition of funding.
**Accountability.** Every lab has annual milestones. Funding continues only when milestones are met. Donors get a portfolio report each quarter.
**Governance.**  Governance will be established with strategic input from Orrick, Herrington & Sutcliffe LLP during 501(c)(3) formation, following best practices and standards. 

**Measuring and sustaining impact**
AthenaBIO succeeds if other people use what it produces: researchers download and reuse the data, trials adopt the endpoints, and companies build on the biomarkers. Producing data is not enough. We track impact in three stages, taking into consideration that uptakes take time to appear and early signals should predict later ones. 
| Stage | Timeframe | What it means | How we measure it |
|---|---|---|---|
| Delivery | Year 5 | Standards work and the data is reaching the public. | Share of funded projects meeting their pre-registered power target; share samples; time from collection to public release. |
| Uptake | Years 6-8 | Data is useful beyond the people who generated it | Downloads and access requests from outside, publications and preprints using data by groups we did not fund, models trained, cross-lab pooled analyses. |
| Adoption | Years 9+ | Field and industry are building on what we made | Candidate biomarkers entering formal qualification; report on trials or registries that adopt them; licenses; follow-on capital. |

We will publish these numbers every year against targets set in advance, including projects that missed their prior target selection. Where we can, we will report. Dollars spent, samples collected and papers published by funded labs are inputs, not results, and we will not count them as success.  

**What we measure:**
- Data quality and coverage: datasets released, life stages and clinical outcomes they cover, share QC and time from collection to public release.
- Standards adoption: labs and datasets using the Genesis metadata standard, external teams submitting to the benchmark.
- Biomarker qualification: candidates at each regulatory stage and how many are qualified.
- Endpoints: endpoints adopted by trial sponsors or proposed to regulators.
- External use: reuse by groups we didn’t fund, including data downloads, citations, models trained and access requests.
- Downstream capital: spinouts, licenses and private capital raised on fund-generated IP. 

**After year 5**

**Our goal is to leave a lasting open-science resource for female biology, starting with the ovary, that meets the AI-ready standard and improves both disease modeling and biomarker discovery.**
- Data: transferred to a long-term open repository, with maintenance funded for at least 5 years and a standing data access committee for controlled-access data.
- Standards: handed to a professional society or consortium to keep current
- Network: continues on government and industry funding, using fund data as the base for new grants.
- AthenaBIO: sets up the structure for open-access and winds down the operations, sets up an endowment for the upkeep and management of the infrastructure, or continues the work only if a new thesis justifies it.

**For more information and date room access :**
- hello@athenabio
