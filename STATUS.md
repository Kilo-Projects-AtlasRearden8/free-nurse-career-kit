# STATUS

## What was built

A printable freebies kit for nurses changing careers, published by Asdale Dynamics, LLC. It contains four worksheets:

1. **Skills inventory** — nursing skills mapped to transferable skills, with confidence ratings (1–5) and example space.
2. **Resume translation** — nursing-speak → plain English resume language, with adaptable example bullets and a fill-in-your-own section.
3. **Job application tracker** — printable tracker table with status legend, weekly goal, and contacts-to-nurture section.
4. **Interview prep worksheet** — STAR-method answer spaces for common interview questions, plus a post-interview thank-you template.

## Format

- `index.html` — printable HTML kit (open in any browser, print or save as PDF). Large-print friendly, no account needed, no tracking.
- `markdown/` — Markdown source versions of all four sections plus a combined `kit.md`.
- `LICENSE` — MIT License, copyright line exactly "Copyright (c) 2026 Asdale Dynamics, LLC".
- `README.md` — project overview, credits Asdale Dynamics, LLC.
- `STATUS.md` — this file.

## How to run it

1. Open `index.html` in a web browser.
2. Press Ctrl+P / Cmd+P to print, or choose "Save as PDF".
3. For a clean worksheet, disable headers and footers in the print dialog.
4. The Markdown files in `markdown/` can be read in any text editor or Markdown viewer.

No build step, no dependencies, no account, no network access required.

## Verification results

- `index.html` opens in a browser without errors (verified by loading the file).
- All required files present: index.html, LICENSE, README.md, STATUS.md, markdown/kit.md, markdown/01-skills-inventory.md, markdown/02-resume-translation.md, markdown/03-job-application-tracker.md, markdown/04-interview-prep.md.
- LICENSE copyright line matches exactly: "Copyright (c) 2026 Asdale Dynamics, LLC".
- README credits Asdale Dynamics, LLC.
- No .github/workflows files present.
- No secrets, API keys, or personal data in any file.
- Git initialized and committed with plain commit messages (no Co-authored-by trailers).

## Known gaps

- No automated test suite (the kit is static HTML/Markdown; verification is manual inspection).
- Print appearance varies slightly by browser/printer; users should preview before printing.
- No PDF is pre-generated; users save/print from their browser.
- The Markdown checkbox/rating glyphs (☐) render differently depending on the Markdown viewer/font.
