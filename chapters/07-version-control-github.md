# Chapter 7 - Version Control with Git & GitHub

**Lead author:** Vahid Alizadeh
**Source meeting:** Meeting 7 (May 1, 2026)
**Status:** *adapted from the SLC's live Notion meeting page; minor formatting cleanup applied*

---


**Date:** Friday, May 1, 2026

**Presenter:** Vahid Alizadeh

**Format:** 90-minute hands-on workshop, Zoom, GUI-only (no terminal)

**Learning Community:** Open Science in Practice: Tools and Workflows for Transparent, Reproducible Research

---

## 🎯 Meeting Objectives

By the end of this session, participants will be able to:

1. **Articulate the value of version control** for research, lab management, and reproducibility, and explain why it matters even for non-coders.
2. **Distinguish Git from GitHub**, and translate version-control vocabulary (repo, commit, branch, pull request, issue) into research vocabulary they already use.
3. **Create and manage a research repository** entirely through the [GitHub.com](http://GitHub.com) web interface, with no command line required.
4. **Use GitHub Desktop** to sync work between their laptop and GitHub with a fully graphical workflow.
5. **Set up the three workshop scenarios** for their own work: a Lab/Project Handbook, a Manuscript & Analysis Companion repo, and a contribution to the shared SLC Implementation Guide.
6. **Apply collaboration features** (Issues, Pull Requests, Projects, Discussions, Wiki, and GitHub Pages) to real research and lab-management tasks.
7. **Use GitHub Copilot** on the GitHub website (Chat and Coding Agent) to draft READMEs, summarize repositories, write PR descriptions, and complete small tasks via natural-language instructions.
8. **Connect their repository** to the broader open-science ecosystem via OSF, Zenodo (for citable DOIs), Zotero, and the Citation File Format.
9. **Choose appropriate visibility** (public vs. private) for sensitive, IRB-regulated, or copyrighted content.
10. **Plan a contribution** to the year-end Open Science Implementation Guide as their workshop deliverable.

---

> 💭
>
> ### Common Worries (and Why They Shouldn't Stop You)
>
> - **"I don't write code."** Most of what we'll do is editing markdown files (essentially Word documents in plain text). The features that matter for lab management, manuscripts, and protocols don't require code at all.
> - **"My data is sensitive (IRB, FERPA, copyrighted)."** GitHub supports unlimited free **private** repositories with collaborators. We'll discuss what should and should not live on GitHub.
> - **"I work in Word, not markdown."** Markdown is plain English with light decoration (`# Heading`, `**bold**`). GitHub renders it beautifully. You can also store `.docx`, `.pdf`, and most other file types directly.
> - **"I'm worried about Copilot training on my work."** Reasonable concern. Private repositories are excluded from training by default, and we'll cover the settings in the workshop.
> - **"I tried Git years ago and got lost in the terminal."** We won't open a terminal once today. Everything happens in the browser or in GitHub Desktop.

---

# PART 1️⃣: Foundations of Version Control & GitHub

## 1.1 The "FINAL_v3_actually_FINAL_real.docx" Problem

Every researcher has lived this story: a manuscript, protocol, or analysis script accumulates a trail of files like `analysis_v3.R`, `analysis_v3_kim_edits.R`, `analysis_v3_kim_edits_FINAL.R`, `analysis_v3_kim_edits_FINAL_actually_FINAL.R`. Co-authors email versions back and forth. Two people edit at once. A change made three months ago can no longer be explained.

Version control replaces this folklore with infrastructure. **One canonical file. Every change recorded. Every change attributable to a person, a date, and a reason. Every prior state recoverable.** The discipline is independent of whether you write code, prose, protocols, or stimuli.

> 📜
>
> **Required reading (read before the workshop if you can; it is short and excellent):**
>
> Bryan, J. (2018). [Excuse me, do you have a moment to talk about version control?](https://peerj.com/preprints/3159/) *The American Statistician*, 72(1), 20-27.
>
> This paper is written explicitly for non-computer-scientists, and it is the canonical justification for version control as a research practice, not as a programming practice.

## 1.2 Git vs. GitHub: What's the Difference?

**Git** is the underlying version-control system, software that tracks changes to files. Created by Linus Torvalds in 2005 to manage the Linux kernel, Git is free, open-source, and runs on any computer.

**GitHub** is a web platform that hosts Git repositories and adds a layer of collaboration features: issues, pull requests, code review, discussions, project boards, hosted websites, AI assistants, and more. GitHub is owned by Microsoft and is free for individuals and academic users.

> 💡
>
> **Analogy.** Git is to GitHub what Microsoft Word is to OneDrive. Git tracks the file; GitHub stores it in the cloud and lets people work on it together.
>
> You can use Git without GitHub (locally, with no internet). You cannot use GitHub without Git, but GitHub Desktop and the website handle every Git command for you.

**Alternatives to GitHub** include GitLab, Bitbucket, Codeberg, and self-hosted Gitea. GitHub is the most widely adopted in academia and has the best free academic tier and AI tooling, which is why this workshop centers on it. Skills transfer to other platforms.

## 1.3 Core Concepts Mapped to Research Vocabulary

| **GitHub Term** | **What It Is** | **Research Analogue** |
| --- | --- | --- |
| **Repository ("repo")** | A folder of files plus its complete history of changes | A project folder with built-in track-changes |
| **Commit** | A labeled snapshot of all files at a moment in time, with a message | Saving a draft, with a sticky-note explaining what you changed |
| **Branch** | A parallel line of work that can be merged back later | A separate copy of a draft for trying something risky |
| **Pull Request (PR)** | A proposal to merge changes from one branch into another, with a place to discuss | "Please review my edits" with track changes, comments, and approval |
| **Issue** | A discussion thread about something to fix, add, or decide | A lab to-do, a meeting agenda item, a Q&A thread |
| **Fork** | A personal copy of someone else's repo | Photocopying a colleague's protocol so you can adapt it |
| **Clone** | A copy of a repo on your local computer | Downloading a shared folder so you can work offline |
| **README** | The orientation document at the top of a repo | The first page of a lab notebook: "what is this and how do I use it?" |
| **License** | The legal terms under which others can reuse your work | Creative Commons license on a paper or dataset |
| **Release** | A named, archived version of the repo (e.g., `v1.0`) | The version you submitted with a manuscript |

## 1.4 Connection to the Year's Open-Science Journey

Version control is the connective tissue between everything we have studied this year:

- **Pre-registration (Meeting 2, Kimberly):** OSF pre-registrations have version histories; GitHub is the same idea applied to your *whole project*.
- **Open data sharing (Meeting 3, Vahid):** Datasets need provenance: who changed what and when. Repositories make that visible.
- **Reproducible analysis (Meeting 4, Vahid):** A literate notebook (Quarto, Jupyter, R Markdown) is most useful when its history is preserved alongside it.
- **Transparent reporting (Meeting 5, Kimberly & Vahid):** Reviewers and editors increasingly ask for the analysis code that produced the figures. A public repo is the cleanest way to provide it.
- **Open access publishing (Meeting 6, Kyle):** A GitHub release archived to Zenodo gives your code a DOI, making it citable in exactly the same way as the manuscript.
- **Today (Meeting 7):** Version control as a *practice*, not just as a tool, with hands-on use of the platform that ties all of the above together.

---

# PART 2️⃣: Tools, GUI-First, No Terminal

This workshop deliberately avoids the command line. Every action shown today is achievable through one of three interfaces: the GitHub website, the GitHub Desktop app, or the GitHub Mobile app. We'll mention Codespaces and the editor extensions briefly so you know they exist when you need more power.

## 2.1 [GitHub.com](http://GitHub.com): The Web Interface

The website is the most powerful and most accessible interface to GitHub. **Almost everything we'll do today happens here.**

**What you can do entirely in the browser, with no installation:**

- Create a new repository
- Create, edit, rename, move, and delete files
- Commit changes with messages
- Create branches and pull requests
- Review and merge pull requests
- Open and close issues
- Manage collaborators and permissions
- Search across repositories
- Use GitHub Copilot Chat to ask questions about a repo
- Assign work to the GitHub Copilot Coding Agent
- Edit files in a full [**github.dev**](http://github.dev) editor (press the `.` key in any repo to launch a VS Code-equivalent in your browser tab)

> ⌨️
>
> **Tip:** In any GitHub repo, press the period key (`.`) on your keyboard. The URL changes from `github.com/...` to `github.dev/...` and the page transforms into a full file editor with file tree, search, and source-control panel. No installation, no terminal. This is the easiest way to make multiple edits in one go.

## 2.2 GitHub Desktop: Drag, Drop, Commit

[**GitHub Desktop**](https://desktop.github.com/) is a free graphical client from GitHub for macOS and Windows. It is the recommended way to work with files locally for non-technical users.

**What it gives you:**

- A visual list of every change in your repository, with side-by-side diffs
- One-click commit, push, and pull
- Branch creation and switching from a dropdown
- Conflict resolution with a built-in merge tool
- One-click "open in your editor" (Word, VS Code, RStudio, etc.) and "show in Finder/Explorer"

**When to use Desktop instead of the website:**

- You're editing many files at once
- You're working with binary files (Word docs, images, PDFs, PowerPoint)
- You want to be able to work offline (e.g., on a plane)
- You're using software that needs the files on your local machine (RStudio, SPSS, ELAN, Praat, ChemDraw)

## 2.3 GitHub Mobile: Triage on the Go

The [GitHub Mobile app](https://github.com/mobile) (iOS, Android) is excellent for one specific use case: **reviewing pull requests and triaging issues from your phone.** You will not write code or do major editing here, but you can read a colleague's proposed change, leave a comment, approve it, or merge it from a coffee shop.

## 2.4 GitHub Codespaces: Your Computer, in the Browser

[**Codespaces**](https://github.com/features/codespaces) is a cloud development environment. With one click on a repo's `<> Code` button, GitHub spins up a remote Linux machine pre-loaded with the repo and a full VS Code editor running in your browser tab. Everything you'd normally install on your own laptop is already there.

> ☁️
>
> **Why Codespaces matters for non-coders.**
>
> - **Zero installation.** No "first set up Python / R / pandoc / Java...". The author of the repo configures it once; everyone after gets a working environment in 30 seconds.
> - **Cross-platform.** Same experience whether you're on a Mac, Windows, Chromebook, iPad, or library kiosk.
> - **Onboarding new lab members.** A new student can be productive in the lab's repo on day one without IT setup.
> - **Free tier.** GitHub gives every account 60 hours/month of Codespaces compute and 15 GB of storage at no cost. GitHub Pro (free with academic verification) raises this to 90 hours.
>
> We will not require Codespaces for the workshop (Desktop is enough), but we'll demo it briefly so you know it exists.

## 2.5 Free Academic Upgrade: GitHub Education

[**GitHub Education**](https://education.github.com/) gives faculty and students free access to **GitHub Pro** features after a one-time verification (typically with a `.edu` email and a quick screenshot of an institutional ID). Benefits:

- Free **GitHub Copilot Pro** (worth $10/month), the AI features we'll cover
- Higher Codespaces and Actions allowances
- Free Pro on [GitHub.com](http://GitHub.com) (advanced insights, code review tools)
- Free or discounted access to dozens of partner tools (Datadog, Namecheap, JetBrains, etc.)

**Apply at** [`education.github.com/discount_requests/application`](https://education.github.com/discount_requests/application). Approval typically takes 1-7 days.

---

# PART 3️⃣: Repos for Research: Public, Private, and Sensitive Data

## 3.1 Public vs. Private Repositories

Every GitHub repository is either **public** (anyone on the internet can read it) or **private** (only you and people you explicitly invite can read it). You can change this setting at any time.

| **Visibility** | **Who can read** | **Cost** | **When to use** |
| --- | --- | --- | --- |
| **Public** | Anyone on the internet | Free, unlimited | Open code, manuscripts ready to share, public datasets, lab websites, the Implementation Guide |
| **Private** | You + invited collaborators | Free, unlimited collaborators (since 2019) | IRB-regulated content, sensitive data, copyrighted corpora, manuscripts in progress, grant proposals |

> 🔒
>
> **Private repositories on GitHub are genuinely free and genuinely unlimited.** This changed in April 2019, and many faculty are still operating on out-of-date assumptions. There is no per-collaborator cost, no storage cap relevant to most lab use cases, and no expiry.

## 3.2 What GitHub Is *Not*

GitHub is excellent at some things and mediocre at others. Knowing the boundaries prevents misuse.

> 🚫
>
> **GitHub is NOT:**
>
> - **A bulk data store.** Repos work best under ~1 GB total and ~100 MB per file. Use OSF, Zenodo, Dropbox, or institutional storage for bulk data; link to it from the repo.
> - **A backup service.** GitHub stores what you push; if your laptop dies before you push, the work is gone. Pair it with real backups (Time Machine, OneDrive, Backblaze).
> - **A long-term archive on its own.** Repos can be deleted, renamed, or made private. Pair public scholarly outputs with **Zenodo**, which gives a permanent DOI and never deletes.
> - **A safe place for raw IRB-restricted data.** Even on a private repo, accidental visibility shifts and the platform's audit history are not designed for HIPAA or FERPA workflows. Keep raw human-subjects data in approved institutional storage; put de-identified summaries and analysis code on GitHub.
> - **A replacement for the Open Science Framework.** OSF and GitHub are complementary. OSF excels at registrations, study materials, and DOI-stamped components. GitHub excels at code, prose, and collaborative editing. Use both, linked together (Section 8.1).

## 3.3 Permissions, Collaborators, and Organizations

**Three ways to share a repository:**

1. **Personal repo + collaborators.** You own the repo under your username; you invite others with read or write access. Good for small projects.
2. **Organization.** A shared namespace (e.g., `depaul-open-science`, `quinn-lab`, `chicago-ling-corpus`) that contains repositories owned by a *group*, not a person. Members can come and go without ownership ever transferring. **This is the right structure for a lab.**
3. **Forks.** Anyone can copy a public repo, change it on their copy, and propose changes back via a pull request. This is how external collaborators contribute to projects they don't have direct write access to.

## 3.4 Repository Hygiene & Etiquette

- **Commit messages** should explain *why*, not just *what*. "Updated file" is useless; "Added reviewer 2's suggested control analysis" is gold.
- **Pull request descriptions** should list what changed and why, link any related issues, and call out anything reviewers should pay extra attention to.
- **Issues** should have one topic each. Close them when resolved; reference them in commits with `#42`.
- **README** at the top of every repo is non-negotiable. If someone arrives on the page and can't tell what the project is in 30 seconds, the README is failing.
- **License every public repo.** "No license" means no one can legally reuse your work, defeating the point of openness. CC BY 4.0 for written content; MIT or Apache 2.0 for code.

---

# PART 4️⃣: Three Scenarios for the Lab

We'll work all three in the live demo. Pick the one that fits your work and use it as your workshop homework.

## 4.1 Scenario A: The Lab/Project Handbook

**The problem this solves.** Every lab has a OneDrive folder full of protocols, SOPs, IRB documents, onboarding instructions, equipment notes, and meeting minutes, and no one knows which version is current. New members spend their first month asking "is this still right?" Old members can't tell which protocol they used in last year's experiment.

**What the repo looks like:**

- `README.md`: about the lab, who's in it, where things are
- `onboarding/`: how to join the lab, accounts to create, expectations
- `protocols/`: synthesis procedures, transcription conventions, study protocols, codebook
- `equipment/`: instrument SOPs, calibration logs, troubleshooting
- `meetings/`: agendas and minutes, dated and searchable
- `safety/`: MSDS, emergency procedures, IRB packets
- `templates/`: boilerplate for grants, manuscripts, posters

**Why GitHub wins.** Every change has an author, a date, and a justification. Six months from now, you can answer: "What did the protocol look like when we ran the May cohort?" Disputes about "who changed the buffer concentration" become 30-second lookups. Onboarding a new student is forking the handbook into their own scratch repo.

## 4.2 Scenario B: The Manuscript & Analysis Companion Repo

**The problem this solves.** A reviewer asks "could you share the code that produced Figure 3?" Six weeks later you've stitched together a zip of files you hope is the right version. Your future self (in two years, replicating this for a follow-up) is in the same boat.

**What the repo looks like:**

- `README.md`: plain-language summary of the project, link to preprint and published paper
- `manuscript/`: the LaTeX or Quarto source of the paper, drafts and revisions
- `analysis/`: scripts or notebooks (R, Python, Stata, MATLAB, SPSS syntax) that run the analyses
- `data/`: small, de-identified data **or** a `README.md` pointing to OSF/Zenodo/repository where the bulk data lives
- `figures/`: the actual figure files in the paper, with the script that generated each one
- `CITATION.cff`: machine-readable citation info
- `LICENSE`: usually CC BY 4.0 for prose, MIT for code

**Why GitHub wins.** Reviewers can verify analyses. Other researchers can reuse them. You can release a tagged version (e.g., `v1.0-as-submitted`) so that what you uploaded with the manuscript is preserved exactly, even after you keep working on the project. Releases archive to Zenodo for a permanent DOI (Section 8.2).

## 4.3 Scenario C: The SLC Implementation Guide (today's hands-on)

**The problem this solves.** Our SLC's year-end deliverable is an *Open Science Implementation Guide* shared with the DePaul community. We could write it in a single Word doc that one person edits, or we could build it the way every modern open-source community handbook is built: as a public, citable, versioned, multi-author repository.

**What the repo looks like.** [`depaul-uni/depaul-open-science`](https://github.com/depaul-uni/depaul-open-science):

- A landing-page `README.md` describing the SLC, its members, and the guide's mission
- One markdown chapter per topic (foundations, pre-registration, open data, reproducible analysis, transparent reporting, open access, version control, open materials, integration)
- A `members/` folder where each of us has a one-page profile with our discipline and contributions
- A `resources/` folder with the curated tool list, glossary, and reading list
- A `workshops/` folder for the ORS Lunch & Learn materials
- A `CONTRIBUTING.md` with the workflow we'll practice in the workshop
- A live preview at **`depaul-uni.github.io/depaul-open-science`** (built with GitHub Pages, see Section 6.6)

**Why GitHub wins.** Every member's contribution is attributable. The guide can keep evolving after the SLC ends. Future DePaul cohorts can fork it. Each release gets a DOI via Zenodo, making the guide formally citable in CVs and grants.

**This is your workshop deliverable.** During the meeting you will edit your section of this repo, commit, open a pull request, and we'll merge it together live.

---

# PART 5️⃣: Discipline Vignettes

Five short pictures of what *your* lab on GitHub could look like.

> ⚗️
>
> **Chemistry (Kyle).** A `grice-lab` organization with one repo per ongoing synthesis project. Each repo holds the synthetic procedure (markdown), instrument data (small files; large NMR/MS spectra link out to Zenodo), ChemDraw structures (committed as `.cdx` and exported `.png`), safety notes, and the LaTeX manuscript. Issues track "what to try next." When the paper is submitted, a `v1.0-as-submitted` release is archived on Zenodo with a DOI.

> 🧠
>
> **Psychology (Kimberly, Susan).** OSF holds the pre-registration, consent forms, and stimuli (registered components with their own DOIs). A linked private GitHub repo holds the de-identified data, the R or Python analysis scripts, the Quarto manuscript draft, and the IRB-approved codebook. The repo goes public on the day of preprint posting. The OSF↔GitHub integration (Section 8.1) keeps both in sync.

> 🗣️
>
> **Linguistics (Brad).** A `chicago-spanish-english-corpus` repo with annotated transcripts (small text files version perfectly), transcription conventions in `CONTRIBUTING.md`, an issue per uncertain transcription decision, and a discussion forum for cross-collaborator interpretation calls. Each contributor's edits are attributable; the version of the corpus used in any published paper is reproducible.

> ⚖️
>
> **Criminology (Kayla).** A private repo for a qualitative coding project. The codebook lives in `codebook.md` and changes through pull requests so every coding-scheme revision is justified and timestamped. Inter-rater reliability sessions use issues for disagreements ("#27: code 4b, should this segment count?"). When the project publishes, a sanitized public repo with the analysis code is forked off; raw interview data never leaves institutional storage.

> 📚
>
> **Library / Scholarly Communication (Kelly).** A `depaul-libraries-oa-resources` repo with versioned LibGuides content, a hosted Pages site for outreach, an issue tracker for faculty requests, and a contribution workflow that lets librarians across the team propose updates without stepping on each other. The repo doubles as the canonical location for institutional OA policy guidance.

---

# PART 6️⃣: Collaboration Features

GitHub's value beyond version control comes from these features, all of which are GUI-only and free.

## 6.1 Issues: Tasks, Bugs, and Discussions

An **issue** is a numbered, threaded discussion thread attached to a repository. Use issues for:

- **To-dos** ("Add robustness check requested by Reviewer 2")
- **Bug reports** ("Figure 3 generation script breaks on Windows")
- **Open questions** ("Should we exclude participants with response times under 200ms?")
- **Decisions** ("Use AAA conventions or IPA for transcription?")

Issues support `@mentions`, file attachments, code blocks, checklists, and labels (`bug`, `manuscript`, `analysis`, `discussion`). Closing an issue happens with a click or by writing `Closes #42` in a commit message.

## 6.2 Pull Requests: Peer Review of Changes

A **pull request** (PR) is the formal mechanism for proposing changes from one branch to another. A PR is a discussion that wraps a set of commits:

1. Create a branch (e.g., `kyle/add-synthesis-protocol`)
2. Make changes on that branch
3. Open a PR back to `main`
4. Reviewers leave line-by-line comments
5. The author addresses comments with new commits
6. Reviewers approve
7. The PR is merged into `main`

This is *peer review for files*. Every merged PR creates a permanent, attributable record of "this change was proposed, this was the discussion, these reviewers approved it." For a multi-author manuscript, this is dramatically better than emailing `.docx` files around.

## 6.3 Projects: Lab Kanban

[**GitHub Projects**](https://github.com/features/issues) is a built-in Kanban / spreadsheet view across issues and PRs. Create columns like *Backlog → In Progress → Review → Done*. Drag cards. Filter by assignee, label, or milestone. **A complete lab task tracker without leaving GitHub.**

Alternatives that integrate with GitHub: Trello, Asana, Linear, Notion (which can embed GitHub issues directly).

## 6.4 Discussions: The Lab Forum

[**GitHub Discussions**](https://docs.github.com/en/discussions) is a forum-style area attached to a repo. Use it for open-ended Q&A that doesn't fit the actionable model of issues. Examples: "How do we handle missing data in the income variable?", "What's our citation style for the manuscript?". Discussions can be marked with answers and converted into issues if action is needed.

## 6.5 Wiki: Lab Handbook

Every repo has a **Wiki**, a built-in, version-controlled set of pages for documentation that doesn't fit into the file tree. Some labs use the Wiki for the handbook; others prefer the file tree. Either is fine; pick one and stick with it.

## 6.6 GitHub Pages: Free Lab Websites

[**GitHub Pages**](https://pages.github.com/) hosts a static website directly from a repo, free, with HTTPS, at `<username>.github.io/<repo-name>` (or a custom domain). Common uses:

- A lab website rendered from a `docs/` folder of markdown
- A book-style guide using Jekyll, MkDocs, Quarto, or Jupyter Book (the **Implementation Guide** uses this)
- A personal academic website
- A teaching syllabus

## 6.7 Releases & Zenodo: Citable DOIs for Code

A **release** is a named, frozen version of the repo (e.g., `v1.0`). Connect your repo to [**Zenodo**](https://zenodo.org) once, and every future release is automatically archived with a citable DOI you can put on your CV.

**Setup (5 minutes, one-time):**

1. Sign in to Zenodo with your GitHub account
2. Toggle the repo "on" in Zenodo's GitHub list
3. Make a release on GitHub
4. Zenodo automatically mints a DOI and archives the release

For academic CVs, this turns research code from "a thing on a website" into a *first-class scholarly output* with a DOI, just like a paper.

---

# PART 7️⃣: GitHub Copilot: AI for Researchers

[**GitHub Copilot**](https://github.com/features/copilot) is the AI assistant integrated across GitHub. It is free for verified academics through GitHub Education. We'll cover the three surfaces that matter for non-coders.

## 7.1 Copilot Chat on [github.com](http://github.com): Ask Anything About a Repo

On any repository's page (or the GitHub homepage), click the Copilot icon in the top-right to open **Copilot Chat**. It can answer questions about:

- The repository as a whole: "What does this project do? Summarize the README."
- Specific files: "Walk me through `analysis/figure3.R`."
- Recent activity: "What changed in the last week?"
- Concepts: "Explain what a pull request is, with an example from this repo."
- Setup: "How would I run this analysis on my Mac?"

**No coding required. No setup beyond signing in.** This is the easiest way to use AI on GitHub and is genuinely transformative for navigating an unfamiliar repo.

## 7.2 Copilot Coding Agent: Assign a Task to AI

This is GitHub's newest AI surface (general availability 2025). You can **@mention `@copilot` in any issue, or assign an issue to Copilot directly**, and it will:

1. Read the issue
2. Open a draft pull request
3. Make the requested change
4. Push commits to the PR branch
5. Wait for your review

This is genuinely useful for non-coders writing prose:

- *"@copilot, update the README to add a section on how to cite this repo."*
- *"@copilot, add Susan's profile to `members/susan-tran.md` with the same structure as the others."*
- *"@copilot, fix the broken links in `resources/reading-list.md`."*
- *"@copilot, expand the glossary to include the terms in #15."*

You review the resulting pull request like any other PR: accept, request changes, or close it. The Coding Agent never merges its own work.

## 7.3 Copilot for PR Descriptions and Issue Summaries

When opening a pull request, click the **"✨ Summary"** button to have Copilot draft the PR description from the changes you've actually made. Same for long issue threads: Copilot will summarize the discussion so a new participant can catch up in a minute.

## 7.4 Copilot in the Editor (Brief)

In VS Code, RStudio, and similar editors, Copilot offers in-line code completions and chat. We won't cover this today, but if you eventually move into more code-heavy work, it's the same Copilot license.

## 7.5 Considerations & Ethics

Reasonable concerns to know about:

- **Training data.** Public code on GitHub trained earlier Copilot models. Microsoft has since added opt-outs for repository owners and excludes private repos from training by default. See [Copilot privacy and policies](https://docs.github.com/en/site-policy/privacy-policies/github-copilot-trust-center).
- **Hallucination.** Copilot will confidently produce incorrect content. Always read what it produces; treat it like a first-draft from a smart-but-junior collaborator.
- **Attribution.** When Copilot writes substantive prose for you, disclose it the same way you'd disclose any AI assistance: in the manuscript's acknowledgments, in a `CONTRIBUTING.md` note, or in the commit message itself.
- **Bias.** Copilot reflects the patterns in its training data, including the demographic and disciplinary skews of public code.
- **Confidentiality.** Don't paste IRB-restricted data into Copilot Chat, even on a private repo. Treat the chat window like any other cloud service.

---

# PART 8️⃣: Integrations Worth Knowing

The research-tooling ecosystem connects to GitHub through these integrations.

## 8.1 OSF ↔ GitHub: The Best of Both

The [**Open Science Framework**](https://osf.io) and GitHub serve overlapping but distinct purposes:

| **OSF excels at** | **GitHub excels at** |
| --- | --- |
| Pre-registrations (with DOIs) | Version-controlled prose and code |
| Stimuli, materials, instruments | Pull requests and code review |
| Component-level DOIs | Issue tracking and project boards |
| Long-term archival | Free websites via Pages |
| Connecting to IRBs and registries | Continuous integration and AI tools |

**Connect them.** From any OSF project, *Add-ons → GitHub → Connect Account*. Choose a repo. Files in the linked repo now appear inside the OSF project, with two-way sync. Many psych and social-science workflows use OSF as the discoverable front door and GitHub as the working-prose-and-code back end. ([OSF GitHub integration docs](https://help.osf.io/article/216-connect-github-to-a-project))

## 8.2 Zenodo: DOIs for Software and Data

Covered in Section 6.7 above. The full guide: ["Making your code citable" (GitHub Docs)](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content). Zenodo's home: [`zenodo.org`](https://zenodo.org).

## 8.3 Zotero: Bibliographies in Your Repo

The [Zotero Better BibTeX](https://retorque.re/zotero-better-bibtex/) plugin can export a `.bib` file that lives in your repo and updates automatically when your library changes. Quarto, R Markdown, and LaTeX manuscripts pull from this file. Co-authors all use the same bibliography even though each maintains their own Zotero library.

## 8.4 CITATION.cff: Machine-Readable Citation

Drop a [`CITATION.cff`](https://citation-file-format.github.io/) file at the top of your repo, and GitHub renders a one-click "Cite this repository" button on the landing page that generates BibTeX, APA, and other formats. Required fields are minimal: title, authors, version, date, DOI.

---

# PART 9️⃣: Workshop Plan & Pre-Work

## 9.1 Before May 1: Pre-Workshop Checklist

> ✅
>
> **Please complete the following before Friday's meeting (15-30 minutes total):**
>
> 1. **Create a free GitHub account** at [github.com/signup](http://github.com/signup). Use your `@depaul.edu` email so the academic upgrade is straightforward. Pick a username you're willing to put on your CV.
> 2. **Apply for GitHub Education** at [education.github.com](http://education.github.com). This unlocks free Copilot Pro and other benefits. Approval takes 1-7 days; doing it now means it's ready for the workshop.
> 3. **Install GitHub Desktop** from [desktop.github.com](http://desktop.github.com) for Mac and Windows. Sign in with your GitHub account once installed.
> 4. **Star the SLC repo:** [`depaul-uni/depaul-open-science`](https://github.com/depaul-uni/depaul-open-science). This puts it on your dashboard for easy access.
> 5. **(Optional) Read** Jenny Bryan's *"Excuse me, do you have a moment to talk about version control?"* (linked above). 20 minutes, written for non-CS folks, sets up the whole workshop.
> 6. **Bring** a laptop you can install software on, a stable internet connection, and one real piece of work in mind (a protocol, manuscript draft, syllabus, or codebook) you'd like to put under version control.

## 9.2 90-Minute Agenda

| **Time** | **Activity** |
| --- | --- |
| 0:00 - 0:10 | Welcome, framing, the "FINAL_v3" hook, reproducibility tie-in |
| 0:10 - 0:25 | Concepts mapped to research vocabulary; Git vs GitHub; tour of [github.com](http://github.com) |
| 0:25 - 0:45 | Live demo: create a repo, commit via the browser, open an issue, open a PR, merge |
| 0:45 - 1:05 | **Hands-on 1 (web only):** every member edits their `members/<name>.md` in the Implementation Guide repo, commits, opens a PR, gets it merged live |
| 1:05 - 1:20 | GitHub Desktop demo + **Hands-on 2:** clone the repo, edit locally, commit, push |
| 1:20 - 1:30 | Copilot Chat & Coding Agent demo, Codespaces 30-second tour, integrations preview, homework, Q&A |

## 9.3 The Workshop Hands-On: Implementation Guide Pull Request

During the workshop, **every member contributes a real pull request** to the SLC Implementation Guide repository. Specifically:

1. Open the repo at `github.com/depaul-uni/depaul-open-science`
2. Navigate to `members/<your-name>.md`
3. Click the pencil ✏️ to edit in the browser
4. Fill in your discipline, your home unit, your research focus, and which open-science practice you've found most relevant this year
5. Scroll down → **"Commit changes"** → choose **"Create a new branch and start a pull request"**
6. Title the PR `Add member profile - <your name>`
7. Submit

We'll review and merge each one live on screen. By the end of the workshop, every SLC member is a recorded contributor to the year-end deliverable.

## 9.4 Homework (between Meeting 7 and Meeting 8)

- Initialize **one** repository for a real piece of your work: a manuscript, a protocol, a syllabus, a codebook. Doesn't have to be public yet.
- Make at least 5 commits with meaningful messages.
- Open and close one issue.
- Make sure the README answers "what is this and how do I use it?"
- Bring questions to Meeting 8.

---

# PART 🔟: Resources, Tutorials & Further Reading

A curated set; everything below is free to access.

## 10.1 Foundational Papers

- **Bryan, J. (2018).** [*Excuse me, do you have a moment to talk about version control?*](https://peerj.com/preprints/3159/) *The American Statistician*, 72(1), 20-27. **The single best read for non-coders.**
- **Perez-Riverol, Y., et al. (2016).** [*Ten Simple Rules for Taking Advantage of Git and GitHub.*](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004947) *PLOS Computational Biology.*
- **Blischak, J. D., Davenport, E. R., & Wilson, G. (2016).** [*A Quick Introduction to Version Control with Git and GitHub.*](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668) *PLOS Computational Biology.*
- **Ram, K. (2013).** [*Git can facilitate greater reproducibility and increased transparency in science.*](https://scfbm.biomedcentral.com/articles/10.1186/1751-0473-8-7) *Source Code for Biology and Medicine.*
- **Wilson, G., et al. (2017).** [*Good enough practices in scientific computing.*](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510) *PLOS Computational Biology.*

## 10.2 Interactive Tutorials (Free, Hands-On)

- [**GitHub Skills**](https://skills.github.com/): official, free, interactive courses run inside GitHub itself. Start with *"Introduction to GitHub."*
- [**The Turing Way: Version Control chapter**](https://book.the-turing-way.org/reproducible-research/vcs): accessible, written for researchers, free and open-source.
- [**Software Carpentry: Version Control with Git**](https://swcarpentry.github.io/git-novice/): classic 3-hour lesson; chapters 1-4 are GUI-friendly.
- [**Library Carpentry: Introduction to Git**](https://librarycarpentry.org/lc-git/): designed for librarians and humanities researchers; non-technical framing.
- [**Happy Git with R (Jenny Bryan)**](https://happygitwithr.com): R-flavored but the conceptual chapters (1-9) apply to anyone using GUIs.
- [**GitHub Docs: Hello World**](https://docs.github.com/en/get-started/start-your-journey/hello-world): official 10-minute walk-through using only the website.

## 10.3 Books & Free Web Books

- [**Pro Git**](https://git-scm.com/book/en/v2) by Scott Chacon and Ben Straub: the definitive Git book, free online; chapters 1-2 are non-technical.
- [**Open Science Manual**](https://book.the-turing-way.org/) (The Turing Way): entire book; the version control, reproducibility, and collaboration sections are gold.
- [**Research Software Engineering with Python**](https://merely-useful.tech/py-rse/): accessible chapters on GitHub-based collaboration.

## 10.4 Discipline-Specific Examples

- **Chemistry:** [The Open Reaction Database](https://github.com/Open-Reaction-Database/ord-data): community-curated reactions in a public GitHub repo.
- **Psychology:** [Many Labs collaborations](https://github.com/many-labs): large multi-site replication projects, fully on GitHub with OSF integration.
- **Linguistics:** [The Universal Dependencies project](https://github.com/UniversalDependencies): annotated treebanks across languages, all in GitHub.
- **Criminology:** [Open Policing Project (Stanford)](https://github.com/stanford-policylab/opp): a public criminology dataset and analysis.
- **Library / Scholarly Comm:** [SPARC's resources](https://github.com/sparcopen): open scholarly infrastructure repos.
- **Cross-disciplinary handbooks:** [The Turing Way itself](https://github.com/the-turing-way/the-turing-way): every page of the book is a markdown file in a public repo, with hundreds of contributors.

## 10.5 Deep-Dive Documentation

- [GitHub Docs](https://docs.github.com/): official, searchable, well-written
- [GitHub Desktop Docs](https://docs.github.com/en/desktop)
- [GitHub Copilot Docs](https://docs.github.com/en/copilot)
- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [GitHub Codespaces Docs](https://docs.github.com/en/codespaces)
- [Zenodo-GitHub Guide](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)
- [OSF-GitHub Add-on](https://help.osf.io/article/216-connect-github-to-a-project)

## 10.6 Cheat Sheets & Quick References

- [GitHub Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf): one-page PDF
- [GitHub Markdown Guide](https://docs.github.com/en/get-started/writing-on-github): for writing READMEs and issues
- [Choose a License](https://choosealicense.com/): for picking the right license in 30 seconds
- [Make a README](https://www.makeareadme.com/): template and guidance
- [Conventional Commits](https://www.conventionalcommits.org/): a popular convention for commit messages

## 10.7 Communities for When You Get Stuck

- [GitHub Community Discussions](https://github.com/orgs/community/discussions)
- [Stack Overflow git tag](https://stackoverflow.com/questions/tagged/git): for question-and-answer style help
- [The Carpentries Slack](https://slack-invite.carpentries.org/): friendly, beginner-welcoming
- [Open Science Framework's community](https://www.cos.io/communities)

---

# PART 1️⃣1️⃣: Glossary

- **Branch**: a parallel line of development inside a repo; lets you experiment without affecting `main`.
- **Clone**: a complete local copy of a remote repo on your computer.
- **Commit**: a labeled snapshot of changes, with author, timestamp, and message.
- **Diff**: a side-by-side comparison of two versions of a file.
- **Fork**: a personal copy of someone else's repo under your account.
- **Issue**: a numbered, threaded discussion attached to a repo.
- **Main (or master)**: the default branch of a repo, conventionally the canonical version.
- **Markdown**: a lightweight plain-text formatting syntax (`**bold**`, `# heading`, `[link](url)`) that GitHub renders into formatted prose.
- **Merge**: combining changes from one branch into another.
- **Origin**: the conventional name for the remote (usually GitHub) version of your repo.
- **Pull Request (PR)**: a proposal to merge a branch into another, with a built-in discussion.
- **Push / Pull**: sending commits to (push) or receiving commits from (pull) a remote.
- **README**: the orientation document at the top of a repo.
- **Release**: a named, frozen snapshot of a repo (e.g., `v1.0`).
- **Repository (repo)**: a project's files plus its full version history.
- **Tag**: a name attached to a specific commit, usually for marking releases.
- **Upstream**: the original repo, when you're working in a fork.

---

> 🌱
>
> **One last thought.** Version control isn't a programming skill, it's a *research* skill. Every commit you make is a small act of transparency. Every pull request is a small act of peer review. Every public repo is a contribution to the scholarly commons. The tools we'll use Friday have been adopted by every modern open-source community for one reason: they make collaborative, reproducible, attributable work *easier*, not harder. That's what we're after.


---

*Previous: [Open Access Publishing & Preprints](06-open-access.md)* - *Next: [Open Materials & Collaborative Protocols (coming May 2026)](08-open-materials.md)*

*Want to contribute? See [CONTRIBUTING.md](../CONTRIBUTING.md).*
