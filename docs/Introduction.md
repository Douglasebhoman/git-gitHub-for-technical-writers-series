# Introduction: Git & GitHub for Technical Writers

**Series:** Git & GitHub for Technical Writers
**Part:** Introduction
**Status:** ✅ Published
**Hashnode:** [Read on Hashnode](https://git-and-github-for-technical-writers.hashnode.dev)

---

## Overview

This series is written for technical writers who work alongside developers and need to understand the tools and workflows used in software documentation environments.

Git and GitHub are the foundation of most professional documentation pipelines. Understanding how they work — even at a basic level — makes you a more effective collaborator, a more confident contributor, and a stronger candidate for technical writing roles in any software company.

No prior experience with Git, the command line, or software development is assumed.

---

## What This Series Covers

This introduction provides the conceptual foundation for the series. It explains:

- What Git is and why it matters for documentation
- What GitHub is and how it differs from Git
- The basic workflow a technical writer follows in a Git-based environment
- Key terminology you will encounter throughout the series

Each subsequent article builds on this foundation. Read the series in order for the best experience.

---

## Why Git Matters for Technical Writers

Git is a **version control system** — a tool that records changes to files over time and allows you to navigate that history.

For technical writers, Git solves problems that tools like Google Docs and SharePoint do not:

| Problem | How Git solves it |
|---------|-------------------|
| Tracking who changed what and when | Every change is recorded with author, timestamp, and description |
| Reverting to a previous version | Any earlier state of a file can be restored at any time |
| Working on changes without affecting the live document | Changes happen on a separate branch until they are approved |
| Collaborating without overwriting each other's work | Git detects and manages conflicting changes |
| Keeping documentation in sync with code | Documentation lives in the same repository as the product it describes |

If you work in a Docs-as-Code environment — or plan to — Git is not optional. It is the infrastructure your documentation runs on.

---

## What GitHub Adds

Git is the version control system. GitHub is the **cloud platform that hosts Git repositories** and adds collaboration tools on top.

Think of it this way:

> Git tracks the history of your files.
> GitHub is where that history lives online and where teams work together.

GitHub provides:

- A central location to store and access your documentation repository
- **Pull Requests** — a structured process for proposing, reviewing, and approving changes
- **Issues** — a way to track tasks, corrections, and improvements
- **Actions** — automated workflows that can build, test, and deploy documentation
- Visual diff tools that show exactly what changed between versions

For technical writers, GitHub is where the collaboration happens. Understanding it is essential for contributing to any professional documentation project.

---

## The Basic Documentation Workflow

Most documentation contributions in a Git-based environment follow this sequence:

```
Clone → Branch → Edit → Commit → Push → Pull Request → Review → Merge
```

In plain terms:

1. **Clone** — copy the repository to your local machine
2. **Branch** — create a separate working copy so your changes don't affect the main document
3. **Edit** — make your changes to the documentation files
4. **Commit** — save your changes with a message describing what you did and why
5. **Push** — upload your changes to GitHub
6. **Pull Request** — propose your changes for review
7. **Review** — a colleague or maintainer checks the changes
8. **Merge** — approved changes are added to the main documentation

Even following this workflow at a basic level puts your documentation under proper version control and makes your contributions visible and traceable.

---

## Key Terminology

The following terms appear throughout this series. Refer back to this table whenever you encounter an unfamiliar term.

| Term | Definition |
|------|------------|
| **Repository (repo)** | A storage location for a project, containing all files and their complete change history |
| **Commit** | A saved snapshot of changes, accompanied by a message describing what was changed |
| **Branch** | An independent line of work within a repository, separate from the main document |
| **Pull Request (PR)** | A formal proposal to merge changes from one branch into another, subject to review |
| **Clone** | Copying a repository from GitHub to your local machine |
| **Push** | Uploading committed changes from your local machine to GitHub |
| **Merge** | Combining changes from one branch into another after review and approval |
| **Main branch** | The primary, authoritative version of the documentation |
| **Diff** | A visual comparison showing exactly what changed between two versions of a file |
| **CI/CD** | Automated systems that build, test, and deploy documentation after changes are merged |

---

## How This Repository Is Organised

```
git-github-for-technical-writers/
├── README.md                        ← Series index and overview
├── CONTRIBUTING.md                  ← How to suggest corrections
├── docs/
│   ├── introduction.md              ← This file
│   ├── part-1-git-basics.md
│   ├── part-2-git-vs-github.md
│   ├── part-3-versioning.md
│   ├── part-4-pull-requests.md
│   ├── part-5-cicd-pipelines.md
│   └── part-6-repo-architecture.md
└── images/
    └── (diagrams referenced in articles)
```

Each article in the `docs/` folder is the primary source for that part of the series. The published Hashnode versions mirror this content.

---

## Reading Order

Start here, then continue in sequence:

1. **Introduction** ← you are here
2. [Part 1 — Git Basics for Technical Writers](part-1-git-basics.md)
3. [Part 2 — Git vs GitHub](part-2-git-vs-github.md)
4. [Part 3 — From Editing Files to Managing Versions](part-3-versioning.md)
5. [Part 4 — Pull Requests](part-4-pull-requests.md)
6. [Part 5 — CI/CD Pipelines](part-5-cicd-pipelines.md)
7. [Part 6 — Repository Architecture](part-6-repo-architecture.md)

---

## Corrections and Feedback

If you find an error or have a suggestion, see [CONTRIBUTING.md](../CONTRIBUTING.md) for how to raise it.

---

*Written by Douglas Ebhoman — Technical Writer & Documentation Specialist*
*[LinkedIn](https://linkedin.com/in/douglas-ebhoman-757329289) · [Hashnode](https://git-and-github-for-technical-writers.hashnode.dev) · [GitHub](https://github.com/Douglasebhoman)*
