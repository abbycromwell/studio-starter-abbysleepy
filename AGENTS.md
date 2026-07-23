# House Rules

This is a student portfolio site for the AI-Native Design Studio course.

- Every color, font size, spacing, and radius value comes from `src/styles/tokens.css` via `var(--*)`. Never hardcode hex colors or px sizes in page styles.
- No CSS frameworks, no JS frameworks. Vanilla HTML/CSS/JS inside Astro.
- `PRODUCT.md` and `DESIGN.md` at the repo root describe what this site is and how it should look. Read them before any design work.
- Full rules (images, assets, accessibility) live in `.claude/skills/design-rules/SKILL.md` — they are mandatory.
- Semantic HTML, mobile-first, WCAG AA contrast.

## Delivery Workflow

- Make every website change on a `codex/` branch and submit it through a pull request.
- After the pull request checks pass, merge it and wait for Vercel's production deployment to finish.
- Verify the production URL before reporting completion. Do not stop after a preview deployment.
