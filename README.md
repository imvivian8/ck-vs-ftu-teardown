# CK Tax vs FreeTaxUSA — Competitive S2C Teardown

3-tab analysis site (Analysis / FreeTaxUSA / CK Tax) covering the full
start-to-complete journey for a single-W-2 Wyoming filer with a
California-nonresident state-return wrinkle, on both products' desktop
web experiences.

Covers: screen-by-screen tedium comparison, guidance/jargon translation,
data-entry (W-2 import vs. manual), monetization & upsell placement,
the state-return paywall on both sides, headline findings, SWOT, and
sprint-sized improvement recommendations.

Static page — open `index.html` directly or serve the folder. All 26
evidence screenshots live in `assets/`, referenced by relative path.

Synthetic test persona throughout; no real payment or e-file occurred
in either traversal.

## Publishing to GitHub Pages

This repo was prepared locally (git pushes to github.com are blocked by
an org-level guard on the machine that authored it). To publish:

```bash
git init
git add -A
git commit -m "Add CK Tax vs FreeTaxUSA S2C teardown site"
git remote add origin https://github.com/<you>/<repo-name>.git
git push -u origin main
```

Then enable GitHub Pages for the repo (Settings → Pages → Deploy from
branch → main → /root).
