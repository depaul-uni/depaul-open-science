# Contributing to the Open Science Implementation Guide

Thank you for your interest in contributing! This guide is built collaboratively by the DePaul Open Science SLC and welcomes contributions from members, DePaul faculty, and the wider open-science community.

This file describes both **the workflow we use during the SLC Meeting 7 workshop** and **the long-term contribution process** afterwards. Both use the same GitHub-native tools.

---

## Quick Start (for the May 1, 2026 Workshop)

If you are an SLC member contributing your **member profile** during the workshop, this is the only section you need.

1. Sign in to GitHub at **[github.com](https://github.com)**.
2. Open the guide repo: **[github.com/depaul-uni/depaul-open-science](https://github.com/depaul-uni/depaul-open-science)**.
3. Navigate into the `members/` folder and click your file (e.g., `kimberly-quinn.md`).
4. Click the pencil ✏️ icon (top-right of the file view) to edit in the browser.
5. Replace the placeholder text with your own content. Markdown formatting (`**bold**`, `# heading`, `- bullet`) renders nicely; plain English is fine.
6. Scroll to the bottom of the page → **"Commit changes..."**.
7. In the dialog:
   - **Commit message:** something like `Add member profile - Kimberly Quinn`
   - Choose **"Create a new branch for this commit and start a pull request"**
   - Click **Propose changes**
8. On the new pull-request page, click **Create pull request**.
9. Done. The workshop facilitator will merge your PR live during the meeting.

That's the entire workflow. No terminal, no install, no Git commands. Welcome to GitHub.

---

## Long-Term Contribution Workflow

For any non-trivial change after the workshop (adding a new chapter, expanding a section, fixing a broken link), follow this workflow.

### 1. Pick or open an issue

Before starting work, **open an issue** describing what you'd like to change and why. This lets others know it's being worked on and surfaces feedback before you invest time. Use the issue templates for:

- 📝 [New section](.github/ISSUE_TEMPLATE/new-section.md)
- 💡 [Feedback or suggestion](.github/ISSUE_TEMPLATE/feedback.md)
- ❓ [Question or clarification request](.github/ISSUE_TEMPLATE/question.md)

If you're an SLC member, you can also assign yourself directly without opening an issue first.

### 2. Create a branch

Use a short, descriptive branch name. Conventions:

- `chapter/<topic>` for chapter edits, e.g., `chapter/open-data-fair-update`
- `member/<name>` for member-profile updates, e.g., `member/kelly-hallisy-update`
- `fix/<short-description>` for small fixes, e.g., `fix/broken-zenodo-link`
- `docs/<short-description>` for site / docs / metadata, e.g., `docs/add-funding-acknowledgment`

You can create a branch on the GitHub website, in GitHub Desktop, or in any GUI Git client.

### 3. Make your changes

- Stay in **markdown** (`.md`) for prose. The guide renders to a static site via GitHub Pages, and HTML inside markdown should be used sparingly.
- Keep paragraphs short and link-rich.
- For citations, use [`CITATION.cff`](CITATION.cff) format where applicable, and prefer DOI links.
- For images and diagrams, drop them in `docs/assets/` and link with relative paths.
- For external resources, prefer **stable, preferably DOI-stamped** URLs.

### 4. Commit with meaningful messages

Bad: `update`, `wip`, `fix`
Good: `Add OSF-GitHub integration section to chapter 3` · `Fix broken Zenodo link in reading list`

We loosely follow [Conventional Commits](https://www.conventionalcommits.org/), but plain English is fine. The goal: a future reader skimming the history understands *why* each change happened.

### 5. Open a pull request

When you're ready, open a PR from your branch to `main`. Use the [PR template](.github/PULL_REQUEST_TEMPLATE.md). It asks for:

- A short summary of the change
- A link to the issue (if any)
- Anything reviewers should pay attention to
- A checklist of common-sense items (no broken links, no IRB-restricted content, etc.)

### 6. Review and merge

- At least one maintainer reviews every PR before merging.
- Reviewers may request changes; respond by pushing additional commits to the same branch.
- Once approved, a maintainer merges. The contribution becomes part of the canonical guide and is reflected on the live site within a few minutes.

---

## What Makes a Good Contribution

- **Concrete over abstract.** Real workflows beat principles.
- **Discipline-aware.** The guide spans chemistry, psychology, linguistics, criminology, computing, and library science. Examples and language should not assume one field's conventions.
- **Link-rich.** Every claim, tool, or recommendation should link to a primary source.
- **Honest about limits.** When a practice is hard, expensive, or controversial, say so.
- **Cite generously.** Earlier work in this space deserves visible credit.

---

## What This Guide Is *Not*

We avoid:

- **Promotional content** for any specific commercial product, beyond practical mention.
- **Recommendations contradicting DePaul IRB, FERPA, or HIPAA guidance.** Open science does not override compliance.
- **Disrespectful or dismissive language** about any discipline, methodology, or career stage.
- **AI-generated content presented as human-authored.** If GitHub Copilot or another AI helped, disclose it in the commit message or PR description.

---

## Getting Help

- **GitHub Discussions:** [open a discussion](https://github.com/depaul-uni/depaul-open-science/discussions) for open-ended questions
- **Issues:** [open an issue](https://github.com/depaul-uni/depaul-open-science/issues/new/choose) for actionable items
- **Direct contact:** the SLC facilitator (Vahid Alizadeh, valizade@depaul.edu) for anything sensitive

---

## Code of Conduct

All participation in this project (issues, pull requests, discussions, in-person workshop interactions) is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By contributing, you agree to abide by it.

---

Thank you for helping make open science a little more accessible at DePaul and beyond. 🌱
