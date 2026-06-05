# CLAUDE.md

Guidance for AI assistants (Claude Code and others) working in this repository.

## What this repository is

This is a **GitHub special profile repository**. The repo name (`ahmeddh/ahmeddh`)
matches the owner's GitHub username, so GitHub renders `README.md` directly on the
user's public profile page at `https://github.com/ahmeddh`.

There is **no application code, build system, test suite, or dependency manifest**.
The entire deliverable is a single Markdown file. Treat this as a *content* and
*presentation* repository, not a software project.

```
.
├── README.md     # The profile page (the only meaningful file)
└── CLAUDE.md     # This file
```

## The one rule that matters

Because `README.md` is rendered publicly on the profile, **correctness, tone, and
visual presentation are the product**. A broken badge URL, a typo, or a malformed
HTML tag is a user-facing defect. Review every change as if it were going live on a
public homepage — because it is.

## Content & style conventions

The README mixes Markdown with inline HTML. Match the existing style exactly:

- **Centered headers/badges** use raw HTML (`<h1 align="center">`, `<p align="center">`).
  Keep this pattern; do not convert to plain Markdown headings where centering is used.
- **Section headers** are `##` with a leading emoji (e.g. `## 🧭 Mission`,
  `## 🧩 What I Do`). Follow the same emoji-prefixed convention for new sections.
- **Horizontal rules** (`---`) separate every major section. Preserve them.
- **Badges** come from `img.shields.io` (`style=for-the-badge`) and tech icons from
  `skillicons.dev`. Reuse these services and the existing color palette
  (dark navy/indigo: `1C1A55`, `0D0B42`, `3F3E8A`, `09071A`; accent blue: `8EB5F7`).
- **Voice** is first-person, consultant-focused (platforms + fintech + security).
  Keep it confident, concise, and outcome-oriented. Avoid hype that isn't backed
  by a concrete deliverable.
- There is an HTML comment banner at the top of the file; keep it in sync if the
  positioning/title changes.

## Verifying changes

There is nothing to compile or test. Instead:

1. **Preview the Markdown** — confirm it renders as intended (headings, tables,
   centered blocks). GitHub's web editor preview or any Markdown previewer works.
2. **Check every link and image URL** is well-formed and reachable. Shields.io and
   skillicons.dev URLs are case- and parameter-sensitive — a mistyped param yields a
   broken image, not an error.
3. **Verify external links** (website, LinkedIn, X, Cal.com, email) point to the
   correct destinations before committing.
4. **Validate tables** render with aligned columns and no broken pipes.

## Git & workflow conventions

- The default branch is `main`.
- Commit messages so far are short and lowercase-ish, conventional-commit-flavored
  where useful (e.g. `chore: add profile README`, `Update my readme to digital
  consultant`, `remove github stats`). Keep messages short and descriptive.
- **Do not create pull requests unless explicitly asked.**
- When working under an assigned feature branch, develop, commit, and push there;
  never push to `main` without explicit permission.

## Facts to preserve (don't accidentally rewrite)

These are real biographical/professional details. Verify with the user before
changing any of them:

- **Identity:** Ahmed Djobs — Digital Consultant (Platforms & Fintech, Solution Architect).
- **Selected engagements:** ShoogirCash (CBOS national e-Wallet), PETRONAS e-Coupon,
  Healthcare Identity (US Gov), Royal Caribbean Digital Pilot. The stats and stacks
  in that table are factual claims — don't invent or inflate them.
- **Contact:** `djobs.net`, `cal.com/djobs`, `linkedin.com/in/ahmeddjobs`,
  `x.com/AhmedDjobs`, `contact@djobs.net`.

When asked to "update the profile," edit copy/badges/sections — but leave factual
claims, names, and links intact unless the user supplies new information.
