# Tools and Platforms

An annotated catalog of every tool mentioned across the chapters. Free unless otherwise noted. The chapter source is shown after each tool.

---

## Version Control and Code Collaboration

| Tool | What it is | Notes | Source |
|------|-----------|-------|--------|
| [GitHub](https://github.com) | Web platform for Git repositories with collaboration features | Free for individuals; free Pro for verified academics | Ch.7 |
| [GitHub Desktop](https://desktop.github.com) | GUI Git client for Mac and Windows | Recommended for non-technical users; no terminal needed | Ch.7 |
| [GitHub Mobile](https://github.com/mobile) | Mobile app for iOS and Android | Best for triaging issues and reviewing PRs from your phone | Ch.7 |
| [GitHub Codespaces](https://github.com/features/codespaces) | Cloud development environment | 60 hr/month free; 90 hr/month with Pro | Ch.7 |
| [GitHub Pages](https://pages.github.com) | Free static-site hosting from a repo | Used for the rendered version of this guide | Ch.7 |
| [GitHub Copilot](https://github.com/features/copilot) | AI coding/writing assistant | Free for verified academics via GitHub Education | Ch.7 |
| [GitHub Education](https://education.github.com) | Free Pro for faculty and students | Apply with your `.edu` email | Ch.7 |
| [GitLab](https://about.gitlab.com) | Alternative to GitHub | Self-hostable; widely used in some research institutions | Ch.7 |
| [Codeberg](https://codeberg.org) | Non-profit alternative to GitHub | Hosted in Europe; supports Forgejo | Ch.7 |
| [Bitbucket](https://bitbucket.org) | Atlassian's Git hosting platform | Often paired with Jira | Ch.7 |

## Pre-registration and Project Management

| Tool | What it is | Notes | Source |
|------|-----------|-------|--------|
| [Open Science Framework (OSF)](https://osf.io) | Free project-management platform from the Center for Open Science | Component-level DOIs; pre-registration support; integrates with GitHub | Ch.1, Ch.2, Ch.3 |
| [AsPredicted](https://aspredicted.org) | Lightweight pre-registration platform | Nine-question format; common in psychology | Ch.2 |
| [Registered Reports (Center for Open Science)](https://www.cos.io/initiatives/registered-reports) | Publication format with pre-data-collection peer review | Adopted by 300+ journals as of 2025 | Ch.2 |
| [ClinicalTrials.gov](https://clinicaltrials.gov) | NIH/NLM registry of clinical studies | Pre-registration mandatory for many trials | Ch.2 |
| [protocols.io](https://www.protocols.io/) | Step-by-step protocol sharing with version control | Strong in life sciences; free for public protocols | Ch.1, Ch.8 |

## Data Sharing and Repositories

| Tool | What it is | Notes | Source |
|------|-----------|-------|--------|
| [Zenodo](https://zenodo.org) | General-purpose research repository operated by CERN | Free DOIs for any output; integrates with GitHub for citable code releases | Ch.3, Ch.6, Ch.7 |
| [Dataverse](https://dataverse.org) | Open-source data repository network | Many institutional instances; strong support for social-science data | Ch.3 |
| [Figshare](https://figshare.com) | Commercial research repository | Free tier available | Ch.3 |
| [Dryad](https://datadryad.org) | Curated repository for research data | Common in biological and ecological sciences | Ch.3 |
| [PubMed Central (PMC)](https://www.ncbi.nlm.nih.gov/pmc/) | NIH's free archive of biomedical literature | Required deposit for NIH-funded research | Ch.6 |
| [arXiv](https://arxiv.org) | Preprint server for physics, math, CS, statistics, quant bio | The original; founded 1991 | Ch.6 |
| [bioRxiv](https://www.biorxiv.org) / [medRxiv](https://www.medrxiv.org) | Preprint servers for biology and medicine | Now operated by openRxiv (non-profit) | Ch.6 |
| [ChemRxiv](https://chemrxiv.org) | Preprint server for chemistry | Operated by ACS | Ch.6 |
| [PsyArXiv](https://psyarxiv.com), [SocArXiv](https://osf.io/preprints/socarxiv), [EdArXiv](https://edarxiv.org), [LawArXiv](https://lawarxiv.info), [MetaArXiv](https://metaarxiv.org/) | OSF-hosted preprint servers | One per discipline; aggregated at [OSF Preprints](https://osf.io/preprints/) | Ch.6 |
| [Research Data Alliance](https://www.rd-alliance.org/) | Global collaboration on data standards | Useful for finding domain-specific repositories | Ch.3 |

## Reproducible Analysis

| Tool | What it is | Notes | Source |
|------|-----------|-------|--------|
| [Quarto](https://quarto.org) | Open-source scientific publishing system | Successor to R Markdown; supports R, Python, Julia, JS | Ch.4 |
| [Jupyter](https://jupyter.org) | Interactive notebooks for Python, R, Julia, and others | The de facto standard for computational notebooks | Ch.4 |
| [R Markdown](https://rmarkdown.rstudio.com) | Literate programming for R | Mature; widely used in social sciences | Ch.4 |
| [RStudio / Posit](https://posit.co/products/open-source/rstudio/) | IDE for R | Free desktop version; integrates with Git via a GUI panel | Ch.4 |
| [Visual Studio Code](https://code.visualstudio.com) | Free, cross-platform editor | The most flexible Markdown editor; integrates with GitHub natively | Ch.7 |
| [github.dev](https://github.dev) | VS Code in the browser, attached to a repo | Press the `.` key in any GitHub repo | Ch.7 |
| [Stencila](https://stenci.la) | Reproducible-document editor | Less widely adopted but interesting for non-coders | Ch.4 |

## Reference Management and Bibliographies

| Tool | What it is | Notes | Source |
|------|-----------|-------|--------|
| [Zotero](https://www.zotero.org) | Open-source reference manager | Free; strong scholarly metadata support | Ch.7 |
| [Better BibTeX for Zotero](https://retorque.re/zotero-better-bibtex/) | Plugin for stable BibTeX export | Useful for repos that include `.bib` files | Ch.7 |
| [Mendeley](https://www.mendeley.com) | Reference manager from Elsevier | Free tier; less-loved than Zotero in open-science circles | Ch.7 |

## Citation, Identifiers, and Persistent IDs

| Tool | What it is | Notes | Source |
|------|-----------|-------|--------|
| [Citation File Format (CFF)](https://citation-file-format.github.io) | Machine-readable citation metadata | A `CITATION.cff` at the top of a repo gives a one-click cite button on GitHub | Ch.7 |
| [ORCID](https://orcid.org) | Persistent author identifier | Free; required by most major journals and funders | Ch.3, Ch.6 |
| [DataCite](https://datacite.org) | DOI registration agency for data | Powers DOIs minted by Zenodo, Dataverse, etc. | Ch.3, Ch.6 |
| [Crossref](https://www.crossref.org) | DOI registration agency for journal articles | The other major DOI provider | Ch.6 |
| [ROR (Research Organization Registry)](https://ror.org/) | Persistent identifiers for research organizations | Used in metadata and grant systems | Ch.3 |

## Open Access and Publishing

| Tool | What it is | Notes | Source |
|------|-----------|-------|--------|
| [DOAJ - Directory of Open Access Journals](https://doaj.org) | Quality-controlled list of legitimate OA journals | Verify journals before submitting | Ch.6 |
| [SHERPA RoMEO](https://v2.sherpa.ac.uk/romeo/) | Publisher self-archiving policies | Look up journal before depositing a preprint or postprint | Ch.6 |
| [Jisc Open Policy Finder](https://openpolicyfinder.jisc.ac.uk/) | Alternative to RoMEO | Same purpose, slightly different interface | Ch.6 |
| [Think. Check. Submit.](https://thinkchecksubmit.org) | Predatory-publisher checklist | Free guidance for researchers | Ch.6 |
| [Unpaywall](https://unpaywall.org) | Browser extension for finding free PDFs | Indexes legitimate OA copies | Ch.6 |
| [Creative Commons License Chooser](https://chooser-beta.creativecommons.org) | Walk-through for picking a license | Three questions, gets you to the right CC license | Ch.6 |
| [Choose a License](https://choosealicense.com/) | Picking the right license in 30 seconds | Recommended for picking the license for code | Ch.7 |

## Reporting Guidelines (Authoritative Frameworks)

| Tool | What it is | Notes | Source |
|------|-----------|-------|--------|
| [EQUATOR Network](https://www.equator-network.org) | Catalog of reporting guidelines across health research | Master list of CONSORT, PRISMA, ARRIVE, STROBE, etc. | Ch.5 |
| [CONSORT](http://www.consort-statement.org) | RCT reporting guideline | Adopted by hundreds of journals | Ch.5 |
| [PRISMA](https://www.prisma-statement.org) | Systematic-review reporting guideline | Updated 2020 | Ch.5 |
| [ARRIVE](https://arriveguidelines.org) | Animal-research reporting guideline | Updated 2020 | Ch.5 |
| [STROBE](https://www.strobe-statement.org) | Observational-study reporting guideline | Cohort, case-control, cross-sectional | Ch.5 |
| [SRQR](https://www.equator-network.org/reporting-guidelines/srqr/) | Qualitative-research reporting | For interviews, ethnography, focus groups | Ch.5 |
| [COREQ](https://academic.oup.com/intqhc/article/19/6/349/1791966) | Reporting for interviews and focus groups | Methodological detail for qualitative work | Ch.5 |
| [TOP Guidelines](https://www.cos.io/initiatives/top-guidelines) | Tiered transparency framework for journals | Used by 5,000+ journals | Ch.1, Ch.5 |
| [Penelope.ai](http://penelope.ai/) | Automated reporting-completeness checker | Useful pre-submission tool | Ch.5 |
| [GoodReports.org](http://GoodReports.org) | Automated reporting-completeness checker | Companion to EQUATOR | Ch.5 |

## Containerization and Computational Reproducibility

| Tool | What it is | Notes | Source |
|------|-----------|-------|--------|
| [Docker](https://www.docker.com) | Containerization platform | The core technology for "ship the environment with the code" | Ch.4 |
| [Code Ocean](https://codeocean.com) | Reproducible-research platform | Container-based; institutional licenses available | Ch.4 |
| [Whole Tale](https://wholetale.org) | Reproducible-research platform | NSF-funded; supports multiple languages | Ch.4 |
| [Binder / mybinder.org](https://mybinder.org) | Run a Jupyter notebook from a GitHub repo | Free; no install for readers | Ch.4 |

## Lab Management and Project Boards

| Tool | What it is | Notes | Source |
|------|-----------|-------|--------|
| [GitHub Projects](https://github.com/features/issues) | Built-in Kanban over Issues | Free; integrates natively with the rest of GitHub | Ch.7 |
| [Notion](https://notion.so) | Document-and-database hybrid | Free academic plan; embeds GitHub issues | Ch.7 |
| [Trello](https://trello.com) | Classic Kanban tool | Free; many free GitHub integrations | Ch.7 |
| [Asana](https://asana.com) / [Linear](https://linear.app) | Modern project trackers | Free tiers; both integrate with GitHub | Ch.7 |

## Markdown and Writing Tools

| Tool | What it is | Notes | Source |
|------|-----------|-------|--------|
| [Make a README](https://www.makeareadme.com/) | Template and guide for writing a good README | Free, useful, short | Ch.7 |
| [GitHub Markdown Guide](https://docs.github.com/en/get-started/writing-on-github) | For writing READMEs and issues | Official docs | Ch.7 |
| [Conventional Commits](https://www.conventionalcommits.org/) | A popular convention for commit messages | Useful with automation | Ch.7 |
| [Overleaf](https://www.overleaf.com) | Cloud-based LaTeX editor | Free academic accounts | Ch.5 |

## Cheat Sheets and Quick References

- [GitHub Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf) - one-page PDF *(Ch.7)*
- [GitHub Markdown Guide](https://docs.github.com/en/get-started/writing-on-github) - for writing READMEs and issues *(Ch.7)*
- [Choose a License](https://choosealicense.com/) - 30 seconds to the right license *(Ch.7)*
- [Make a README](https://www.makeareadme.com/) - template and guidance *(Ch.7)*

---

*See also: [Reading List](reading-list.md), [Glossary](glossary.md).*
