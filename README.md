# CalDMV Prep

A single-file, offline-friendly study app for the California Class C driver license knowledge test.

- **Learn** — seven exam-focused cheat sheets distilled from the official California Driver's Handbook.
- **Assess** — a 36-question mock exam (pass = 30/36, the real DMV standard) plus per-topic quizzes, each with instant feedback and explanations.
- 100 verified questions; answers cross-checked against the current handbook.

## Tech
Pure static HTML/CSS/JS in `index.html`. No build step, no dependencies. Progress is saved in the browser's local storage.

## Deploy (Vercel)
No configuration needed — Vercel serves `index.html` as a static site.
1. Push this folder to a GitHub repo.
2. In Vercel, **Add New → Project → Import** the repo.
3. Framework Preset: **Other** (leave build & output settings empty). Deploy.

Every future `git push` redeploys automatically.

## Updating content
Questions live in the `Q` array and cheat sheets in the `SHEETS` object, both inside `index.html`.

---
Study aid only — not affiliated with the California DMV. Verify current rules at dmv.ca.gov.
