# CLAUDE.md — GitHub profile repository

This repository is Manan Thakkar's **GitHub profile README**. `README.md` renders
publicly at <https://github.com/ManankumarThakkar> and is, for most recruiters and
hiring managers, the first page they see. Treat every change as a change to a
public professional landing page, not to a personal scratch repo.

**This repository is public.** Do not commit anything here that should not be
world-readable — working notes, job-search strategy, target-company lists,
compensation, or interview plans. Those belong in the private `resume-builder`
skill, not here.

## Audience and tone

The page is written for a senior/enterprise audience: experienced-engineer
positioning, not new-grad.

- Lead with current title and substance. No "aspiring", "passionate", "highly
  skilled graduate", "countless hours", or "always up for a challenge" phrasing.
- Quantified outcomes over adjectives: prefer "cut API latency 60%" to "skilled
  in performance tuning".
- Availability is stated once, confidently and without urgency, next to the
  work-authorization note. No "actively looking", no "open to any opportunity".
- Skills stay curated to the current stack. Do not re-add technologies the page
  deliberately dropped: WordPress, jQuery, Laravel, PHP, Ruby, Flutter.

## Removed on purpose — do not reintroduce

The 2026-09 rewrite cut these as new-grad signals. They should not come back
unless Manan asks for them explicitly:

- Animated GIF header (giphy waving hand) and the `readme-typing-svg` banner
- The u8views profile view counter
- The ~50-badge "Tech Stack" wall, replaced by a curated skills table
- Commented-out GIF social blocks

Badges are now used sparingly, only for the four header links (resume, LinkedIn,
email, Calendly).

## Structure

Preserve this section order:

1. Name, title line, header badge row
2. Summary (two paragraphs) + availability / work-authorization line
3. Focus areas (table)
4. Experience — Walmart roles with bullets, then an "Earlier" table
5. Selected AI work
6. Technical skills (table)
7. Education
8. Get in touch

## Content rules

- **Internal Walmart work** (AuthForge, Wayfinder, service names) is described at
  resume level only: no repo links, no code, no internals beyond what the resume
  already states. Keep these summaries publicly shareable.
- **Canonical career data** — titles, dates, bullets, metrics — lives in the
  private `resume-builder` skill at `data/profile.json`. Source facts from there
  instead of re-deriving them, and never invent a metric or title.
- `resume/Manankumar-Thakkar-Resume.pdf` is the committed resume linked from the
  header. It contains a phone number and city, which are therefore permanently in
  this repo's git history.
- Contact surface is deliberately: email, LinkedIn, Calendly, WhatsApp.
- **No portfolio link** until the new site ships. Both `mananthakkar.tech` and
  `manankumarthakkar.github.io/portfolio` were non-resolving as of 2026-09 and
  were removed. Re-add a single canonical link once a site is live.
- LinkedIn slug is `manan-t-93239a151`. The older `manankumar-t-93239a151` is
  stale — do not use it.

## Markdown gotchas

- GitHub does **not** render a single newline as a line break in `.md` files.
  Text that must break needs a blank line (new paragraph) or an explicit `<br>`.
  Several lines in the rewrite were bugs for exactly this reason.
- Keep shields.io badge URLs ASCII. Non-ASCII label text (e.g. "Résumé") risks
  encoding problems; use "Resume" inside the URL.

## Environment notes (Claude Code on the web)

- Outbound egress is restricted: `shields.io`, `linkedin.com` and similar return
  HTTP `000`. Badge rendering and external links **cannot be verified** from a
  web session — say so rather than claiming they render.
- `pdftotext`/poppler is not installed, and `apt-get install poppler-utils`
  fails. To read a PDF: `pip3 install pypdf`; if it then fails with
  `ModuleNotFoundError: No module named '_cffi_backend'`, run
  `pip3 install --upgrade cffi` first.
