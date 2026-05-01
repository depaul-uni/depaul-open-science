# Chapter 5 - Transparent Reporting Standards

**Lead author:** Kimberly Quinn & Vahid Alizadeh
**Source meeting:** Meeting 5 (February 2026)
**Status:** *adapted from the SLC's live Notion meeting page; minor formatting cleanup applied*

---


**Date:** March 6, 2026

**Presenters:** Kimberly & Vahid

**Learning Community:** Open Science in Practice: Tools and Workflows for Transparent, Reproducible Research

---

## 🎯 Meeting Objectives

By the end of this session, participants will be able to:

1. **Explain the evidence base** showing how incomplete reporting undermines research quality, synthesis, and clinical/policy translation
2. **Navigate the EQUATOR Network** to identify the appropriate reporting guideline(s) for any study type
3. **Apply major reporting guidelines** (CONSORT 2025, PRISMA 2020, STROBE, SRQR, COREQ) to their own discipline and research designs
4. **Distinguish between qualitative reporting standards** (SRQR vs. COREQ) and apply them appropriately
5. **Implement discipline-specific reporting practices** for psychology, chemistry, computing, criminology, and modern languages
6. **Use automated tools** ([Penelope.ai](http://Penelope.ai), [GoodReports.org](http://GoodReports.org)) to check reporting completeness
7. **Construct transparent methods and results sections** that meet current reporting standards
8. **Complete a reporting checklist** for their own research (published or in-progress)

---

# PART 1️⃣: The "Why" and the Disciplinary Perspective

## 1.1 Why Transparent Reporting Matters (Beyond Reproducibility)

### The Reporting Quality Gap: Evidence from Meta-Research

Despite decades of methodological advances, biomedical and social science research continues to suffer from a **pervasive reporting quality gap**. Glasziou and colleagues estimated that approximately **85% of research investment is wasted**, with at least **50% of studies suffering from such poor reporting that they are unusable for evidence synthesis, replication, or clinical translation**. This waste translates to over $170 billion annually in global health research alone.

The reporting problem manifests across multiple dimensions:

**Methodological Details:** Systematic reviews consistently find that essential methodological information is frequently omitted. In diagnostic accuracy studies, 20% used different reference standards for positive and negative tests (inflating accuracy estimates), and only 17% used double-blind reading. In animal research, before ARRIVE guidelines, most studies failed to report randomization, blinding, sample size calculations, or handling of missing data.

**Outcome Reporting:** Approximately **31% of trials exhibit discrepancies between pre-specified and reported outcomes**, with studies showing changes more likely to report statistically significant results. Kirkham and colleagues found that in 23% of systematic reviews, selective outcome reporting reduced the treatment effect by at least 20%.

**Intervention Description:** Studies of behavioral interventions show that many fail to provide sufficient detail for replication, lacking information on intervention timing, dosage, theoretical basis, and comparison conditions.

### Impact on Evidence Synthesis and Clinical Practice

Incomplete reporting directly undermines the scientific enterprise in several ways:

**Systematic Reviews and Meta-Analyses:** When primary studies fail to report outcomes, effect sizes, confidence intervals, or methodological details, systematic reviewers cannot adequately assess study quality, pool results, or draw reliable conclusions. This forces reviewers to contact authors for missing information - a process that often fails, as approximately 50% of completed trials are never published in full.

**Clinical Decision-Making:** Healthcare providers and policymakers rely on published research to make evidence-based decisions. When research reports omit harms, adverse events, or negative findings, clinicians lack the complete picture needed to weigh benefits against risks.

**Economic and Societal Costs:** Research waste extends beyond the direct financial loss. When clinicians cannot implement interventions due to incomplete descriptions, when systematic reviews draw incorrect conclusions from biased reporting, and when subsequent researchers duplicate failed experiments unknowingly, the human and societal costs multiply.

### Connection to Research Waste Reduction

Chalmers and Glasziou's influential 2009 analysis identified poor reporting as one of four major sources of avoidable research waste (alongside asking wrong questions, inadequate methods, and non-publication). Even when research is well-designed and published, **if reporting is incomplete or unclear, the knowledge cannot contribute to the cumulative evidence base**.

---

## 1.2 The EQUATOR Network Ecosystem  -  Deep Dive

### History, Mission, and Scope

The **EQUATOR Network** (Enhancing the QUAlity and Transparency Of health Research) was established in 2006 as an international initiative to improve the reliability and value of health research literature by promoting transparent and accurate reporting. The network serves as a comprehensive resource center housing over **500 reporting guidelines** organized by study design, clinical area, and research type.

The core mission encompasses:

- Developing and maintaining a searchable library of reporting guidelines
- Promoting guideline awareness among researchers, journals, and funders
- Providing training resources for authors, reviewers, and editors
- Conducting research on guideline effectiveness and adoption

### Navigating the EQUATOR Library

The EQUATOR Network organizes guidelines into primary categories:

**By Study Design:**

- Randomized trials (CONSORT and extensions)
- Observational studies (STROBE, RECORD, STROBE-MR)
- Systematic reviews (PRISMA, PRISMA-P, PRISMA-ScR)
- Qualitative research (SRQR, COREQ, ENTREQ)
- Diagnostic accuracy (STARD)
- Case reports (CARE)
- Prognostic studies (TRIPOD)
- Economic evaluations (CHEERS)

**By Research Phase:**

- Study protocols (SPIRIT, PRISMA-P)
- Completed studies (most guidelines)
- Extensions for specific contexts (harms, abstracts, pilot studies)

### Recent Developments (2024–2025)

The EQUATOR Network continues to evolve with the research landscape:

**Major Guideline Updates:** The simultaneous publication of CONSORT 2025 and SPIRIT 2025 in April 2025 marked the most significant update to trial reporting standards in 15 years. These updates incorporate open science principles, data sharing requirements, and patient involvement reporting.

**GoodReports Platform:** In 2021, EQUATOR launched [GoodReports.org](http://GoodReports.org), an interactive website helping authors find appropriate guidelines through a decision-tree wizard and providing validation tools to check checklist completion. The platform has been integrated with automated manuscript checking systems like [Penelope.ai](http://Penelope.ai).

**Expanding Coverage:** New guidelines continue to emerge for previously under-served areas, including CCQR (Comprehensive Criteria for Reporting Qualitative Research) for global health qualitative studies (2024), and ongoing development of guidelines for AI use in guideline development.

---

## 1.3 Major Reporting Guidelines by Study Design

### CONSORT 2025  -  Randomized Controlled Trials (MAJOR 2025 UPDATE)

> **CONSORT 2025 is a major update!** The April 2025 revision - developed through a three-round Delphi survey with 317 participants and a consensus meeting of 30 international experts - represents the most substantial revision in 15 years.

The **Consolidated Standards of Reporting Trials (CONSORT)** statement has become the international gold standard for RCT reporting since its 1996 inception.

**Key Updates in CONSORT 2025:**

The updated statement expands from 25 to **30 items**, with seven new checklist items, three revised items, one deleted item, and significant restructuring around open science principles.

**New Items:**

1. **Patient and Public Involvement (Item 8):** Details of how patients or the public were involved in trial design, conduct, and reporting
2. **Data Sharing (Item 4):** Where and how to access de-identified participant data, statistical code, and related materials
3. **Harms (within existing item):** Detailed description of how harms were defined and assessed
4. **Intervention Delivery (Item within methods):** Clear reporting of how interventions and comparators were administered

**Restructured Checklist Sections:**

- Title and Abstract (Item 1)
- **Open Science** (Items 2–5): Trial registration, protocol access, data sharing, funding/COI
- Introduction (Items 6–7)
- Methods (Items 8–17)
- Results (Items 18–26)
- Discussion (Item 27)
- Other Information (Items 28–30)

**The Open Science Section** represents a paradigm shift, emphasizing transparency before, during, and after trial completion. This aligns with global movements toward research transparency and reflects updated journal policies from major publishers (BMJ, JAMA, Lancet, Nature Medicine, PLOS Medicine).

**CONSORT 2025 Checklist Structure:**

- **30 total items** (up from 25)
- Includes flow diagram for participant progression
- Accompanied by extensive Explanation and Elaboration document with examples

### PRISMA 2020  -  Systematic Reviews and Meta-Analyses

The **Preferred Reporting Items for Systematic reviews and Meta-Analyses (PRISMA)** statement was updated in 2020 to reflect advances in systematic review methodology.

**PRISMA 2020 Structure:**

- **27-item checklist** (compared to 27 in 2009, but with substantial content changes)
- Items organized into: Title, Abstract, Introduction, Methods, Results, Discussion, Funding
- Separate abstract checklist (12 items)
- Updated flow diagrams with horizontal orientation (easier to read)

**Notable Changes from 2009:**

1. **Search Documentation:** All database search strategies must be reported (not just one), plus searches of websites, registers, and other sources
2. **Exclusion Justification:** Authors must explain why studies that appear eligible were excluded
3. **Data Availability:** Public availability of data collection forms, extracted data, and analytic code should be indicated
4. **Synthesis Methods:** More detailed reporting of synthesis approaches beyond traditional meta-analysis
5. **Certainty Assessment:** Required assessment of certainty/confidence in body of evidence

**PRISMA Extensions:** PRISMA-P (Protocols), PRISMA-ScR (Scoping Reviews), PRISMA for Individual Patient Data Meta-Analyses, PRISMA for Network Meta-Analyses

**Tooling:** PRISMA 2020 flow diagrams can be generated using a [free Shiny app](https://www.eshackathon.org/software/PRISMA2020.html) or R package.

### STROBE  -  Observational Studies

The **Strengthening the Reporting of Observational Studies in Epidemiology (STROBE)** statement, published in 2007, provides reporting standards for cohort, case-control, and cross-sectional studies.

**STROBE Checklist:**

- **22 items** covering title, abstract, introduction, methods, results, and discussion
- **18 items common** to all three designs (cohort, case-control, cross-sectional)
- **4 items specific** to each study design

**Key Reporting Elements:** Study design specification, setting and participant eligibility, variables and data sources, bias management approaches, study size determination, statistical methods, participant flow (with flow diagram recommended), descriptive data and outcome data, main results with measures of precision.

**Impact:** Studies examining STROBE adoption show mixed results - while awareness has increased, compliance remains inconsistent, with many studies still omitting critical information on study approach, reflexivity, and trustworthiness techniques.

**Extensions:** STROBE-MR (Mendelian Randomization), RECORD (Routinely collected health data)

### ARRIVE 2.0  -  Animal Research

The **Animal Research: Reporting of In Vivo Experiments (ARRIVE)** guidelines, updated in 2020, address the persistent problem of inadequate reporting in animal studies.

**ARRIVE 2.0 Innovation  -  Two-Tier Structure:**

**Essential 10 (Minimum Requirement):**

1. Study design
2. Sample size
3. Inclusion and exclusion criteria
4. Randomization
5. Blinding
6. Outcome measures
7. Statistical methods
8. Experimental animals
9. Experimental procedures
10. Results

**Recommended Set (Additional Context  -  11 items):** Abstract, background, objectives, ethics statement, housing and husbandry, animal care and monitoring, interpretation, generalizability, protocol registration, data access, declaration of interests.

This prioritization helps journals enforce minimum standards while encouraging comprehensive reporting.

### TREND  -  Non-Randomized Behavioral Interventions

The **Transparent Reporting of Evaluations with Nonrandomized Designs (TREND)** statement, published in 2004, addresses behavioral and public health interventions evaluated without randomization.

**TREND Checklist:**

- **22 items** emphasizing intervention theory, description, and bias management
- Designed to complement CONSORT for non-randomized designs

**Unique TREND Elements:** Theoretical basis of intervention (explicit reporting required), detailed comparison condition description, unit of analysis and clustering considerations, methods to address confounding, applicability and generalizability discussion.

**Adoption:** Many journals and CDC-funded programs require TREND compliance.

### CARE  -  Case Reports

The **CAse REport (CARE)** guidelines, developed through international consensus in 2013, standardize reporting of clinical case reports.

**CARE Checklist (13 Items):**

1. Title
2. Keywords
3. Abstract (structured)
4. Introduction
5. Patient information (de-identified)
6. Clinical findings
7. Timeline
8. Diagnostic assessment
9. Therapeutic interventions
10. Follow-up and outcomes
11. Discussion
12. Patient perspective
13. Informed consent

**Key Feature:** The patient perspective (Item 12) ensures the patient's voice is included in the case narrative.

---

## 1.4 Reporting Guidelines for Qualitative and Mixed-Methods Research

Qualitative research requires different reporting standards than quantitative studies, yet faces similar challenges with incomplete reporting. Two major guidelines serve this space, with important distinctions.

### SRQR (Standards for Reporting Qualitative Research)  -  21 Items

SRQR, published in 2014 by O'Brien and colleagues, provides comprehensive standards for **all types of qualitative research**.

**SRQR Coverage (21 Items):**

- Title and abstract (2 items)
- Introduction: Problem formulation, purpose/research question (2 items)
- Methods (11 items):
    - **Qualitative approach and research paradigm** (e.g., ethnography, grounded theory, phenomenology)
    - **Researcher characteristics and reflexivity** (positionality, assumptions, presuppositions)
    - Context and setting
    - Sampling strategy
    - Ethical issues
    - Data collection methods and instruments
    - Data collection procedures
    - Data processing and analysis
    - Trustworthiness techniques
- Results and discussion (5 items)
- Other (1 item)

> **Critically Important Elements Often Omitted:**
>
> - **Reflexivity (Item S6):** Absent or partial in 97% of studies in one review
> - **Qualitative approach specification (Item S5):** Missing in 64% of studies
> - **Trustworthiness techniques (Item S14):** Absent or partial in 68% of studies

**Broad Applicability:** SRQR applies to interviews, focus groups, ethnography, case studies, narrative research, and mixed qualitative approaches.

### COREQ (Consolidated Criteria for Reporting Qualitative Research)  -  32 Items

COREQ, published in 2007 by Tong and colleagues, is **specifically designed for interviews and focus groups**.

**COREQ Structure (32 Items in 3 Domains):**

**Domain 1: Research Team and Reflexivity (8 items)**

Personal characteristics (interviewer/facilitator, credentials, occupation, gender, experience/training) and relationship with participants (established, participant knowledge of interviewer, interviewer characteristics)

**Domain 2: Study Design (15 items)**

Theoretical framework, participant selection (sampling, contact method, sample size, non-participation), setting (location, presence of non-participants, description of sample), data collection (interview guide, repeat interviews, audio/visual recording, field notes, duration, data saturation, transcripts returned)

**Domain 3: Analysis and Findings (9 items)**

Data analysis (number of coders, description of coding tree, derivation of themes, software, participant checking) and reporting (quotations presented, data and findings consistency, clarity of major themes, clarity of minor themes)

### COREQ vs. SRQR  -  When to Use Which

| Aspect | SRQR | COREQ |
| --- | --- | --- |
| **Scope** | All qualitative approaches | Interviews and focus groups only |
| **Items** | 21 items | 32 items |
| **Detail Level** | Comprehensive across designs | Highly detailed for specific methods |
| **Best For** | Ethnography, case studies, any qualitative design | Qualitative interviews, focus group studies |
| **Published** | 2014 | 2007 |
| **Emphasis** | Research paradigm, theoretical framework | Team reflexivity, data collection specifics |

**Reporting Quality Evidence:** Studies applying both COREQ and SRQR to COVID-19 nursing research found that despite pandemic challenges, major issues persisted: underreporting of qualitative approach, reflexivity, and trustworthiness techniques.

### Emerging Standards: CCQR (2024)

The **Comprehensive Criteria for Reporting Qualitative Research (CCQR)**, published in 2024, extends qualitative reporting standards for **global health research**, incorporating cultural considerations and context-specific reporting needs not fully addressed by SRQR or COREQ.

### The Debate: Do Checklists Fit Qualitative Research?

> A contentious issue in qualitative methodology is whether standardized checklists risk **imposing positivist frameworks on interpretive research traditions**. Critics argue that qualitative research's emphasis on emergent design, researcher subjectivity, and contextual understanding resists the checklist approach. However, proponents note that reporting standards improve transparency without prescribing methodology - they describe **what to report**, not **how to research**.

### APA JARS for Mixed Methods

The **APA Journal Article Reporting Standards (JARS)**, updated in 2018, include comprehensive guidance for **qualitative and mixed-methods research** alongside quantitative studies.

**JARS Coverage:**

- Quantitative research standards
- **Qualitative research standards** (Levitt et al., 2018)
- **Mixed methods research standards** (separate guidelines)
- **JARS-REC** (Race, Ethnicity, and Culture) added in 2023

JARS provides approximately two dozen general reporting prescriptions plus design-specific requirements.

---

## 1.5 Discipline-Specific Reporting Landscapes

### Psychology: APA JARS and Replication Reporting

**Primary Guidelines:**

- **APA JARS** (Journal Article Reporting Standards)  -  comprehensive suite covering quantitative, qualitative, and mixed methods
- **APA 7th Edition** Publication Manual  -  integrates reporting requirements
- **Replication Reporting Standards**  -  specific guidance for direct and conceptual replications

**Key APA JARS Components:** Study design and rationale, participant/subject characteristics, sampling procedures, sample size/power/precision, measures and covariates, research design and data analysis. Reporting standards vary by design: experimental manipulations, clinical trials, longitudinal studies, observational studies, meta-analyses.

**Psychology-Specific Considerations:**

- Effect sizes and confidence intervals (mandatory in most APA journals)
- Reliability estimates for all measures
- Validity evidence for measures
- Transparency about excluded data and outlier treatment
- Open materials and data sharing (increasingly required)

**Resources:** [APA Style JARS website](https://apastyle.apa.org/jars) with checklists and tutorials, flowchart for selecting appropriate quantitative tables.

### Chemistry: IUPAC Standards and Journal-Specific Requirements

**Primary Standards:**

- **IUPAC (International Union of Pure and Applied Chemistry)** reporting standards for chemical research
- **Journal-specific requirements** from ACS (American Chemical Society), RSC (Royal Society of Chemistry), Wiley, Elsevier

**Synthesis Reporting:** Complete experimental procedures with quantities, temperatures, times, yields; purification methods and purity assessments; characterization data (NMR, MS, IR, elemental analysis); Supporting Information with full spectra and chromatograms.

**Spectroscopic Data Reporting:**

- **NMR:** chemical shifts (δ), coupling constants (J), integration, splitting patterns, solvent
- **Mass spectrometry:** ionization method, m/z values, relative intensities
- **IR:** peak positions (cm⁻¹), intensities (s, m, w), measurement conditions

**Crystallographic Data:**

- **CIF (Crystallographic Information File)** deposition in Cambridge Structural Database (CSD) or Inorganic Crystal Structure Database (ICSD)
- CCDC deposition numbers reported in manuscript
- Key crystallographic parameters in supplementary material

**ACS Guidelines:** Compound characterization section with complete data, experimental section with reproducible detail, Supporting Information requirements (procedures, spectra, computational details).

### Computing/HCI: ACM Transparency and Artifact Review

**Primary Guidelines:**

- **ACM SIGCHI** transparency and openness guidelines
- **ACM artifact review and badging** system
- **IEEE/ACM standards** for empirical software engineering

**ACM SIGCHI Reporting Requirements:** Study design (participant recruitment, sampling, assignment), materials availability (stimuli, protocols, interview guides), data availability (anonymized datasets when possible), statistical analysis (methods, software, effect sizes), ethical approval and consent procedures.

> **Generative AI Disclosure Requirements (2023–Present):**
>
> - Which AI tools were used (e.g., ChatGPT, GitHub Copilot)
> - How AI was used (ideation, code generation, writing assistance, data analysis)
> - What content was AI-generated vs. human-authored
> - Human oversight and verification processes

**ACM Badging System:**

- **Artifacts Available:** Materials publicly accessible
- **Artifacts Evaluated  -  Functional:** Artifacts work as described
- **Artifacts Evaluated  -  Reusable:** Artifacts can be adapted for other uses
- **Results Reproduced:** Independent verification of key results

**Empirical Software Engineering Standards:** Hardware specifications for performance studies, software versions and dependencies, datasets and benchmarks used, hyperparameter choices and tuning procedures, evaluation metrics with justification, statistical testing procedures, threats to validity discussion.

**Computing-Specific Challenges:** Rapid technological change (versioning critical), proprietary datasets and code, computational cost of replication, privacy concerns with user data.

### Criminology: Campbell Collaboration and Sensitive Data

**Primary Guidelines:**

- **Campbell Collaboration** standards for systematic reviews in social sciences
- **STROBE** for observational criminology studies
- **CONSORT/TREND** for intervention evaluations
- **NACJD (National Archive of Criminal Justice Data)** requirements

**Criminology-Specific Reporting Challenges:**

- **Sensitive populations:** Incarcerated individuals, victims, offenders
- **Confidentiality:** Geographic identifiers, small sample disclosure risk
- **Data access limitations:** Restricted-use datasets, IRB constraints
- **Ethical considerations:** Potential for harm from disclosure

**Campbell Collaboration Standards:** Explicit theory of change for interventions, context and setting details, implementation fidelity, heterogeneity exploration, equity considerations.

**Reporting with Restricted Data:** Describe dataset without disclosing identifying information, report aggregate statistics only, specify data access procedures for replication, document restrictions and justifications.

**Policy Relevance Section:** Many criminology journals require explicit policy implications, connection to criminal justice practice and reform, cost-benefit considerations when applicable.

### Modern Languages & Humanities: Interpretive Traditions

**Primary Guidelines:**

- **SRQR** for linguistic and language acquisition research
- **COREQ** for interview-based studies
- Field-specific reporting norms (vary by subfield)

**Corpus Linguistics Reporting:** Corpus description (size, composition, representativeness), query syntax and parameters, concordance software and version, coding schemes for qualitative analysis, inter-rater reliability when applicable.

**Digital Humanities Reporting:** Data sources and curation procedures, tools and algorithms used, computational parameters, visualization methods, code and dataset availability (when possible).

**Interpretive Research Traditions:**

- **Positionality statements:** Researcher background, relationship to subject matter
- **Theoretical framework:** Explicit grounding in literary, cultural, linguistic theory
- **Analytical transparency:** How interpretations were derived from texts
- **Alternative interpretations:** Acknowledgment of other possible readings

**Challenges for Humanities Reporting:** Qualitative interpretation vs. quantitative measurement, single-scholar vs. collaborative research norms, archive/primary source accessibility, copyright restrictions on textual data.

**Adaptation Strategy:** SRQR and COREQ guidelines can be adapted for humanities research by replacing "participants" with "texts/archives" where applicable, emphasizing hermeneutic approach over research "paradigm", foregrounding interpretive choices and theoretical commitments, and documenting archival/textual sources thoroughly.

---

## 1.6 Publication Bias and Selective Outcome Reporting

### What is Selective Outcome Reporting?

**Selective outcome reporting (SOR)** occurs when researchers choose which outcomes to report based on the magnitude or direction of results, typically favoring statistically significant findings.

**Types of SOR (Kirkham et al.):**

1. **Selective omission of entire outcomes:** Analyzed outcomes not reported at all
2. **Selective choice of data for an outcome:** Reporting only favorable time points
3. **Selective reporting of analyses:** Adjusted vs. unadjusted; subgroup vs. full sample
4. **Selective reporting of subsets:** Reporting only certain types of events (e.g., ischemic but not hemorrhagic strokes)
5. **Selective under-reporting of data:** Stating "not significant" without providing actual values

### Prevalence and Impact

> **Prevalence:**
>
> - **31% of registered trials** show discrepancies between registered and published outcomes
> - In osteoarthritis RCTs, **48% had discrepancies** in primary outcomes between protocol and publication
> - **18% of high-impact medical journal RCTs** had primary outcome discrepancies
>
> **Impact on Meta-Analyses:**
>
> - When Kirkham adjusted 81 systematic reviews for outcome reporting bias, **23% showed at least 20% reduction in treatment effect**
> - In 42 meta-analyses with only significant outcomes, **19% (8 reviews) became non-significant** after adjustment

**Outcome Switching:** Studies with outcome changes between registration and publication were **more likely to report statistically significant results**, suggesting deliberate manipulation to achieve positive findings.

### The Role of Reporting Guidelines in Reducing Bias

Transparent reporting standards combat selective reporting through:

**Pre-specification Transparency:**

- **CONSORT 2025 Item 10:** Requires reporting of "important changes to the trial after it commenced including any outcomes or analyses that were not prespecified, with reason"
- **SPIRIT 2025:** Protocol registration makes original plans publicly available for comparison

**Complete Outcome Reporting:** Guidelines require reporting of **all** pre-specified outcomes, not just significant ones. Negative and null results must be reported. Deviations from pre-registered plans must be transparently documented with justification.

**Harms Reporting:** CONSORT 2025 includes dedicated item for **harms assessment and reporting**, preventing selective focus on benefits while suppressing adverse events.

### The AllTrials Campaign

The **AllTrials** campaign advocates that:

1. All clinical trials must be **registered at inception**
2. All results must be **reported within 12 months of completion**
3. Historical trial results must be **disclosed retroactively**

This movement, supported by researchers, patients, and regulators globally, directly addresses the estimated **50% non-publication rate** for completed trials.

---

## 1.7 The Role of Journals, Reviewers, and Institutions

### Journal Adoption and Enforcement

**Current Landscape:**

- Nearly **200 journals** formally endorse PRISMA guidelines
- Over **1000 journals** endorse ARRIVE for animal research
- CONSORT has been endorsed by hundreds of journals since 1996

**Enforcement Levels Vary Widely:**

- Some journals **require** checklist submission at manuscript submission
- Others **recommend** guideline use without enforcement
- Many journals **mention** guidelines but don't verify compliance

**Impact of Endorsement:** Studies show that journal endorsement **is associated with improved reporting quality**, but the effect is modest without active enforcement. The introduction of STROBE, for example, showed improvement in endorsed journals but incomplete adoption.

### Peer Reviewer Training

**The Problem:** Reviewers often lack training in assessing reporting quality, focusing instead on study design, analysis, and conclusions. This perpetuates poor reporting even when guidelines exist.

**Solutions:**

- **EQUATOR Network** offers workshops for reviewers and editors
- Some journals provide reviewer checklists aligned with reporting guidelines
- [**Penelope.ai**](http://Penelope.ai) and similar tools enable pre-review automated checking

### Institutional Support

**Academic Institutions Can Support Reporting Through:**

- **Writing centers:** Training on reporting standards
- **Libraries:** Systematic review services, guideline navigation support
- **Research offices:** Protocol review for reporting completeness
- **Biostatistics cores:** Support for complete results reporting

### Funder Mandates

**Major Funders Now Require:**

- **NIH:** Trial registration ([ClinicalTrials.gov](http://ClinicalTrials.gov)), results reporting within 12 months
- **Wellcome Trust:** Open access publication, data sharing
- **Gates Foundation:** Immediate open access, data availability
- **Horizon Europe:** Protocol registration, open science practices

These mandates increasingly include reporting standard compliance as a condition of funding.

---

# PART 2️⃣: The Tools and Hands-On Implementation

## 2.1 Finding Your Reporting Guideline

### Step-by-Step: Using the EQUATOR Network Wizard

> **Navigation Path:**
>
> 1. Visit [**https://www.equator-network.org/**](https://www.equator-network.org/)
> 2. Click **"Reporting Guidelines"** → **"Search for a reporting guideline"**
> 3. Use the **Wizard** (recommended for beginners) or **Advanced Search**

**Wizard Decision Points:**

- What is your study type? (Intervention, Observation, Diagnostic, etc.)
- What is your study design? (Randomized, non-randomized, cohort, etc.)
- Is there a specific clinical area?
- Is this a protocol or a completed study?

**Example Walkthrough:**

- **Study:** A randomized trial of a mindfulness intervention for anxiety
- **Wizard Path:** Study type → Intervention → Randomized trial → CONSORT 2025
- **Additional Needs:** Behavioral intervention → Check CONSORT extension for non-pharmacological interventions

### Decision Tree: Study Design → Guideline

```
Study Design → Reporting Guideline

Randomized trial → CONSORT 2025
   └─ Non-pharmacological intervention → + TIDieR checklist
   └─ Pilot/feasibility trial → + CONSORT pilot extension
   └─ Trial protocol → SPIRIT 2025

Systematic review/Meta-analysis → PRISMA 2020
   └─ Protocol → PRISMA-P
   └─ Scoping review → PRISMA-ScR

Observational study → STROBE
   ├─ Cohort study → STROBE
   ├─ Case-control → STROBE
   └─ Cross-sectional → STROBE

Qualitative study:
   ├─ Interviews/focus groups → COREQ
   ├─ Any qualitative design → SRQR
   └─ Mixed methods → APA JARS mixed methods

Diagnostic accuracy → STARD 2015
Case report → CARE
Animal research → ARRIVE 2.0
Non-randomized intervention → TREND
```

### Handling Studies Spanning Multiple Guidelines

**Scenario 1: RCT with Qualitative Component**

Primary: **CONSORT 2025** for the trial. Secondary: **COREQ** or **SRQR** for qualitative arm. Strategy: Main manuscript follows CONSORT; qualitative findings either integrated (with COREQ items addressed) or reported separately.

**Scenario 2: Systematic Review with Meta-Analysis**

Primary: **PRISMA 2020**. Additional: Statistical synthesis extensions if using advanced methods (network meta-analysis, individual patient data).

**Scenario 3: Observational Study with Complex Intervention**

Primary: **STROBE**. Secondary: **TIDieR** (Template for Intervention Description and Replication) for detailed intervention description.

### When No Guideline Fits

**If no guideline exists for your study type:**

1. **Identify the closest guideline** by design features
2. **Adapt items** that apply to your study
3. **Consult related guidelines** for reporting principles
4. **Document your approach:** Explain in methods which guidelines informed your reporting
5. **Consider developing new guidelines:** Contact EQUATOR Network if your field lacks standards

---

## 2.2 Anatomy of a Reporting Checklist: CONSORT 2025 Deep Dive

### Walking Through the CONSORT 2025 Checklist

**CONSORT 2025: 30-Item Structure**

**Section 1: Title and Abstract (Item 1)**

1a: Identification as a randomized trial (in title)

1b: Structured summary of trial design, methods, results, conclusions

**Section 2: Open Science (Items 2–5)  -  NEW SECTION**

- **Item 2:** Trial registration (registry name, number, URL, date)
- **Item 3:** Protocol and statistical analysis plan access
- **Item 4:** Data sharing (where/how to access de-identified data, code, materials)
- **Item 5:** Funding sources, role of funders, conflicts of interest

**Section 3: Introduction (Items 6–7)**

- **Item 6:** Scientific background and rationale
- **Item 7:** Specific objectives (benefits AND harms)

**Section 4: Methods (Items 8–17)**

- **Item 8:** **Patient and public involvement** (NEW)  -  details of involvement in design, conduct, reporting
- **Item 9:** Trial design (type, allocation ratio, framework)
- **Item 10:** Changes to protocol after trial started (including unprespecified outcomes/analyses)
- **Item 11:** Trial setting and locations
- **Item 12:** Eligibility criteria (participants, sites, individuals)
- **Item 13:** Interventions (for each group  -  sufficient detail for replication)
- **Item 14:** Outcomes (prespecified primary and secondary, how/when assessed)
- **Item 15:** Sample size (how determined, power calculation if done)
- **Item 16:** Randomization (sequence generation, allocation concealment, implementation)
- **Item 17:** Blinding (who was blinded, how achieved, similarity of interventions)
- **Item 18:** Statistical methods (primary/secondary outcomes, subgroups, missing data handling)

**Section 5: Results (Items 19–26)**

- **Item 19:** Flow diagram (participant flow through study)
- **Item 20:** Recruitment dates and follow-up completion
- **Item 21:** Baseline characteristics (each group)
- **Item 22:** Intervention implementation (intervention received by each group)
- **Item 23:** Outcomes (for each group, effect size with precision)
- **Item 24:** Harms (NEW emphasis)  -  adverse events in each group
- **Item 25:** Ancillary analyses (subgroups, adjusted analyses)

**Section 6: Discussion (Item 26)**

**Item 26:** Interpretation (benefits, harms, limitations, generalizability)

**Section 7: Other Information (Items 27–30)**

Item 27: Consent statement, Item 28: Protocol access (where available), Item 29: Funding (sources, role)

### How to Fill Out the Checklist with Page Numbers

> **Practical Steps:**
>
> 1. **Download the fillable checklist** from [https://www.consort-spirit.org/](https://www.consort-spirit.org/)
> 2. **As you write each section**, note the page number where that item appears
> 3. **For items spanning multiple pages**, note the primary location
> 4. **If an item is not applicable** (e.g., no blinding possible), write "N/A" and justify in manuscript

**Common Pitfalls:**

| Pitfall | Why It's a Problem | How to Avoid |
| --- | --- | --- |
| Writing "See methods section" | Reviewer must hunt for information | Provide specific page number |
| Omitting N/A items | Looks like oversight | Explicitly state N/A with brief justification |
| Generic responses | Doesn't help reader locate information | Be specific: "Page 7, paragraph 3" |
| Incomplete item coverage | Misses sub-items within main items | Review each item carefully; many have parts a, b, c |

### Comparing Checklist Structures: CONSORT vs. STROBE vs. PRISMA

| Feature | CONSORT 2025 | STROBE | PRISMA 2020 |
| --- | --- | --- | --- |
| **Total Items** | 30 | 22 | 27 |
| **Flow Diagram** | Required | Recommended | Required |
| **Open Science Section** | Yes (Items 2-5) | No dedicated section | Partial (data/materials) |
| **Intervention Detail** | Extensive (TIDieR integration) | Limited | N/A (reviews interventions) |
| **Design-Specific Items** | Randomization, blinding | 4 items vary by observational design | Synthesis methods vary |
| **Harms Reporting** | Dedicated item | Mentioned | In results (from primary studies) |
| **Patient Involvement** | Item 8 (NEW) | Not addressed | Not addressed |
| **Protocol Registration** | Item 2 (required) | Not required | PRISMA-P addresses protocols |

---

## 2.3 Writing Transparent Methods Sections

### Before and After Examples

**EXAMPLE 1: Sample Size Reporting**

❌ **Before (Inadequate):**

> "We recruited 50 participants for this study."
>

✅ **After (Transparent):**

> "We recruited 50 participants (25 per group). This sample size was determined a priori based on a power analysis to detect a medium effect size (Cohen's d = 0.60) for the primary outcome, using G*Power 3.1 software."
>

**EXAMPLE 2: Randomization Reporting**

❌ **Before (Inadequate):**

> "Participants were randomly assigned to groups."
>

✅ **After (Transparent, CONSORT 2025 Item 16):**

> "Participants were randomly assigned to intervention or control groups (1:1 allocation ratio) using a computer-generated randomization sequence created by an independent statistician via R software (blockrand package, version 2.0). Allocation concealment was ensured using sequentially numbered, opaque, sealed envelopes."
>

**EXAMPLE 3: Qualitative Researcher Reflexivity**

❌ **Before (Inadequate):**

> "Semi-structured interviews were conducted."
>

✅ **After (Transparent, SRQR Item S6):**

> "Semi-structured interviews were conducted by the first author (J.S.), a clinical psychologist with 15 years of experience. The interviewer approached the study from a constructivist paradigm. Prior to data collection, J.S. documented personal assumptions about mindfulness and potential biases. These reflexive notes were revisited throughout analysis."
>

**EXAMPLE 4: Computing Study**

❌ **Before (Inadequate):**

> "We evaluated model performance using standard metrics."
>

✅ **After (Transparent, ACM Standards):**

> "We evaluated model performance using precision, recall, and F1-score on the held-out test set (n = 5,000 examples). Metrics were computed using scikit-learn (version 1.2.0) in Python 3.9. Hyperparameters were tuned via 5-fold cross-validation using grid search. All experiments ran on NVIDIA A100 GPUs; training time was approximately 6 hours per model."
>

**EXAMPLE 5: Chemistry Synthesis**

❌ **Before (Inadequate):**

> "The compound was synthesized and characterized."
>

✅ **After (Transparent, ACS Standards):**

> "Synthesis of 2,4-dinitrophenylhydrazine (1): To a stirred solution of 2,4-dinitrofluorobenzene (500 mg, 2.69 mmol) in ethanol (20 mL) was added hydrazine hydrate (161 uL, 3.23 mmol, 1.2 equiv). The mixture was stirred for 4 hours, purified by column chromatography to afford product 1 as an orange solid (480 mg, 90% yield). Full spectra in Supporting Information."
>

### Key Elements Most Commonly Omitted

**Across All Disciplines:**

1. **Sample Size Justification:** Power analysis with effect size, alpha, power specified
2. **Handling of Missing Data:** Report number excluded at each stage, describe imputation methods
3. **Deviations from Pre-Registered Plans:** CONSORT 2025 Item 10 requires explicit statement with justification

**Qualitative Research Specific:**

1. **Theoretical Framework:** SRQR Item S5 requires explicit qualitative approach specification
2. **Researcher Positionality:** SRQR Item S6 and COREQ Items 1-8 require detailed reflexivity
3. **Data Saturation:** Explicit criteria for saturation, when it was reached, and how it was determined

**Computing Research Specific:**

1. **Hyperparameter Selection:** Explicit values tested, search method, validation approach
2. **Dataset Characteristics:** Version, date accessed, preprocessing steps, train/validation/test splits with sizes

---

## 2.4 Transparent Results Reporting

### Reporting ALL Pre-Specified Outcomes

**The Requirement:**

Both **CONSORT 2025** (Item 23) and **SPIRIT 2025** require reporting of **all** outcomes specified in the protocol, regardless of statistical significance or direction of effect.

**Implementation:**

1. **Cross-check protocol against manuscript:** Ensure every registered outcome is addressed
2. **If an outcome cannot be reported:** State explicitly with reason (e.g., "Cortisol data could not be analyzed due to assay failure in 40% of samples")
3. **Secondary outcomes:** Report even if non-significant; do not bury in supplementary materials only

### Effect Sizes and Confidence Intervals: Why and How

**Why Effect Sizes Matter:**

- **P-values alone** indicate only whether an effect exists, not its magnitude
- **Effect sizes** quantify the strength of phenomena
- **Confidence intervals** communicate precision and uncertainty

**How to Report:**

> **Continuous Outcomes:**
>
> Cohen's d or Hedges' g (standardized mean difference), Mean difference with 95% CI
>
> *Example:* "The intervention group showed greater anxiety reduction (M = 15.2, SD = 4.1) compared to control (M = 10.3, SD = 3.8), Cohen's d = 1.27, 95% CI [0.85, 1.69]."
>
> **Binary Outcomes:**
>
> Risk ratio or odds ratio with 95% CI, Number needed to treat (NNT)
>
> *Example:* "Abstinence rates were higher in the intervention group (45%, 45/100) vs. control (20%, 20/100), RR = 2.25, 95% CI [1.48, 3.42], NNT = 4."
>
> **Correlation/Association:**
>
> Correlation coefficient with 95% CI, R² for variance explained
>
> *Example:* "Sleep quality correlated with cognitive performance (r = 0.52, 95% CI [0.38, 0.64], p < .001)."

### Reporting Negative and Null Results

**The Problem:**

Studies with null findings are less likely to be published (publication bias), creating a distorted literature where only positive results appear.

**The Solution:**

- **Report null results completely:** Do not simply state "no significant difference"; provide means, SDs, effect sizes, CIs
- **Distinguish null from inconclusive:** A well-powered study finding no effect is informative; an underpowered study is inconclusive
- **Frame appropriately:** "We found no evidence for a difference..." (rather than "We found no difference...")

**Example:**

> "Contrary to our hypothesis, cognitive behavioral therapy did not significantly reduce insomnia severity compared to sleep hygiene education. Mean ISI scores at 8 weeks were 12.4 (SD = 5.2) for CBT and 11.8 (SD = 4.9) for control, mean difference = 0.6, 95% CI [-1.8, 3.0], Cohen's d = 0.12, 95% CI [-0.34, 0.58]. This study was powered to detect a moderate effect (d = 0.50) with 80% power; thus, we can conclude that any effect is smaller than anticipated."
>

### Flow Diagrams: CONSORT and PRISMA

**CONSORT Flow Diagram:**

Shows participant progression through trial phases:

1. **Enrollment:** Assessed for eligibility → Excluded (with reasons) → Randomized
2. **Allocation:** Assigned to intervention → Received intervention → Did not receive (with reasons)
3. **Follow-up:** Lost to follow-up (with reasons) → Discontinued intervention (with reasons)
4. **Analysis:** Analyzed → Excluded from analysis (with reasons)

**Creating CONSORT Flow Diagrams:**

- **Manual:** Download template from [https://www.consort-spirit.org/](https://www.consort-spirit.org/)
- **R Package:** `consort` package for automated diagram generation
- **Graphviz/DiagrammeR:** For custom diagrams

**PRISMA Flow Diagram:**

Shows study selection process for systematic reviews:

1. **Identification:** Records from databases, registers, other sources
2. **Screening:** Records screened → Excluded (with reasons)
3. **Eligibility:** Reports assessed → Excluded (with reasons, counts)
4. **Included:** Studies included in review

**Creating PRISMA Flow Diagrams:**

- **Shiny App:** [https://www.eshackathon.org/software/PRISMA2020.html](https://www.eshackathon.org/software/PRISMA2020.html) (free, interactive)
- **Templates:** Download from [https://www.prisma-statement.org/](https://www.prisma-statement.org/)
- **Word/PowerPoint:** Editable templates available

### Handling Deviations from Pre-Registered Plans

> **When Plans Change:**
>
> - Protocol modifications during trial
> - Outcome measures changed
> - Analysis plan updated
> - Additional exploratory analyses added
>
> **CONSORT 2025 Item 10 Requires:**
>
> "Important changes to the trial after it commenced including any outcomes or analyses that were not prespecified, with reason"

**Example Statement:**

> "The following changes were made to the original protocol (registered January 2023, [ClinicalTrials.gov](http://ClinicalTrials.gov) NCT12345678): (1) The secondary outcome 'sleep quality' (Pittsburgh Sleep Quality Index) was added in March 2023 after participant feedback indicated sleep was a key concern. This was pre-specified before data analysis began. (2) The planned 12-month follow-up was reduced to 6 months due to COVID-19 restrictions limiting in-person visits. (3) We conducted an unplanned exploratory analysis examining intervention effects by baseline anxiety severity; this should be considered hypothesis-generating."</td>
>

---

## 2.5 Tools for Reporting Compliance

### [Penelope.ai](http://Penelope.ai)  -  Automated Manuscript Checking

**What It Does:**

[Penelope.ai](http://Penelope.ai) is an automated manuscript checker that scans submissions for compliance with journal requirements and reporting guidelines.

**Features:**

- **30+ automated checks** covering: ethical approval sections, conflict of interest statements, data sharing statements, funding sections, abstract structure (CONSORT/PRISMA format detection), reference formatting, figure/table citations, word count limits
- **Reporting guideline integration:** Works with EQUATOR GoodReports to identify appropriate checklists
- **Publishing platform integration:** Available for journals using Manuscript Manager; waitlist for Editorial Manager and ScholarOne

> **Access [Penelope.ai](http://Penelope.ai):**
>
> Website: [https://www.penelope.ai/](https://www.penelope.ai/)
>
> Pricing: £0.80–£1.50 per submission for journals (institutional subscriptions)
>
> Authors can use for free through participating journals
>
> **Evidence:** A pilot study with BMJ Open found that authors who used Penelope were **more likely to include reporting checklists** with their submissions compared to those who didn't.

### [GoodReports.org](http://GoodReports.org)  -  EQUATOR Reporting Guideline Finder and Validator

**What It Does:**

GoodReports is an EQUATOR Network tool that helps authors find, complete, and validate reporting checklists.

**Key Features:**

1. **Reporting Guideline Wizard:** Answer questions about your study → Get guideline recommendation
2. **Online/Downloadable Checklists:** 16 most common guidelines available for completion
3. **Validation Tool:** Checks checklist completion before submission
4. **Linked Explanations:** Each checklist item links to examples and explanations from E&E documents
5. **Copyright-Free Access:** Secured licenses for free online access to major checklists

> **Access GoodReports:**
>
> Website: [https://www.goodreports.org/](https://www.goodreports.org/)
>
> Free to use for authors and journals
>
> Integration with [Penelope.ai](http://Penelope.ai) for automated checking
>
> **Validation Study:** Researchers validated the GoodReports wizard against expert judgment and found agreement in **81% of cases** where a suitable checklist existed.

### COBWEB (Completeness of Reporting) Tool

**Purpose:** Assesses reporting completeness for specific study types by checking adherence to multiple reporting guidelines simultaneously.

### Writefull  -  AI Writing Assistant with Reporting Features

**Features:**

- AI-powered writing suggestions
- Checks for common omissions in methods/results
- Language editing tailored to scientific writing
- Integrates with Word and Overleaf

### Flow Diagram Generators

**CONSORT Flow Diagram:**

- **R Package:** `consort` package  -  automatically generates diagrams from data.frame, outputs to grid or Graphviz format
- Example code: `consort_plot(data, orders, side_box)`

**PRISMA Flow Diagram:**

- **Shiny App:** [https://www.eshackathon.org/software/PRISMA2020.html](https://www.eshackathon.org/software/PRISMA2020.html)  -  point-and-click interface, export to PDF, PNG, or editable formats, automatically formats per PRISMA 2020 specifications
- **PRISMA Flow Diagram Generator (BetterEvaluation):** Free online tool

### Journal-Specific Tools

**PLOS Submission System:**

Integrated checklist requirements for all submissions. Author must complete and upload checklist before submission allowed.

**BMJ Author Hub:**

Reporting checklists automatically populated from submission metadata. Author reviews and completes during submission process.

**Nature Research:**

Life Sciences Reporting Summary for biology manuscripts. Covers experimental design, statistics, data availability.

---

## 2.6 Creating Discipline-Specific Reporting Templates

### Strategy 1: Adapt Existing Guidelines to Your Context

**Steps:**

1. **Select base guideline** closest to your research (e.g., CONSORT for trial, SRQR for qualitative)
2. **Add discipline-specific elements:**
    - Chemistry: Add synthesis details, characterization data requirements
    - Computing: Add computational environment, hyperparameters
    - Criminology: Add sensitive data handling, policy relevance
3. **Document adaptation:** Create supplementary checklist noting added/modified items

**Example: Adapted Checklist for Computational Linguistics**

Based on SRQR (21 items), add: corpus specifications (size, composition, representativeness, version/date), computational methods (software, versions, parameters, preprocessing steps), annotation procedures (inter-annotator reliability if applicable), code availability (repository link, license, documentation).

### Strategy 2: Lab/Group Protocol Integration

**Create a "Before Submission" Checklist:**

- Integrate reporting items into your lab's standard operating procedures
- Example: Before any manuscript is submitted, PI reviews checklist completion
- Use project management tools (Notion, Trello, Asana) to track checklist items throughout research process

> **Template: Pre-Submission Reporting Checklist**
>
> **Metadata:**
>
> - [ ]  Identify appropriate reporting guideline(s) using EQUATOR wizard
> - [ ]  Download and save checklist(s) to project folder
> - [ ]  Assign team member responsible for checklist completion
>
> **During Writing:**
>
> - [ ]  Methods section drafted with reporting guideline open side-by-side
> - [ ]  Results section includes all pre-specified outcomes
> - [ ]  Flow diagram created and exported
> - [ ]  Supplementary materials organized
>
> **Before Submission:**
>
> - [ ]  Complete reporting checklist with page numbers
> - [ ]  Upload checklist to journal (if required)
> - [ ]  Run manuscript through [Penelope.ai](http://Penelope.ai) (if available)
> - [ ]  Cross-check protocol vs. manuscript for consistency
> - [ ]  Verify all data/code availability statements accurate
>
> **PI Final Check:**
>
> - [ ]  PI reviews checklist for completeness
> - [ ]  Co-authors approve checklist
> - [ ]  Checklist archived with manuscript files

### Strategy 3: Transparency Report Card

Create a **one-page summary** that accompanies any manuscript (internally or for submission) highlighting transparency practices:

> **Template: Transparency Report Card  -  [Manuscript Title]**
>
> **Pre-registration:**
>
> - [ ]  Study pre-registered: [Registry, ID, Date]
> - [ ]  Protocol publicly available: [URL]
> - [ ]  Analysis plan pre-specified: [URL or "See protocol"]
>
> **Reporting:**
>
> - [ ]  Reporting guideline used: [CONSORT 2025, STROBE, SRQR, etc.]
> - [ ]  Completed checklist: [Attached / Available upon request]
> - [ ]  Deviations from protocol: [None / Described on p. XX]
>
> **Data Availability:**
>
> - [ ]  Raw data available: [Repository, DOI]
> - [ ]  Analysis code available: [GitHub, Zenodo, etc.]
> - [ ]  Materials available: [OSF, Supplementary, Upon request]
>
> **Reproducibility:**
>
> - [ ]  Computational environment documented: [Yes / N/A]
> - [ ]  Random seed reported: [Yes / N/A]
> - [ ]  All measures/stimuli described or shared: [Yes]

---

## 2.7 Hands-On Activities

### Activity 1: Guideline Scavenger Hunt

**Objective:** Practice using EQUATOR Network to find appropriate guidelines

**Instructions:**

1. Open [https://www.equator-network.org/](https://www.equator-network.org/) on your device
2. Use the Guideline Wizard to find the reporting guideline for YOUR current research project
3. Answer in shared document:
    - What is your study design?
    - Which guideline(s) did the wizard recommend?
    - How many checklist items does it have?
    - Does an extension exist for your specific context (e.g., pilot study, specific intervention type)?

**Debrief (Group Discussion):**

- Share findings: What guideline did you identify?
- Were you surprised by any recommendations?
- Did multiple guidelines apply?

---

### Activity 2: Reporting Audit of Your Own Work

**Objective:** Identify gaps in your own reporting practices

**Instructions:**

1. **Select a manuscript:**
    - Option A: A published paper you authored
    - Option B: A manuscript currently in preparation
2. **Download the appropriate reporting checklist** for that study (from EQUATOR or GoodReports)
3. **Audit your manuscript against the checklist:**
    - For each item: Check if it's reported in your manuscript
    - Note the page/paragraph where it appears
    - Mark items as: ✓ Fully reported, ⚠ Partially reported, ✗ Not reported
4. **Record findings:**
    - Total items: ___
    - Fully reported: ___
    - Partially reported: ___
    - Not reported: ___
    - **Three most commonly missing elements in your manuscript:**
        1.

        ---

        1.

        ---

        1.

        ---


**Individual Reflection Questions:**

- Which items were **hardest to address**? Why?
- Which missing items would require **going back to the original data** to complete?
- Which missing items could be added **right now** with information you have?

**Debrief (Pair-Share → Large Group):**

- Share your "top 3 missing elements" with a partner
- Discuss: Are there common patterns across disciplines?
- Large group: What are the most frequently omitted items?

---

### Activity 3: Methods Rewrite Workshop

**Objective:** Practice transforming poor reporting into transparent reporting

**Instructions:**

1. **Read the "before" methods paragraph** provided below (projected on screen)
2. **Identify what's missing** according to reporting guidelines
3. **Rewrite the paragraph** to meet reporting standards
4. **Compare your version** with a partner
5. **Group debrief:** Review an exemplar transparent version

**Example "Before" Paragraph (Generic  -  Psychology Study):**

> "We recruited 40 undergraduate students for this study. Participants completed a memory task under two conditions: with and without background music. We analyzed the data using a t-test. Results showed that memory was better without music (p < .05)."
>

**What's Missing?**

Eligibility criteria, recruitment method, sample size justification, study design (within- or between-subjects?), randomization (if between-subjects) or counterbalancing (if within-subjects), detailed task description, outcome measure specification, descriptive statistics (M, SD), effect size and confidence interval.

**Exemplar "After" Paragraph:**

> "We recruited 40 undergraduate students (ages 18-22, 62% female) enrolled in introductory psychology courses at [University] via the SONA research participation system. Eligibility criteria included normal or corrected-to-normal vision, no self-reported hearing impairment, and English as primary language. This sample size was determined via power analysis (G*Power 3.1) to detect a medium effect size (Cohen's d = 0.50) with 80% power at α = .05 for a within-subjects design."
>

> "Participants completed a within-subjects memory task with two conditions (music vs. silence), counterbalanced using a Latin square design to control for order effects. In each condition, participants studied 20 concrete nouns (4-6 letters, presented 2 seconds each) and immediately completed a free recall test (2 minutes). The music condition used instrumental classical music (Bach, Goldberg Variations) played at 60 dB. The primary outcome was number of words correctly recalled (possible range: 0-20)."
>

> "Data were analyzed using a paired-samples t-test. Memory performance was significantly better in the silence condition (M = 12.4, SD = 3.2) compared to the music condition (M = 10.1, SD = 3.8), t(39) = 2.85, p = .007, Cohen's d = 0.45, 95% CI [0.13, 0.77]. All analyses were conducted in R (version 4.2.0)."
>

**Discipline-Specific Variants:**

For different disciplines, provide analogous "before" paragraphs: Chemistry (synthesis procedure lacking detail), Computing (model evaluation without hyperparameters), Criminology (survey sampling without methodology), Modern Languages (corpus analysis without corpus specifications).

---

## 📚 Resources & Materials

### Essential Resources

> **📄 Reporting Standards for Research in Psychology: Why Do We Need Them? What Might They Be?**
>
> *[file: Reporting Standards for Research in Psychology.pdf - see Notion meeting page]*
>
> APA Publications and Communications Board Working Group on Journal Article Reporting Standards. (2008). Reporting standards for research in psychology: Why do we need them? What might they be? *American Psychologist*, 63(9), 839–851. [https://doi.org/10.1037/0003-066X.63.9.839](https://doi.org/10.1037/0003-066X.63.9.839)
>
> **📄Reporting Standards for Quantitative Research in Psychology**
>
> *[file: Journal Article Reporting Standards for Quantitative Research in Psycholo.pdf - see Notion meeting page]*
>
> Appelbaum, M., Cooper, H., Kline, R. B., Mayo-Wilson, E., Nezu, A. M., & Rao, S. M. (2018). Journal article reporting standards for quantitative research in psychology: The APA Publications and Communications Board Task Force report. *American Psychologist*, 73(1), 3–25. [https://doi.org/10.1037/amp0000191](https://doi.org/10.1037/amp0000191)
>
> **📄 Reporting Standards for Qualitative Primary, Qualitative Meta-Analytic, and Mixed Methods Research in Psychology**
>
> *[file: Journal Article Reporting Standards for Qualitative Primary, Qualitative Meta-Analytic, and Mixed Methods Research in Psychology.pdf - see Notion meeting page]*
>
> Levitt, H. M., Bamberg, M., Creswell, J. W., Frost, D. M., Josselson, R., & Suárez-Orozco, C. (2018). Journal article reporting standards for qualitative primary, qualitative meta-analytic, and mixed methods research in psychology: The APA Publications and Communications Board Task Force report. *American Psychologist*, 73(1), 26–46. [https://doi.org/10.1037/amp0000151](https://doi.org/10.1037/amp0000151)
>
> ---
>
> **EQUATOR Network**
>
> [https://www.equator-network.org/](https://www.equator-network.org/)
>
> Comprehensive library of 500+ reporting guidelines with search tools and training materials
>
> **CONSORT 2025 Statement**
>
> [https://www.consort-spirit.org/](https://www.consort-spirit.org/)
>
> Updated checklist, flow diagram template, and explanation & elaboration document
>
> **PRISMA 2020 Statement**
>
> [https://www.prisma-statement.org/](https://www.prisma-statement.org/)
>
> 27-item checklist, flow diagram generator, and E&E document
>
> [**GoodReports.org**](http://GoodReports.org)
>
> [https://www.goodreports.org/](https://www.goodreports.org/)
>
> Interactive guideline finder and checklist validator

### Tools and Templates

> [**Penelope.ai](http://Penelope.ai)  -  Automated Manuscript Checker**
>
> [https://www.penelope.ai/](https://www.penelope.ai/)
>
> Checks manuscripts for reporting guideline compliance and journal requirements
>
> **PRISMA Flow Diagram Generator (Shiny App)**
>
> [https://www.eshackathon.org/software/PRISMA2020.html](https://www.eshackathon.org/software/PRISMA2020.html)
>
> Free interactive tool for creating PRISMA flow diagrams
>
> **CONSORT Flow Diagram R Package**
>
> CRAN package: `consort`
>
> Automated CONSORT diagram generation from data
>
> **STROBE Statement**
>
> [https://www.strobe-statement.org/](https://www.strobe-statement.org/)
>
> 22-item checklist for observational studies
>
> **ARRIVE 2.0 Guidelines**
>
> [https://arriveguidelines.org/](https://arriveguidelines.org/)
>
> Essential 10 + Recommended Set for animal research

### Qualitative Reporting Guidelines

> **SRQR Checklist**
>
> 21-item Standards for Reporting Qualitative Research
>
> Available: [https://academic.oup.com/DocumentLibrary/ACN/SRQR%20Guidelines%20Checklist.doc](https://academic.oup.com/DocumentLibrary/ACN/SRQR%20Guidelines%20Checklist.doc)
>
> **COREQ Checklist**
>
> 32-item checklist for interviews and focus groups
>
> Available: *[file: https://onlinelibrary.wiley.com/pb-assets/assets/17416612/COREQ_Checklist-1556513515737.pdf - see Notion meeting page]*
>
> **APA Style JARS**
>
> [https://apastyle.apa.org/jars](https://apastyle.apa.org/jars)
>
> Comprehensive reporting standards for psychology (quantitative, qualitative, mixed methods)

### Discipline-Specific Resources

> **TREND Statement (Behavioral Interventions)**
>
> [https://www.cdc.gov/hivpartners/php/trend-statement/index.html](https://www.cdc.gov/hivpartners/php/trend-statement/index.html)
>
> 22-item checklist for non-randomized behavioral/public health interventions
>
> **CARE Guidelines (Case Reports)**
>
> [https://www.care-statement.org/](https://www.care-statement.org/)
>
> 13-item checklist for clinical case reports
>
> **STARD 2015 (Diagnostic Accuracy)**
>
> 30-item checklist for diagnostic test accuracy studies
>
> Available via EQUATOR Network
>
> **ACM SIGCHI Policies**
>
> [https://sigchi.org/about/policies/](https://sigchi.org/about/policies/)
>
> Submission, review, and transparency guidelines for HCI research

---

## 💬 Discussion Topics

### Topic: Qualitative Reporting Standards  -  Helpful or Constraining?

**Question:** Do standardized checklists like SRQR and COREQ impose positivist frameworks on interpretive research?

**Discussion Points:**

- Transparency vs. epistemological fit
- Flexibility within reporting guidelines
- Do checklists improve rigor or stifle creativity?
- Can interpretive research be "transparent" in the same way as quantitative?

### Topic: The Future of Automated Reporting Tools

**Question:** Can AI and automation solve the reporting problem?

**Discussion Points:**

- Promise of tools like [Penelope.ai](http://Penelope.ai) and GoodReports
- Limitations: automation can check format but not quality of content
- Could AI extract reporting elements from methods sections automatically?
- Ethical concerns: over-reliance on automation

---

## ➡️ Next Session Preview: Meeting 6  -  Open Access Publishing & Preprints

**Date:** March 2026 (Last week poll?)

**Presenters:** [To be announced]

### Topics to be Covered:

- Open access models: Gold, Green, Diamond, Bronze
- Preprint servers: bioRxiv, medRxiv, PsyArXiv, arXiv, ChemRxiv
- Journal licensing and author rights
- Article Processing Charges (APCs) and funding strategies
- Predatory journals: identification and avoidance
- Open peer review and post-publication review
- Altmetrics and measuring research impact beyond citations

---

## 🙋 Volunteer Call

**We need presenters for Meeting 6 (March 2026)!**

If you have experience with open access publishing, preprints, or navigating journal policies, please consider co-leading next month's session.

---

## Key Takeaways

> 📌 **Transparent reporting is not optional**  -  it's essential for evidence synthesis, replication, and clinical/policy translation. Approximately 85% of research investment is wasted, with incomplete reporting a major contributor.
>
> 📌 **The EQUATOR Network is your starting point**  -  Over 500 reporting guidelines organized by study design. Use the wizard to find your guideline.
>
> 📌 **CONSORT 2025 and PRISMA 2020** are the gold standards for trials and systematic reviews, with major updates emphasizing open science.
>
> 📌 **Qualitative research has robust reporting standards**  -  Use SRQR (21 items, all qualitative designs) or COREQ (32 items, interviews/focus groups).
>
> 📌 **Selective outcome reporting undermines science**  -  Report ALL pre-specified outcomes, including null and negative findings, with complete statistics and effect sizes.
>
> 📌 **Tools can help but not replace judgment**  -  [Penelope.ai](http://Penelope.ai), GoodReports, and flow diagram generators streamline compliance checking, but thoughtful reporting requires human insight.
>
> 📌 **Discipline-specific adaptations are necessary**  -  Psychology (APA JARS), Chemistry (ACS standards), Computing (ACM transparency), Criminology (Campbell), Modern Languages (SRQR) all have distinct reporting needs.
>
> 📌 **Integration into workflow is key**  -  Use reporting guidelines as **writing templates**, not post-hoc checklists. Build them into lab protocols and pre-submission procedures.

---

## References and Further Reading

**Foundational Papers:**

- Chalmers, I., & Glasziou, P. (2009). Avoidable waste in the production and reporting of research evidence. *Lancet*, 374(9683), 86-89.
- Glasziou, P., Altman, D. G., Bossuyt, P., Boutron, I., Clarke, M., Julious, S., ... & Wager, E. (2014). Reducing waste from incomplete or unusable reports of biomedical research. *Lancet*, 383(9913), 267-276.

**Major Reporting Guidelines:**

- Schulz, K. F., Altman, D. G., & Moher, D. (2025). CONSORT 2025 statement: Updated guideline for reporting randomised trials. *BMJ*, 381, e081123.
- Page, M. J., McKenzie, J. E., Bossuyt, P. M., et al. (2021). The PRISMA 2020 statement: An updated guideline for reporting systematic reviews. *BMJ*, 372, n71.
- von Elm, E., Altman, D. G., Egger, M., et al. (2007). The Strengthening the Reporting of Observational Studies in Epidemiology (STROBE) statement. *PLoS Medicine*, 4(10), e296.
- Percie du Sert, N., Hurst, V., Ahluwalia, A., et al. (2020). The ARRIVE guidelines 2.0: Updated guidelines for reporting animal research. *PLOS Biology*, 18(7), e3000411.
- O'Brien, B. C., Harris, I. B., Beckman, T. J., Reed, D. A., & Cook, D. A. (2014). Standards for reporting qualitative research: A synthesis of recommendations. *Academic Medicine*, 89(9), 1245-1251.
- Tong, A., Sainsbury, P., & Craig, J. (2007). Consolidated criteria for reporting qualitative research (COREQ): A 32-item checklist for interviews and focus groups. *International Journal for Quality in Health Care*, 19(6), 349-357.

**Meta-Research on Reporting Quality:**

- Kirkham, J. J., Dwan, K. M., Altman, D. G., et al. (2010). The impact of outcome reporting bias in randomised controlled trials on a cohort of systematic reviews. *BMJ*, 340, c365.
- Chan, A. W., Hróbjartsson, A., Haahr, M. T., Gøtzsche, P. C., & Altman, D. G. (2004). Empirical evidence for selective reporting of outcomes in randomized trials. *JAMA*, 291(20), 2457-2465.

**Tools and Resources:**

- Hopewell, S., Clarke, M., Moher, D., et al. (2021). GoodReports: Developing a website to help health researchers find and use reporting guidelines. *BMJ Open*, 11(10), e048865.

---

---

*Previous: [Reproducible Analysis Workflows](04-reproducible-analysis.md)* - *Next: [Open Access Publishing & Preprints](06-open-access.md)*

*Want to contribute? See [CONTRIBUTING.md](../CONTRIBUTING.md).*
