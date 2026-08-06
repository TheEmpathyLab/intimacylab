# Session log

A dated history of setup work on the Intimacy Lab splash page, kept for historical reference.

## 2026-08-04 — Placeholder splash page built and shipped

- Built `index.html`: a single self-contained placeholder page. Title "intimacy lab", subtitle "a much needed NSFW empathetic venture," byline linking to shelton@empathylab.io.
- Design system: dark aubergine background (`#170f13`), blush/ember accents (`#e7a8a0`, `#d98c5f`), Fraunces (italic display) + Inter (body) + IBM Plex Mono (labels). Signature motif is a slow "breathing" glow behind the wordmark paired with a heartbeat pulse-line along the bottom edge.
- Iterated per feedback: removed the "in development" eyebrow label; rebuilt the pulse-line as a seamlessly looping CSS `background-position` tile (the original SVG dash-offset version visibly jumped at loop reset); kept the 18+ notice; changed the footer line to "18+ · currently in threeplay (listening, learning, loving)."
- `git init`'d the local repo and made the initial commit.
- Confirmed the target GitHub account is `TheEmpathyLab` (not `provenancelabel`, a different project also authenticated in the local `gh` CLI). Pushed to `github.com/TheEmpathyLab/intimacylab`, merging in the repo's existing `README.md`/`LICENSE` (unrelated histories, no conflicts).
- Switched `gh`'s active account to `TheEmpathyLab` so it's the default for future Intimacy Lab work.
- Noted hosting stack for this project: Digital Ocean, Sendgrid, Stripe, Namecheap, and Gmail (for now) — same platforms as Shelton's other sites.

## 2026-08-06 — Session captured for historical reference

- Added this log, plus a persistent project-memory note summarizing the stack, GitHub account, and design tokens above, so future sessions don't need to re-derive them.
