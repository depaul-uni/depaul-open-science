# Chapter 8 - Open Materials and Collaborative Protocols Sharing

**Lead author:** Bradley Hoot (with content support from Vahid Alizadeh)
**Source meeting:** Meeting 8 (Friday, June 5, 2026)
**Status:** *adapted from the SLC's Meeting 8 resource page; minor formatting cleanup applied for GitHub rendering*

---

## Meeting Objectives

By the end of this session, participants will be able to:

1. **Define what "materials" means** in their own discipline and distinguish it from open data and open code.
2. **Identify candidate materials** in their current workflow that could be shared, and the ones that should not be.
3. **Choose an appropriate platform** for each material type (general-purpose, protocols, stimuli, reagents, language data, code-as-instrument).
4. **Navigate the legal and ethical constraints** around sharing: IRB and consent, copyright on stimuli, Material Transfer Agreements, FERPA, and culturally sensitive material.
5. **Apply CARE principles** alongside FAIR when sharing materials that involve human communities.
6. **Recognize collaborative-protocol consortia** in their field and evaluate whether participating fits their research.
7. **Connect open materials** to the open-science practices already covered this year (pre-registration, open data, reproducible analysis, transparent reporting, open access, version control).

---

> **Where this fits in our year.** We have covered most of the open-science lifecycle already: design (Chapter 2 pre-registration), data (Chapter 3 open data and FAIR), analysis (Chapter 4 reproducible workflows), reporting (Chapter 5 transparent reporting standards), publication (Chapter 6 open access), and the connective tissue of version control (Chapter 7 Git and GitHub). This chapter fills the last operational gap: the **materials** that produced the research in the first place. The stimuli a participant saw, the protocol a chemist ran, the transcription convention a linguist used, the codebook a criminologist applied. The stuff between the methods section and a replicator's success.

---

## Part 1: What "Materials" Actually Means

### 1.1 The gap between a methods section and a successful replication

A typical methods section reads: *"Participants were asked to rate stimuli on a 7-point scale."* Or: *"The compound was synthesized using a standard Suzuki coupling procedure."* Or: *"Sociolinguistic interviews were transcribed using community-standard conventions."*

A future researcher trying to replicate, extend, or even understand any of these studies needs the **actual** stimuli, the **actual** procedure, the **actual** transcription conventions. The cost of building these from scratch is what the open-materials movement is trying to eliminate, alongside the unfairness of asking people to reproduce what you would not let them see.

### 1.2 The boundary with practices we have already covered

We are not re-covering these. They have their own chapters:

- **The data themselves:** [Chapter 3 (Open Data Sharing)](03-open-data.md)
- **The analysis scripts:** [Chapter 4 (Reproducible Analysis)](04-reproducible-analysis.md)
- **The manuscript and venue choice:** [Chapter 6 (Open Access)](06-open-access.md)
- **The version history of any of the above:** [Chapter 7 (Version Control with GitHub)](07-version-control-github.md)

Materials are the **instruments and artifacts used in producing the research**. They are upstream of the data and downstream of the design.

### 1.3 Four buckets that cover most cases

Almost every material in research falls into one of four categories:

| Category | What it is | Examples across disciplines |
|----------|-----------|------------------------------|
| **Instruments and stimuli** | What the participant or experiment is exposed to | Questionnaires, audio files, image sets, video clips, reagents, plasmids, software interfaces |
| **Protocols and procedures** | The step-by-step procedure used to collect or process | SOPs, study scripts, sampling procedures, interview guides, synthesis protocols, calibration procedures |
| **Conventions and standards** | The schemes used to organize, code, or annotate | Transcription conventions, coding schemes, ontologies, codebooks, annotation guidelines |
| **Apparatus** | The hardware or software acting as an instrument | Custom rigs, devices, instrument configurations, experimental control software, hardware specs |

The taxonomy matters because each category has different sharing platforms, different legal constraints, and different conventions.

---

## Part 2: Why Materials, Specifically

We have already made the general case for openness across the year. What is specific to materials?

### 2.1 The replication argument

Without the actual stimuli or protocol, even a perfectly described methods section is insufficient. The reproducibility studies in psychology (Open Science Collaboration 2015), preclinical biology (Begley & Ellis 2012), and animal research (Plant et al 2019, *PLOS Biology*) all converge on the same point: protocols described in papers omit details that turn out to matter. Sharing the materials closes that gap directly.

### 2.2 The efficiency argument

Why should every graduate student in your field build their own questionnaire, elicitation task, codebook, or synthesis procedure from scratch when a well-tested version exists? Shared materials accelerate the field. The Stanford Open Policing Project, the Many Labs consortia, and the IRIS database for second-language research all exist because someone decided to release the working tooling rather than just the results.

### 2.3 The mandate argument

Funders increasingly require materials sharing alongside data. NIH Data Management and Sharing Policy (effective 2023) covers "scientific data" broadly, which in practice includes annotated stimuli, codebooks, and instruments. NSF Public Access Plan and the 2025 OSTP memo extend in a similar direction. Reading guideline updates is part of writing a competitive grant.

### 2.4 The credit argument

A materials archive with a DOI is now a citable scholarly output. The Berez-Kroeker et al (2018) Tromso Recommendations explicitly call for citing linguistic data and materials as primary outputs, not just supplements to a paper. Faculty CVs in the open era include materials and tools, not just publications. This is non-trivial credit that simply was not available a decade ago.

### 2.5 The ethical argument

If you are studying a population, a phenomenon, or a community at the public expense, the materials your work produced are part of the public scholarly commons. There are legitimate reasons not to share (IRB constraints, copyright limits, cultural-sensitivity considerations) and we will cover them at length. The default, where those constraints do not apply, is to share.

---

## Part 3: A Disciplinary Tour

A tour of what materials look like in each of our six disciplines. The point is that "materials" looks completely different depending on the field, and the sharing infrastructure has to match.

> **Chemistry.** Materials = synthetic procedures (reaction schemes, stoichiometries, reagent suppliers, lot numbers), spectral data files (NMR, mass spec), purification methods, safety considerations, ChemDraw files. The Open Reaction Database is the discipline-specific archive for reactions. JoVE Chemistry hosts video versions of difficult procedures. Reagents and biological catalysts go via MTAs (see Part 6).

> **Psychology.** Materials = stimuli (images, audio, video, vignettes), instruments (questionnaires, scales, behavioral tasks, neuroimaging paradigms), study scripts (the exact wording the experimenter reads), IRB-approved consent forms, qualitative codebooks. OSF Materials components are the workhorse. IRIS hosts second-language and applied-linguistics instruments. PsychOpen Materials hosts validated scales. Stimuli with copyrighted content require special handling.

> **Linguistics.** Materials = annotated corpora, transcription conventions, elicitation tasks, sociolinguistic interview guides, judgment-task stimuli, dictionaries and lexica, grammatical sketches, audio and video recordings of speech, annotation schemes. Linguistics has more discipline-specific archives than almost any other field: LDC, TalkBank/CHILDES, ELAR, The Language Archive at Max Planck, CLARIN, AILLA, PARADISEC. Part 5 goes deep on these.

> **Criminology.** Materials = interview guides, qualitative coding schemes, codebooks, observational protocols, vignettes, survey instruments, IRB packets. The IRB and confidentiality constraints in criminology research are unusually tight (vulnerable populations, sensitive topics, potential legal exposure), so the share/don't-share decision is more nuanced than in many other fields. Inter-University Consortium for Political and Social Research (ICPSR) has restricted-use archives that solve this for some projects.

> **Computing.** Materials = the software itself when software is the experimental instrument, configuration files, datasets used for benchmarking, hardware specifications, system snapshots. The line between "code" and "materials" blurs here. The right pattern is: active development on GitHub (see Chapter 7), citable snapshots on Zenodo with a DOI.

> **Library and Scholarly Communication.** Materials = LibGuides, instructional materials, training videos, workflow templates, advocacy materials for faculty open-science adoption. The library side increasingly produces *open educational resources* (OER) with their own dedicated archives like OER Commons, MERLOT, and OASIS.

---

## Part 4: Where to Share by Material Type

A practical map. Pick the platform that matches the material, not the other way around.

### 4.1 General-purpose

These accept almost any file type and assign DOIs. Use them when no discipline-specific archive applies, or when you want a single bundled deposit.

- [**OSF (Open Science Framework)**](https://osf.io) - Materials live as components in a project, each with its own DOI. The strongest choice for psych, social science, and any project with a pre-registration on OSF (Chapter 2 connection).
- [**Zenodo**](https://zenodo.org) - General research repository at CERN. Free DOIs for anything. Most useful for code-as-instrument and software releases connected to a GitHub repo (Chapter 7 connection).
- [**Figshare**](https://figshare.com) - Commercial repository, free tier. Good for posters and supplementary materials.
- [**Dataverse**](https://dataverse.org) - Strong support for social-science materials with structured metadata. Many institutional instances.

### 4.2 Protocols and procedures

- [**protocols.io**](https://www.protocols.io) - Owned by Springer Nature, free for academic use. Version-controlled, citable, with a Slack-style commenting and forking model. Now the de facto standard for biological and biomedical protocols.
- [**Bio-protocol**](https://bio-protocol.org) - Peer-reviewed protocol journal. Free to publish and to read.
- [**JoVE (Journal of Visualized Experiments)**](https://www.jove.com) - Video-protocol journal across disciplines. Subscription required to read for most institutions.
- [**STAR Protocols**](https://star-protocols.cell.com) - Open-access protocol journal from Cell Press, born from the STAR Methods checklist.
- [**Nature Protocols**](https://www.nature.com/nprot/) - Subscription, peer-reviewed step-by-step methods.

### 4.3 Stimuli and instruments (psychology, education, applied linguistics)

- [**OSF Materials components**](https://osf.io) - The most common host. Anything from a single PDF to a complex stimulus set.
- [**IRIS Database**](https://www.iris-database.org) - Instruments and materials for second-language research, hosted by University of York. Highly curated, with attribution metadata.
- [**PsychOpen**](https://www.psychopen.eu) - European-led open-access psych publishing infrastructure, with a materials section.
- [**Open Test Archive (Leibniz Institute)**](https://www.testarchiv.eu) - Validated psychological tests, scales, and questionnaires.

### 4.4 Reagents, biological materials, cell lines, organisms

- [**Addgene**](https://www.addgene.org) - Non-profit plasmid repository. Distributes physical plasmids globally.
- [**ATCC**](https://www.atcc.org) - Cell line and microorganism repository.
- [**Materials Project**](https://materialsproject.org) - Computed materials data (DFT calculations, properties).
- [**Cambridge Structural Database**](https://www.ccdc.cam.ac.uk) - Crystallographic structures.

### 4.5 Educational materials

- [**OER Commons**](https://oercommons.org) - Open Educational Resources catalog.
- [**MERLOT**](https://www.merlot.org) - Multimedia educational resources.
- [**OASIS (Openly Available Sources Integrated Search)**](https://oasis.geneseo.edu) - Aggregator across multiple OER repositories.
- **Institutional repositories** - DePaul's *Digital Commons @ DePaul* hosts faculty-produced teaching materials.

### 4.6 Apparatus and hardware

- [**HardwareX**](https://www.hardware-x.com) - Open-access journal for open-source scientific hardware. Each accepted design gets a DOI.
- [**Thingiverse / Printables**](https://www.thingiverse.com) - 3D-printable hardware designs (community quality varies).
- [**Open Source Hardware Association (OSHWA)**](https://www.oshwa.org) - Certification mark and registry for open hardware.

---

## Part 5: Linguistics Deep Dive (the field with the most archive infrastructure)

Linguistics has built more archive infrastructure than almost any other field, partly because so much of the work documents languages and speech communities that will not exist in their current form a generation from now.

### 5.1 Why linguistics archives matter

Unlike many disciplines, linguistic data and materials are often **unique and unrecoverable**. A recording of a fluent speaker of a language with 200 remaining speakers cannot be redone. The materials sharing question in linguistics is not abstract.

Bird and Simons (2003), in *Language*, defined seven dimensions of portability for language documentation: content, format, discovery, access, citation, preservation, and rights. Their framework anticipated FAIR by more than a decade and remains foundational. ([article link](https://www.linguisticsociety.org/sites/default/files/02-Bird.pdf))

### 5.2 The major archives

| Archive | Focus | Host | Access model |
|---------|-------|------|--------------|
| [**LDC (Linguistic Data Consortium)**](https://www.ldc.upenn.edu) | Speech, text, and lexical resources for NLP and computational linguistics | University of Pennsylvania | Membership-based; corpora available to member institutions |
| [**TalkBank / CHILDES**](https://talkbank.org) | Spoken-language corpora across populations: child language (CHILDES), aphasia, dementia, bilingualism, classrooms | Carnegie Mellon University (Brian MacWhinney) | Free with registration; CHAT transcription standard |
| [**ELAR (Endangered Languages Archive)**](https://www.elararchive.org) | Documentation of endangered languages | Humboldt University of Berlin (was SOAS, London) | Tiered access; some materials restricted by depositor community agreement |
| [**The Language Archive (TLA)**](https://archive.mpi.nl) | Multimedia language and gesture corpora | Max Planck Institute for Psycholinguistics, Nijmegen | Mostly open with attribution |
| [**CLARIN**](https://www.clarin.eu) | European federation of language resources and tools | European research infrastructure consortium | Federated single-sign-on across national nodes |
| [**AILLA**](https://ailla.utexas.org) | Indigenous languages of Latin America | University of Texas at Austin | Tiered access including community-restricted |
| [**PARADISEC**](https://www.paradisec.org.au) | Pacific and regional cultures and languages | Consortium of Australian universities | Mostly open; some access restrictions |
| [**DELAMAN**](https://www.delaman.org) | Network of digital archives for endangered language materials (umbrella organization) | International consortium | Coordination layer across the above |

### 5.3 Transcription standards as shared materials

A transcription convention is itself a piece of open infrastructure. The two dominant systems:

- **CHAT (Codes for the Human Analysis of Transcripts)** is the transcription standard used by TalkBank and CHILDES. Documented in MacWhinney's *The CHILDES Project* (2000) and continuously updated. Choosing CHAT for your transcriptions makes your corpus compatible with thousands of others.
- **ELAN** is the multimedia annotation tool from the Max Planck Institute, paired with the EAF file format. Excellent for time-aligned annotation of audio and video.

Using standard conventions is itself a form of materials sharing: every future researcher gets your corpus for free in their tool of choice.

### 5.4 Citing linguistic materials

The Berez-Kroeker et al (2018) **Tromso Recommendations** make the case that linguistic data deposits should be cited as first-class scholarly outputs in the same way papers are. The piece is in *Linguistics* 56(1) and is worth reading in full. ([open-access version](https://www.degruyter.com/document/doi/10.1515/ling-2017-0032/html))

The specific recommendations:

1. Cite data, materials, and tools in bibliographies.
2. Include DOIs whenever possible.
3. Treat archive deposits as citable on the same level as journal articles.
4. Tenure and promotion committees should count data and materials deposits.
5. Journals should require data and materials citations.

### 5.5 An honest constraint: community ownership of materials

The linguistics field has had to confront a hard question that other fields are only beginning to: when the speakers of an endangered language give you their recordings, what rights do they retain over those recordings? The CARE Principles for Indigenous Data Governance (Carroll et al 2020, *Data Science Journal*) extend FAIR with **Collective benefit, Authority to control, Responsibility, Ethics**. Many of the major linguistics archives now operate tiered-access systems specifically to honor community agreements. This is good practice that other disciplines (criminology, education, public health) are learning from. ([CARE principles paper](https://datascience.codata.org/articles/10.5334/dsj-2020-043))

---

## Part 6: Legal and Ethical Constraints on Sharing

The default is to share. The exceptions are real and worth knowing.

### 6.1 IRB and consent

The binding question: **what did your consent form authorize?**

- If the form said "data may be shared with other researchers in de-identified form," you can probably share de-identified materials.
- If the form said "data will be used only for this study," you cannot share even materials derived from those participants.
- If you want to share retrospectively, an IRB amendment is needed. Some IRBs allow this; some do not.

**Anonymization vs. de-identification:** anonymization (removing all identifiers irreversibly) is the safest. De-identification (replacing identifiers with codes you keep separately) is sometimes acceptable but is reversible by you and therefore by anyone who compels you.

**Going forward:** the cleanest practice is to write data sharing into your consent form from the start. Many institutions now provide template language for this. DePaul ORS can advise.

### 6.2 Copyright on stimuli

This trips up psychology and education researchers most often.

- A picture from a stock-photo website, a paragraph from a copyrighted novel, a film clip, or a piece of music used as a stimulus is **someone else's intellectual property**. The fact that you used it in research does not give you the right to redistribute it.
- **Fair use** in research is real but narrow. It generally permits **using** copyrighted material in a study but does **not** automatically permit **redistributing** it.
- The cleanest fix is to use **Creative Commons-licensed stimuli** from the start. Wikimedia Commons, Pexels, Unsplash, and Free Music Archive offer large CC-licensed pools. For a paid study, building this discipline in is worth the small effort.
- If you cannot release the original stimuli, you can usually release: the stimulus selection criteria, exact names or identifiers of the items, statistical norming data, and a description sufficient for someone with similar resources to assemble an equivalent set. This is often called a **stimulus protocol** and is better than nothing.

### 6.3 Material Transfer Agreements (MTAs)

For physical materials that move between institutions: plasmids, cell lines, reagents, biological samples, novel hardware. An MTA is a contract specifying who can use the material, for what purpose, and what credit and ownership the recipient has.

- The **Uniform Biological Material Transfer Agreement (UBMTA)** is a standardized template used by hundreds of US institutions. If both your institution and the recipient institution are UBMTA signatories, the transfer is essentially pre-approved. DePaul's Office of Research Services manages MTAs.
- For chemistry materials and novel reagents, expect a custom MTA per transfer.
- For software-as-material, an open-source license can fully replace an MTA (see Chapter 7's licensing notes).

### 6.4 FERPA and education materials

For education research, the Family Educational Rights and Privacy Act constrains sharing of identifiable student records, classroom recordings that capture students, and similar materials. Aggregated, de-identified materials are generally permissible. Recordings with identifiable students are not, unless explicit FERPA consent was obtained.

### 6.5 Cultural sensitivity and indigenous knowledge

Mentioned in Part 5 in the linguistics context: CARE Principles (Carroll et al 2020) extend FAIR with collective benefit, authority to control, responsibility, and ethics. Material that documents knowledge from indigenous, tribal, or sovereign communities should be shared under whatever access terms the source community agreed to, not under the researcher's default preference. Tiered-access archives like ELAR and AILLA are designed for exactly this.

### 6.6 Licensing materials you do share

When you have cleared the constraints above and are ready to release a material publicly, attach an explicit license:

- **CC BY 4.0** is the default for most non-code materials (stimuli, protocols, instruments, codebooks). Requires attribution; otherwise unrestricted.
- **CC0** for materials that should be effectively public domain (databases, factual compilations).
- **MIT or Apache 2.0** for code-as-instrument.

No license at all means "all rights reserved by default" in most jurisdictions, which defeats the point of releasing it. We covered the full license landscape in [Chapter 6 (Open Access)](06-open-access.md).

---

## Part 7: Collaborative-Protocol Consortia

A growing set of multi-institution collaborations build shared protocols deliberately, so that any participating site runs the same study and results are directly comparable. Worth knowing whether one exists in your area.

### 7.1 Notable consortia

- [**Many Labs**](https://github.com/many-labs) - A series of large-scale, pre-registered, multi-site replication projects in social and cognitive psychology. The original Many Labs 1 paper (Klein et al 2014, *Social Psychology*) introduced the model. Subsequent ManyLabs 2, 3, 4, 5 each addressed different questions.
- [**ManyBabies**](https://manybabies.org) - The same collaborative model applied to infant cognition research. The flagship study coordinated 67 labs and 2,329 infants (ManyBabies Consortium 2020, *AMPPS*).
- [**Psychological Science Accelerator (PSA)**](https://psysciacc.org) - Distributed global lab network. 700+ labs in 70+ countries. Each project uses a pre-registered shared protocol.
- [**Open Reaction Database (ORD)**](https://open-reaction-database.org) - Community-curated database of chemical reactions with consistent metadata. Founded by industry-academia consortium.
- [**ManyPrimates**](https://manyprimates.github.io) - Multi-site comparative cognition research across primate species.

### 7.2 What makes a protocol "collaborative-ready"

Whether you are running a consortium or just publishing a protocol others might adopt, certain features make a protocol actually usable by other labs:

- **Version control** with a clear citation for which version produced which results (Chapter 7 connection)
- **Translation infrastructure** if it might travel internationally
- **Pilot data** showing the protocol runs as intended
- **Adaptation guidance** spelling out which parameters are critical and which can flex by site
- **Pre-registered analysis** so all participating sites analyze identically (Chapter 2 connection)
- **A standing communication channel** for sites to flag execution issues

### 7.3 Whether to participate

Not every project should join a consortium. The downsides are real: slower timelines, less control over design, the political work of consensus. But for any research question where multi-site evidence would substantially change confidence in the finding, the upside is enormous. Consortium contributions also increasingly count as scholarly outputs in their own right.

---

## Part 8: A Sharing Workflow

From "I should share this" to "it is shared." A practical sequence.

> 1. **Identify what you have.** Walk through one current project and inventory its materials by the four categories from Part 1 (instruments/stimuli, protocols/procedures, conventions/standards, apparatus).
> 2. **Check what you can legally share.** Apply the constraint checklist from Part 6: IRB consent language, copyright on third-party content, MTAs for physical materials, FERPA if applicable, cultural-community agreements.
> 3. **Choose the right platform.** Use the map in Part 4. Discipline-specific archives are usually a better choice than general-purpose ones when they exist, because metadata and discoverability are better.
> 4. **Document context.** A bare file with no metadata is hard to reuse. Include: what the material is, what study it supported, what version it is, what known limitations or caveats apply, how to cite it.
> 5. **Get a DOI.** Almost every platform listed in Part 4 mints DOIs. The DOI is what makes the deposit citable and durable.
> 6. **Cite the material in your manuscript.** Berez-Kroeker et al (2018) Tromso Recommendations make this norm explicit. Treat your own materials deposits the way you treat your own published papers in the bibliography.
> 7. **Link from the manuscript and the repo.** Cross-link the materials archive, the GitHub repo (Chapter 7), the OSF project, and the manuscript so any one entry point leads to the others.

---

## Part 9: Discipline Vignettes

Short sketches of what an open-materials practice could look like, one per discipline.

> **Chemistry.** A synthesis project has its procedure on protocols.io with a DOI, a tabulated reagent list with supplier and lot numbers, spectral data (NMR, mass spec) deposited on Zenodo, and a ChemDraw file in the GitHub repo. The Open Reaction Database deposit gives the reaction itself a machine-readable, queryable record. Future synthetic chemists trying the same coupling find your procedure in 30 seconds instead of rebuilding it from your paper's supplement.

> **Psychology.** A study's stimuli (when copyright permits) live in an OSF Materials component, the instruments and scales in IRIS or PsychOpen, the experimental script in a paragraph-by-paragraph protocol document. Where copyright blocks redistribution, a *stimulus protocol* gives selection criteria, norming data, and exact identifiers so others can assemble an equivalent set. The whole bundle is linked from the OSF pre-registration (Chapter 2) and the manuscript.

> **Linguistics.** A documentation project deposits annotated audio and transcriptions in ELAR or TLA, follows CHAT or ELAN conventions so the corpus is interoperable, makes elicitation tasks and judgment-task stimuli available in an OSF component, and pre-registers any quantitative work. Tiered access honors any community agreements about which materials remain restricted. The data deposit gets cited as a primary output in any subsequent paper.

> **Criminology.** A qualitative project releases the interview guide, coding scheme, and aggregated coding tree on OSF, with raw interview transcripts in ICPSR's restricted-use archive accessible only with a data-use agreement. The codebook becomes a citable artifact in its own right. Future researchers studying related questions can adopt or critique the coding scheme directly rather than reinventing it.

> **Computing.** Custom benchmarking software, evaluation scripts, hardware configurations, and dataset preprocessing pipelines all live on GitHub for active development. Each manuscript-associated version is tagged as a release and snapshotted to Zenodo with a DOI. The repo README explicitly distinguishes "data we collected" from "software we built," and each gets the right license (MIT for code, CC BY for data).

> **Library and Scholarly Communication.** Faculty-facing instructional materials (LibGuides, workshop slides, OER course modules) are deposited in OER Commons or MERLOT with CC BY licenses, mirrored in DePaul's Digital Commons, and referenced in the institutional open-science guidance. Each instructional artifact is citable and reusable by peer librarians and faculty at other institutions.

---

## Part 10: Resources and Further Reading

A curated, validated set.

### 10.1 Foundational papers

- **Berez-Kroeker, A. L., Andreassen, H. N., Gawne, L., Holton, G., Kung, S. S., Pulsifer, P., & Woodbury, A. C. (2018).** [Reproducible research in linguistics: A position statement on data citation and attribution.](https://www.degruyter.com/document/doi/10.1515/ling-2017-0032/html) *Linguistics*, 56(1), 1-18.
- **Bird, S., & Simons, G. (2003).** [Seven dimensions of portability for language documentation and description.](https://www.linguisticsociety.org/sites/default/files/02-Bird.pdf) *Language*, 79(3), 557-582.
- **Carroll, S. R., Garba, I., Figueroa-Rodriguez, O. L., Holbrook, J., Lovett, R., Materechera, S., et al. (2020).** [The CARE Principles for Indigenous Data Governance.](https://datascience.codata.org/articles/10.5334/dsj-2020-043) *Data Science Journal*, 19(1), 43.
- **Klein, R. A., Ratliff, K. A., Vianello, M., Adams, R. B., Bahnik, S., Bernstein, M. J., et al. (2014).** [Investigating variation in replicability: A "Many Labs" replication project.](https://econtent.hogrefe.com/doi/10.1027/1864-9335/a000178) *Social Psychology*, 45(3), 142-152.
- **The ManyBabies Consortium. (2020).** [Quantifying sources of variability in infancy research using the infant-directed-speech preference.](https://journals.sagepub.com/doi/10.1177/2515245919900809) *Advances in Methods and Practices in Psychological Science*, 3(1), 24-52.
- **Begley, C. G., & Ellis, L. M. (2012).** [Raise standards for preclinical cancer research.](https://www.nature.com/articles/483531a) *Nature*, 483(7391), 531-533.
- **Plant, A. L., Locascio, L. E., May, W. E., & Gallagher, P. D. (2014).** [Improved reproducibility by assuring confidence in measurements in biomedical research.](https://www.nature.com/articles/nmeth.2884) *Nature Methods*, 11(9), 895-898.

### 10.2 Platforms (a quick directory)

- General-purpose: [OSF](https://osf.io), [Zenodo](https://zenodo.org), [Figshare](https://figshare.com), [Dataverse](https://dataverse.org)
- Protocols: [protocols.io](https://www.protocols.io), [Bio-protocol](https://bio-protocol.org), [JoVE](https://www.jove.com), [STAR Protocols](https://star-protocols.cell.com), [Nature Protocols](https://www.nature.com/nprot/)
- Stimuli and psych instruments: [IRIS Database](https://www.iris-database.org), [PsychOpen](https://www.psychopen.eu), [Open Test Archive](https://www.testarchiv.eu)
- Linguistics: [LDC](https://www.ldc.upenn.edu), [TalkBank / CHILDES](https://talkbank.org), [ELAR](https://www.elararchive.org), [The Language Archive](https://archive.mpi.nl), [CLARIN](https://www.clarin.eu), [AILLA](https://ailla.utexas.org), [PARADISEC](https://www.paradisec.org.au)
- Reagents and biology: [Addgene](https://www.addgene.org), [ATCC](https://www.atcc.org), [Materials Project](https://materialsproject.org)
- Education / OER: [OER Commons](https://oercommons.org), [MERLOT](https://www.merlot.org), [OASIS](https://oasis.geneseo.edu)
- Hardware: [HardwareX](https://www.hardware-x.com), [OSHWA](https://www.oshwa.org)

### 10.3 Consortia worth knowing

[Many Labs](https://github.com/many-labs), [ManyBabies](https://manybabies.org), [Psychological Science Accelerator](https://psysciacc.org), [ManyPrimates](https://manyprimates.github.io), [Open Reaction Database](https://open-reaction-database.org), [ICPSR](https://www.icpsr.umich.edu) for restricted-use social science data.

### 10.4 Practical guides

- [**The Turing Way - Chapter on research compendia and protocols**](https://book.the-turing-way.org)
- [**OSF's documentation on sharing materials**](https://help.osf.io)
- [**protocols.io getting-started guide**](https://www.protocols.io/start)
- [**DePaul Library guide on open data and materials**](https://libguides.depaul.edu) - Kelly Hallisy's purview; ask her for the specific guide that applies to your discipline.

### 10.5 IRB and ethics references

- The **CARE Principles** paper (Carroll et al 2020) listed above
- DePaul's IRB office for consent-form templates that include sharing language
- **CITI Program's research-ethics modules** if you want a refresher on consent and sharing

---

## Glossary

Terms specific to materials. The version-control vocabulary from Chapter 7 and the FAIR/open-data vocabulary from Chapter 3 are not repeated here.

- **Apparatus.** Hardware or software acting as an instrument in the research.
- **CARE Principles.** Collective benefit, Authority to control, Responsibility, Ethics. Complement FAIR for materials involving indigenous and community data (Carroll et al 2020).
- **CHAT.** Codes for the Human Analysis of Transcripts. Transcription standard used by CHILDES and TalkBank.
- **Codebook.** A structured document explaining variables, codes, and meanings in qualitative or survey research.
- **Consortium.** A multi-institution collaborative running a shared protocol across sites (Many Labs, ManyBabies, etc).
- **Documentation (linguistic).** The recording, annotation, and archival preservation of language data from a speech community.
- **ELAN.** Multimedia annotation tool from Max Planck. Paired with EAF file format.
- **Materials Transfer Agreement (MTA).** Contract governing transfer of physical research materials between institutions.
- **OER (Open Educational Resources).** Teaching, learning, and research materials in any medium released under an open license.
- **Pre-registration.** Public commitment to a study's design before data collection. (See Chapter 2 for depth.)
- **Protocol.** A step-by-step procedure used to collect, process, or analyze data.
- **Restricted-use archive.** A repository where deposit is open but access requires a data-use agreement (e.g., ICPSR's restricted-use track).
- **Stimulus protocol.** A document describing stimulus selection and norming sufficiently for others to assemble an equivalent set, used when copyright blocks redistribution of the original stimuli.
- **Tiered access.** Archive model where some materials are openly available and others are restricted by community agreement or IRB.
- **Tromso Recommendations.** A set of recommendations on data and materials citation in linguistics, articulated in Berez-Kroeker et al (2018).
- **UBMTA.** Uniform Biological Material Transfer Agreement. Standardized template used by many US institutions for biological-material transfers.

---

> **Closing thought.** Of all the open-science practices we have covered this year, materials sharing is the one most likely to be invisible to journal reviewers and most consequential for the next researcher who tries to build on your work. The norms are field-specific, the constraints are real, the platforms are good, and the credit is finally arriving. Pick one piece of one project this week and put it under a DOI.

---

*Previous: [Version Control with Git & GitHub](07-version-control-github.md)* - *Next: end of guide*

*Want to contribute? See [CONTRIBUTING.md](../CONTRIBUTING.md).*
