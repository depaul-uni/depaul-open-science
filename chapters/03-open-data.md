# Chapter 3 - Open Data Sharing & Management

**Lead author:** Vahid Alizadeh
**Source meeting:** Meeting 3 (December 19, 2025)
**Status:** *adapted from the SLC's live Notion meeting page; minor formatting cleanup applied*

---


**Date:** December 19, 2025

**Presenter:** Vahid Alizadeh

**Learning Community:** Open Science in Practice: Tools and Workflows for Transparent, Reproducible Research

---

## 🎯 Meeting Objectives

By the end of this session, participants will:

- **Understand** the FAIR principles (Findable, Accessible, Interoperable, Reusable) and their importance in modern research
- **Navigate** data repositories appropriate for their discipline and data types
- **Develop** comprehensive data management and sharing strategies aligned with funder requirements
- **Apply** metadata standards and documentation best practices to their research data
- **Design** privacy-preserving approaches for sensitive data while maximizing sharing potential
- **Create** actionable data management plans for ongoing and future projects

---

## 📚 Main Resources and Templates

> ### Essential Core Resources
>
> **FAIR Principles Foundation**
>
> 1. **Wilkinson, M. D., Dumontier, M., Aalbersberg, I. J., et al. (2016)**. The FAIR Guiding Principles for scientific data management and stewardship. *Scientific Data*, 3, 160018. [https://doi.org/10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18)
>     - The foundational paper defining the 15 FAIR principles developed through the 2014 Lorentz Workshop. Essential reading for understanding the theoretical basis of data sharing standards.
>
>         *[file: The FAIR Guiding Principles for scientific data management and stewardship.pdf - see Notion meeting page]*
>
> 2. **GO FAIR Foundation Implementation Networks** - [https://www.go-fair.org/](https://www.go-fair.org/)
>     - Discipline-specific guidance and tools for implementing FAIR principles. Coordinates Implementation Networks across biology, chemistry, social sciences, and more.
> 3. **Research Data Alliance (RDA) FAIR Data Maturity Model** - [https://doi.org/10.15497/rda00050](https://doi.org/10.15497/rda00050)
>     - Developed by 200+ experts from 20+ countries. Provides 17 indicators and priority levels for assessing FAIR compliance. The "lingua franca" for comparing FAIR assessments across repositories.
>
>         *[file: FAIR Data Maturity Model_ specification and guidelines_v1.00.pdf - see Notion meeting page]*
>
>
> **Funder Requirements & Data Management Planning**
>
> 1. **NIH Data Management and Sharing Policy** - [https://sharing.nih.gov/](https://sharing.nih.gov/)
>     - Effective January 25, 2023: ALL NIH-funded research generating scientific data requires 2-page Data Management and Sharing Plan (DMSP). Non-compliance may affect future funding eligibility.
> 2. **NSF Data Management Plan Guidelines** - [https://nsf.gov/funding/data-management-plan](https://nsf.gov/funding/data-management-plan)
>     - Required since 2011. Directorate-specific requirements vary (SBE emphasizes human subjects protection; BIO focuses on community repositories and FAIR).
> 3. **Horizon Europe Data Management Plan Requirements** - [https://rea.ec.europa.eu/open-science_en](https://rea.ec.europa.eu/open-science_en)
>     - Mandatory data management plans within 6 months. Principle: "as open as possible, as closed as necessary." Immediate open access to publications (no embargo); Creative Commons CC-BY or CC0 licensing required for metadata.
>
> **Assessment and Guidance Tools**
>
> 1.  **How to be FAIR with your data (2022)** - [https://doi.org/10.17875/gup2022-1915](https://doi.org/10.17875/gup2022-1915)
>     - Comprehensive training materials including lesson plans, competence frameworks, and implementation guidance. Available as GitBook at [fairsfair.gitbook.io](http://fairsfair.gitbook.io)
>
>         *[file: FAIRsFAIR Teaching Handbook.pdf - see Notion meeting page]*
>
> 2. **Cornell Data Services README Template** - [https://data.research.cornell.edu/data-management/sharing/readme](https://data.research.cornell.edu/data-management/sharing/readme)
>     - Industry-standard template for documenting datasets. Covers general information, sharing/access, data overview, methodological information, and data-specific documentation.

> ### Data Management Plan Templates
>
> **DMP Tool Platforms**
>
> - **DMPTool** - [https://dmptool.org/](https://dmptool.org/): US-focused with templates for NIH, NSF, DOE, and NEH; institutional customization available
> - **DMPonline** - [https://dmponline.dcc.ac.uk/](https://dmponline.dcc.ac.uk/): UK-focused; supports all UKRI councils plus Horizon Europe
> - **ARGOS** - [https://argos.openaire.eu/](https://argos.openaire.eu/): European platform; produces machine-actionable DMPs following RDA Common Standard
> - **Data Stewardship Wizard** - [https://ds-wizard.org/](https://ds-wizard.org/): Features smart questionnaires with built-in FAIR metrics indicators; developed by ELIXIR
>
> **Key Template Elements**
>
> - Data types and volume estimates
> - Related tools, software, and code
> - Metadata standards and documentation
> - Preservation timelines and formats
> - Access considerations and restrictions
> - Oversight responsibilities and workflows

> ### Supplementary Resources
>
> **1. Recent Implementation Reviews**
>
> - **Kobayashi, M., & Croft, W. (2025)**. Research data management and FAIR compliance through popular research data repositories: an exploratory study. *Data Technology and Applications*, 59(2). Evaluates Figshare, Zenodo, Dataverse, and Dryad against FAIR principles - finding Figshare highest (58.3%), but all repositories show gaps in access metrics and licensing features.
>     - [https://www.emerald.com/insight/content/doi/10.1108/DTA-12-2022-0477/full/html](https://www.emerald.com/insight/content/doi/10.1108/DTA-12-2022-0477/full/html)
> - **Pichler, F., & Sorensen, D. O. (2024)**. Initiatives, Concepts, and Implementation Practices of the Findable, Accessible, Interoperable, and Reusable Data Principles in Health Data Stewardship: Scoping Review. *JMIR Medical Education*, 10. Comprehensive scoping review identifying projects, tools, and workflows for FAIRifying health research data since COVID-19 pandemic.
>     - [https://doi.org/10.2196/22505](https://doi.org/10.2196/22505)
>
> **2. Practical Implementation Guides**
>
> - **Hardwicke, T. E., et al. (2024)**. Open science interventions to improve reproducibility and replicability. *Royal Society Open Science*. Systematic evaluation of intervention effectiveness with evidence-based implementation recommendations.
>     - [https://royalsocietypublishing.org/doi/10.1098/rsos.242057](https://royalsocietypublishing.org/doi/10.1098/rsos.242057)
> - **NFDI4Chem (2025)**. Proposal for 2025-2030: Vision of all chemists publishing FAIR data. *RIO Journal*. Details integrated lab-to-repository workflows using electronic lab notebooks (ELNs) and federated repositories.
>     - [https://riojournal.com/article/177037/](https://riojournal.com/article/177037/)
>
> **3. Discipline-Specific Standards**
>
> - **Nature Scientific Data Recommended Repositories** - Curated list of 100+ discipline-specific repositories across biomedics, chemistry, earth sciences, social sciences, and more
> - **PLOS ONE Recommended Repositories** - [https://journals.plos.org/plosone/s/recommended-repositories](https://journals.plos.org/plosone/s/recommended-repositories)
> - **EQUATOR Network** - [https://www.equator-network.org/](https://www.equator-network.org/): Comprehensive database of reporting guidelines by discipline

---

## 🔑 The FAIR Principles: From Theory to Practice

### Understanding the Four Pillars

**Findability (F1-F4)**: Ensuring data are discoverable

- **F1**: Data are assigned globally unique persistent identifiers (PIDs) - typically DOIs
- **F2**: Data are described with rich metadata using controlled vocabularies
- **F3**: Metadata explicitly include the identifier(s) that they describe
- **F4**: Metadata are registered or indexed in searchable resources (registries, search engines)

**Accessibility (A1-A2)**: Enabling data retrieval

- **A1**: Data are retrievable by their identifier using standardized communication protocols (HTTP, FTP) that are preferably free and universally implementable
- **A1.1**: The protocol allows for an authentication and authorization procedure (where necessary)
- **A1.2**: The protocol allows for free access when appropriate
- **A2**: Metadata are accessible even when data are no longer available

**Interoperability (I1-I3)**: Facilitating data integration and analysis

- **I1**: Data use a formal, accessible, shared, and broadly applicable language for knowledge representation
- **I2**: Data use vocabularies that follow FAIR principles
- **I3**: Data include qualified references to other data

**Reusability (R1-R1.3)**: Supporting future research and applications

- **R1**: Data are richly described with a plurality of accurate and relevant attributes
- **R1.1**: Data are released with a clear and accessible data usage license
- **R1.2**: Data are associated with detailed provenance information (who, what, when, how, why)
- **R1.3**: Data meet domain-relevant community standards

### The Machine-Readability Distinction

Critically, FAIR emphasizes **machine-actionability** alongside human readability. This distinction separates FAIR from traditional documentation practices:

- Data must be discoverable by **automated search and retrieval systems**, not just human browsing
- Metadata must use **structured, standardized formats** that computers can parse and interpret
- Persistent identifiers enable **automatic linkages** across datasets and publications
- Standardized vocabularies permit **cross-dataset integration** without manual mapping

### Assessment Tools for Self-Evaluation

**F-UJI** ([f-uji.net](http://f-uji.net))

- Automated REST API-based assessment tool
- Evaluates datasets against 16 FAIRsFAIR metrics
- Provides automated reports and improvement recommendations
- No account required; paste dataset URL or metadata file

**FAIRshake** ([fairshake.cloud](http://fairshake.cloud))

- Community-driven rubrics and visual assessment
- Creates "FAIR insignias" for websites and publications
- Enables collaborative evaluation and expertise crowd-sourcing
- Metric scores reflect community assessment, not just technical compliance

---

## 🏢 Navigating Data Repositories: Selecting the Right Solution

### Decision Framework for Repository Selection

> **Step 1: Check for Discipline-Specific Repositories**
>
> Best for: Community discovery, specialized curation, domain-relevant standards
>
> If one exists and accepts your data type → Use it as primary repository

> **Step 2: Check for Institutional Repositories**
>
> Best for: Alignment with institutional policies, IT support integration
>
> If your institution has one accepting datasets → Consider institutional plus discipline-specific

> **Step 3: Consider Data Sensitivity**
>
> If data contain personally identifiable or sensitive information → Controlled-access repositories
>
> If data are fully open → General or discipline-specific repositories

> **Step 4: Fall Back to General Repositories**
>
> Best for: Interdisciplinary projects, rare data types
>
> If no suitable specialized repository → General repositories (Zenodo, Dryad, Dataverse)

### General-Purpose Repositories Comparison

**Zenodo** ([zenodo.org](http://zenodo.org))

- Operated by CERN with OpenAIRE support
- Unlimited free storage (50GB per dataset)
- Versioning with DOI assignment for each version
- GitHub integration for code archiving
- Best for: Interdisciplinary projects, code repositories, multimedia
- Use case: Ideal when spanning multiple disciplines or no discipline-specific option exists

**Dryad** ([datadryad.org](http://datadryad.org))

- Professional data curation included in fee ($120 for ≤20GB)
- Many publishers cover deposit costs through partnerships
- Requires CC0 licensing (most permissive)
- Strong FAIR compliance
- Best for: Published datasets, curated collections, disciplinary breadth
- Use case: Data accompanying journal articles where publisher covers fees

**Harvard Dataverse** ([dataverse.harvard.edu](http://dataverse.harvard.edu))

- Open-source software for institutional deployment
- Strong FAIR compliance built-in
- Supports multiple metadata formats (DataCite, Dublin Core, DDI, EAS)
- Can be installed locally by institutions
- Best for: Institutional implementations, customized metadata
- Use case: Universities seeking local control and long-term preservation

**Open Science Framework (OSF)** ([osf.io](http://osf.io))

- Project management platform with data sharing
- Integration with GitHub, Dropbox, OneDrive
- Preregistration capabilities alongside data storage
- Best for: Project management, collaborative workflows, preregistered studies
- Use case: Multi-component research projects requiring version control and collaboration

**Figshare** ([figshare.com](http://figshare.com))

- Highest FAIR compliance rating in recent evaluation (58.3%)
- Strong metadata and versioning
- Multimedia support
- Best for: Diverse data types, multimedia, visual research
- Use case: When comprehensive FAIR features are priority

### Discipline-Specific Repositories

**Psychology & Social Sciences**

- **ICPSR (Inter-university Consortium for Political and Social Research)** - [https://www.icpsr.umich.edu/](https://www.icpsr.umich.edu/): World's largest social science archive with professional curation
- **openICPSR** - Free self-deposit up to 30GB
- **UK Data Service** - [https://www.ukdataservice.ac.uk/](https://www.ukdataservice.ac.uk/): Largest UK social science collection
- **Qualitative Data Repository (QDR)** - [https://qdr.syr.edu/](https://qdr.syr.edu/): Specializes in qualitative and mixed-methods research

**Chemistry**

- **Cambridge Structural Database** - [https://www.ccdc.cam.ac.uk/](https://www.ccdc.cam.ac.uk/): Mandatory for crystallographic data (CoreTrustSeal certified)
- **PubChem** - [https://pubchem.ncbi.nlm.nih.gov/](https://pubchem.ncbi.nlm.nih.gov/): 235+ million substances freely accessible
- **ChEMBL** - [https://www.ebi.ac.uk/chembl](https://www.ebi.ac.uk/chembl): Drug-like molecules and bioactivity data
- **NFDI4Chem** - [https://www.nfdi4chem.de/](https://www.nfdi4chem.de/): Chemistry-specific data management infrastructure with templates and ELN integration

**Biology & Biomedics**

- **GEO (Gene Expression Omnibus)** - Microarray and high-throughput gene expression data
- **GenBank** - DNA and protein sequences
- **BioStudies** - Cross-disciplinary biological research data
- **NCI Cancer Research Data Commons** - [https://cbioportal.org/](https://cbioportal.org/): Integrates genomic, proteomic, imaging, clinical cancer data

**Criminology**

- **National Archive of Criminal Justice Data (NACJD)** - [https://www.icpsr.umich.edu/nacjd/](https://www.icpsr.umich.edu/nacjd/): 2,700+ curated studies including National Crime Victimization Survey and FBI Uniform Crime Reports

**Modern Languages & Linguistics**

- **CLARIN** - [https://www.clarin.eu/](https://www.clarin.eu/): European Research Infrastructure Consortium; federated search across 20+ member countries
- **Linguistic Data Consortium** - [https://www.ldc.upenn.edu/](https://www.ldc.upenn.edu/): Gold-standard corpora through institutional membership

**Computing & Data Science**

- **Papers with Code** - [https://paperswithcode.com/](https://paperswithcode.com/): Links 3,200+ datasets to papers and code implementations
- **UCI Machine Learning Repository** - [https://archive.ics.uci.edu/](https://archive.ics.uci.edu/): Classic benchmark datasets
- **GitHub + Zenodo**: Combine for code archiving with DOIs

### Repository Discovery Tools

[**re3data.org**](http://re3data.org) ([https://re3data.org/](https://re3data.org/))

- Indexes 3,000+ repositories worldwide
- Filter by subject, access restrictions, certification status
- Provides detailed metadata about repository features and policies

[**FAIRsharing.org**](http://FAIRsharing.org) ([https://www.fairsharing.org/](https://www.fairsharing.org/))

- Interlinks standards, databases, and policies
- Shows which standards each repository implements
- Enables cross-referencing between data types, standards, and appropriate repositories

---

## 📝 Data Management and Documentation Best Practices

### Creating Effective README Files

The **Cornell Data Services Template** provides the standard structure:

### 1. General Information

- Title of dataset
- Author(s)/Creator(s)
- Date of data collection
- Geographic location (if applicable)
- Funding information and grants
- Data availability and licensing

### 2. Sharing/Access Information

- Licenses and restrictions on use
- Related publications and links
- Recommended citation format
- Relationship to other datasets

### 3. Data & File Overview

- Directory/file structure and organization
- Relationship between files
- File naming conventions and logic
- Individual file descriptions

### 4. Methodological Information

- Data collection methods
- Temporal coverage and frequency
- Geographic coverage
- Processing and quality assurance procedures
- Software and tools used

### 5. Data-Specific Information (per file)

- Variable definitions and units
- Variable names, labels, and question text
- Coded values and their meanings
- Missing data codes and definitions
- Data types and measurement scales
- Summary statistics

### Variable Documentation Standards

**Naming Conventions** (for maximum software compatibility)

- Use **snake_case**: lowercase with underscores, never spaces or special characters
- Example: `health_smoking_status` not `Health_SmokingStatus` or `Health Smoking Status`
- Use descriptive but concise names
- Group related variables with consistent prefixes: `health_*`, `demographics_*`

**Date Formatting**

- Always use **ISO 8601 format**: YYYY-MM-DD
- Enables automatic sorting and machine-readability
- Example: `2025-12-19` not `12/19/2025` or `December 19, 2025`

**Documentation Elements Per Variable**

- Variable name and short label
- Full variable description and measurement question
- Data type (numeric, text, date, boolean)
- Measurement unit (if applicable)
- Range or valid values
- Coded values and their meanings (e.g., 1=Male, 2=Female, 3=Other)
- Missing data codes (e.g., -99=Not applicable, -88=Refused, -77=Don't know)
- Summary statistics (min, max, mean, standard deviation)
- Related variables or dependencies

### File Format Selection for Preservation

**Recommended Preservation Formats**

| Data Type | Preferred Format | Alternative | Avoid |
| --- | --- | --- | --- |
| Tabular data | CSV, TSV | Plain text with delimiter | Excel (.xlsx), binary formats |
| Text documents | PDF/A, TXT | XML | Microsoft Word (.docx) |
| Images | TIFF, PNG | JPEG (for photos) | Proprietary formats |
| Audio | FLAC, WAV | MP3 | Proprietary codecs |
| Video | H.264 in MP4 | FFV1 | Proprietary containers |
| Spreadsheets | CSV (export from spreadsheets) | Parquet (for complex structures) | .xls, .xlsx |
| Code | Plain text (.py, .R, .m) | Language-specific + documentation | Compiled binaries |

**Rationale**: Open, non-proprietary formats ensure long-term accessibility independent of software availability or licensing changes.

### Data Version Control

**Git & GitHub** (for code and small files)

- Standard version control system
- Tracks all changes with commit messages
- Enables collaboration and rollback
- Free hosting on GitHub with public/private options

**DVC (Data Version Control)** ([dvc.org](http://dvc.org))

- Git-like version control for large data files
- Stores data separately from repositories using efficient pointer files
- Tracks versions without duplicating massive files
- Integrates seamlessly with Git workflows

**lakeFS** ([lakefs.io](http://lakefs.io))

- Version control for data lakes
- Git-like interface for data lake management
- Enables atomic transactions and rollbacks
- Best for: Large-scale data management and MLOps workflows

---

## 🔒 Privacy, Consent, and Ethical Data Sharing

### Regulatory Frameworks and Distinctions

**GDPR (European Union)**

- Applies to personal data of EU residents regardless of where processing occurs
- Key distinction: "De-identified" under HIPAA often remains "pseudonymized" under GDPR
- Only data from which individuals cannot be identified **by any means** constitutes "anonymous" data
- GDPR scope: Personal data must be protected; truly anonymous data falls outside GDPR

**HIPAA (US Healthcare)**

- Applies to covered entities and business associates handling protected health information (PHI)
- De-identification requires either: (a) Expert determination that data have low re-identification risk, or (b) Removal of 18 specified identifiers plus knowledge that re-identification is very low
- De-identified data not covered by HIPAA

**Common Rule (US Human Subjects Research)**

- Requires informed consent for research with human subjects
- Covers research with identifiable human data
- IRB approval required for most human subjects research

### De-identification Techniques

**Suppression**: Removing unnecessary identifiers

- Example: Delete exact dates, keep only year
- Reduces specificity to protect individuals

**Pseudonymization**: Replacing identifiers with arbitrary codes

- Example: Replace names/IDs with study codes (ID_001, ID_002)
- Allows data linkage within studies but breaks external linkages
- Note: GDPR considers pseudonymized data still subject to protection (not anonymous)

**Generalization**: Aggregating specific values into categories

- Example: Replace exact ages with age ranges (18-25, 26-35)
- Reduces precision while maintaining analytical utility

**Top/Bottom Coding**: Capping extreme values

- Example: Report age as 90+ for all ages ≥90
- Protects outliers who might be easily identified

**Noise Addition**: Adding random variation

- Example: Add ±1 year to all ages
- Protects individual privacy while maintaining aggregate patterns

**Permutation**: Swapping values between subjects

- Example: Shuffle ages across records
- Breaks direct identifiability links

### Tools and Resources for De-identification

**ARX Data Anonymization Tool** ([arx.deidentifier.org](http://arx.deidentifier.org))

- Open-source, comprehensive de-identification platform
- Supports k-anonymity, l-diversity, t-closeness, differential privacy
- Built-in risk assessment and re-identification likelihood
- User-friendly GUI
- Best for: Comprehensive de-identification workflows

**sdcMicro** (R package)

- Statistical disclosure control for R users
- Multiple de-identification methods
- Integration with R analysis workflows
- Best for: Researchers already using R

### Licensing for Reuse

**Recommended for Research Data**

- **CC0 (Public Domain Dedication)**: Waives all rights, maximum reuse potential. Best for: Most research data.
- **CC-BY (Attribution)**: Requires attribution but allows all uses. Best for: Data where you want attribution but maximum reuse.

**Not Recommended**

- **CC-NC (Non-Commercial)**: Problematic because "commercial" is ambiguously defined (does consulting violate this?)
- **CC-ND (No Derivatives)**: Prevents necessary data transformations and prevents reuse
- **Custom licenses**: Confuse users; standardized licenses preferable

### Data Use Agreements (DUAs) for Controlled Access

**Federal Demonstration Partnership ([thefdp.org](http://thefdp.org))**

- Provides standardized DUA templates used by 200+ institutions

**Key Components**

- Data description and permitted uses
- Security requirements
- Breach notification procedures (typically 10 days)
- Publication rights and restrictions
- Data disposition at study end
- Confidentiality commitments

**Negotiation Considerations**

- DUA negotiation often takes months; start early
- Align with IRB-approved protocols
- Be explicit about secondary uses to avoid future delays
- Include provisions for institutional transitions (staff changes, institution closures)

### Discipline-Specific Sensitivity Challenges

**Psychology**

- Protection from psychological harm
- Vulnerable populations (minors, clinical samples)
- Qualitative data difficult to fully anonymize (verbatim quotes reveal individuals)
- Emotion/mental health status highly sensitive
- Solution: Tiered access, synthetic data generation, qualitative data repositories with confidentiality review

**Criminology**

- Criminal behavior disclosure lacks legal privilege protection unlike attorney-client confidentiality
- Researchers may face subpoena demands for data
- Sensitive organizational/institutional identifiers (which prisons, police departments)
- Solution: NACJD confidentiality review, secure enclaves, limited-access repositories, data destruction procedures

**Social Sciences with Vulnerable Populations**

- Immigration status, financial hardship, discrimination experiences
- Stigmatized identities or behaviors
- Solution: Secure data enclaves (like UK Data Service), multi-layered access requirements

**Biomedical Research**

- Genetic data potential for discrimination
- Clinical trial results sensitive to individual participants
- Solution: Tiered access, external data repositories with governance

---

## 🚀 Implementing Your Data Sharing Strategy

### Pre-Research Phase

1. **Select and Register Your Project**
    - Register on OSF or AsPredicted (if preregistering)
    - Identify potential data repositories for your discipline
    - Document repository requirements in your DMP
2. **Design Consent Forms with Data Sharing**
    - Include explicit language about data sharing
    - Avoid restrictive phrases like "only the research team will access your data"
    - Specify duration of sharing (indefinite, limited term)
    - Example language: "Your data will be de-identified and shared with the scientific community to support research advancement."
3. **Create Your Data Dictionary Before Collection**
    - Develop comprehensive documentation before any data collection
    - Use this as roadmap for instrument design
    - Identify potential identifiers early
    - Establish consistent variable naming and coding

### During Research Phase

1. **Organize Data with Recommended Folder Structure**

    ```
    project_name/
    ├── raw_data/                 (immutable original data)
    │   └── study_baseline_data.csv
    ├── processed_data/           (cleaned, processed versions)
    │   └── study_baseline_processed.csv
    ├── analysis/                 (code and scripts)
    │   ├── analysis_primary.R
    │   └── analysis_sensitivity.R
    ├── documentation/            (README, codebooks, protocols)
    │   ├── [README.md](http://README.md)
    │   ├── data_dictionary.xlsx
    │   └── collection_protocol.pdf
    └── results/                  (figures, tables, outputs)
        ├── figure_1_descriptives.png
        └── table_1_regression.csv
    ```

2. **Apply Consistent Naming Conventions**
    - File names: `YYYY-MM-DD_studyname_version_description.csv`
    - Variable names: `snake_case`
    - Dates: Always ISO 8601 (YYYY-MM-DD)
3. **Version Control Everything**
    - Use Git/GitHub for code
    - Use DVC or Git LFS for large data files
    - Commit frequently with descriptive messages
    - Document major analysis decisions in commit history
4. **Maintain Comprehensive README Files**
    - Update alongside data as it evolves
    - Document any deviations from protocol
    - List all files with descriptions
    - Note special handling requirements (e.g., sensitive identifiers in specific columns)

### Deposit and Sharing Phase

1. **Prepare Metadata**
    - Use DataCite (most common) or discipline-specific standards
    - Include mandatory elements: Title, Creator, Publisher, Publication Year, Resource Type
    - Add 10+ optional descriptors: Subject keywords, spatial coverage, temporal coverage, funder, related publications
2. **De-identify and Secure Data**
    - Use ARX or sdcMicro to assess re-identification risk
    - Apply de-identification techniques
    - Create tiered access versions if appropriate (open + controlled-access)
    - Document de-identification methods in README
3. **Select Repository and Deposit**
    - Primary: Discipline-specific if available
    - Secondary: Institutional repository
    - Tertiary: General repositories (Zenodo, Dryad, Dataverse)
    - Assign CC0 or CC-BY license
    - Set embargo period only if necessary (default: no embargo)
    - Verify FAIR compliance using F-UJI or FAIRshake
4. **Obtain DOI and Share Citation**
    - Document dataset DOI in your publication
    - Use recommended citation format: Creator (Year). Title. Repository. [https://doi.org/](https://doi.org/)...
    - Ensure metadata and data are publicly linked

---

## 📊 Evidence on Data Sharing and FAIR Benefits

### Impact on Research Outcomes

**Citation Advantage**: McKiernan et al. (2016) found that open research practices correlate with:

- Increased citations (multiple studies show 15-50% citation advantages)
- Enhanced media attention and public engagement
- Greater collaboration opportunities
- Improved funding prospects

**Publication Success**: Scheel et al. (2021) found Registered Reports produced null results in 44% of cases versus 96% positive results in standard journals - indicating that FAIR data practices reduce publication bias.

**Reproducibility**: Hardwicke et al. (2024) systematic review found that data sharing enables:

- Independent verification of analyses
- Detection of computational errors
- Identification of unreported findings
- Meta-scientific research on methodology

### Barriers and Current State

State of Open Data 2024 (Springer Nature, Digital Science, Figshare):

- **89% of researchers** make data publicly available
- **73% feel sharing work isn't worth the credit received** (recognition gap is primary barrier)
- **Technical challenges** are NOT the primary barrier
- Researchers need institutional support and career recognition

NIH Data Management and Sharing Policy Initial Data:

- Since January 2023 requirement, compliance steadily increasing
- Most challenges: disciplinary variation, institutional support gaps
- Successful implementations: Genomics (highest compliance), clinical trials
- Slower adoption: Social sciences, qualitative research, confidential data

---

## 🔄 Next Steps for Your Research

### Immediate Actions

- [ ]  Identify discipline-specific repository for your data type
- [ ]  Review funder DMP requirements (NIH, NSF, Horizon Europe)
- [ ]  Assess your current documentation practices against Cornell template
- [ ]  Create or update your data dictionary

### Short-term

- [ ]  Complete Data Management Plan using appropriate tool
- [ ]  Set up version control for your project (Git/GitHub or DVC)
- [ ]  Develop tiered folder structure for new project
- [ ]  Draft data sharing language for next IRB application/protocol amendment

### Medium-term

- [ ]  De-identify and prepare existing datasets for sharing
- [ ]  Deposit one completed dataset to test repository workflow
- [ ]  Obtain community feedback on documentation completeness
- [ ]  Attend repository-specific training if available

### Long-term

- [ ]  Integrate open data sharing into all grant proposals
- [ ]  Build data management into research design phase
- [ ]  Create institutional templates for your lab/group

---

## 🤝 Community Resources and Support

### Training Platforms

- **FOSTER Open Science** - [https://openplato.eu/course/view.php?id=3](https://openplato.eu/course/view.php?id=3): Comprehensive online courses
- **How to FAIR (Denmark)** - [https://howtofair.dk/](https://howtofair.dk/): Interactive tutorial
- **GO FAIR Training Materials** - [https://www.go-fair.org/](https://www.go-fair.org/): Discipline-specific training
- **FORRT** - [https://forrt.org/](https://forrt.org/): Psychology and social sciences focus

### Repository Support

- Most repositories provide: Documentation, webinars, email support
- Example: Harvard Dataverse help desk ([https://support.dataverse.harvard.edu/](https://support.dataverse.harvard.edu/))
- Example: Zenodo guides ([https://guides.zenodo.org/](https://guides.zenodo.org/))

---

> ## Key Takeaways
>
> ✅ **FAIR principles** (Findable, Accessible, Interoperable, Reusable) are now standard requirements from major funders (NIH, NSF, Horizon Europe)
>
> ✅ **Data Management Plans** must address: data types, tools/software, metadata standards, preservation, access, oversight
>
> ✅ **Repository selection** should follow: (1) Discipline-specific first, (2) Institutional second, (3) General third
>
> ✅ **Documentation** is everything: README files, variable dictionaries, and metadata are as important as data itself
>
> ✅ **Privacy protection** and **data sharing** are compatible: Use de-identification, controlled access, and tiered repositories
>
> ✅ **Machine-readability** matters: Standardized formats, controlled vocabularies, and persistent identifiers enable automated reuse
>
> ✅ **Version control** from day one: Organize data systematically to prevent errors and enable tracking
>
> ✅ **Early planning** saves months: Design data sharing into your research from inception, not as afterthought

---

## 🚀 Next Session Preview

### **Meeting 4: Reproducible Analysis Workflows**

**Session Objectives:**

- Master literate programming approaches (R Markdown, Jupyter Notebooks, Quarto)
- Develop version-controlled computational pipelines
- Create fully reproducible analysis workflows
- Implement containerization for computational environments
- Establish peer review processes for analytical code

**Preparation Resources**

- [Knitr/R Markdown Guide]({{https://rmarkdown.rstudio.com/}})
- [Jupyter Notebooks Documentation]({{https://jupyter.org/}})
- [Quarto Publishing System]({{https://quarto.org/}})
- [Docker for Data Science]({{https://www.docker.com/}})

---

> **🙋 Call for January Session Leaders:**
>
> We need volunteers to research and co-present on:
>
> **Next Meeting: January 2026 - Reproducible Analysis Workflows**
>
> **To Volunteer**: Contact facilitator by January 10th

---

---

*Previous: [Pre-registration & Study Planning](02-preregistration.md)* - *Next: [Reproducible Analysis Workflows](04-reproducible-analysis.md)*

*Want to contribute? See [CONTRIBUTING.md](../CONTRIBUTING.md).*
