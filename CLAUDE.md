# CLAUDE.md — GitHub profile repository

This repository is Manan Thakkar's **GitHub profile README**. `README.md` renders
publicly at <https://github.com/ManankumarThakkar> and is, for most recruiters and
hiring managers, the first page they see. Treat every change as a change to a
public professional landing page, not to a personal scratch repo.

**This repository is public.** Do not commit anything here that should not be
world-readable — working notes, job-search strategy, target-company lists,
compensation, or interview plans. Those belong in the private `resume-builder`
skill, not here.

## The page is not a resume

This is the single most important rule, and an earlier revision got it wrong.
The README is **forward-looking**: what Manan is building now, what he is
aiming at, how to reach him. It is not a career history.

- **What he does in general is the major part. Where he works is a small part.**
  The employer gets roughly one short section, not the page.
- Target length is about one screen. Detail belongs in the linked resume PDF.
- Industry guidance is blunt about the failure mode: the most common mistake is
  "treating your README like a resume dump with long lists of every technology
  you've ever touched and walls of badges that look impressive but say nothing."
- A strong profile does four things: says who you are and what you ship, proves
  it with real numbers, signals what work you want next, and gives one clear
  place to go.

## Audience

Hiring managers and recruiters at FAANG and top companies — **one audience**.
The page is not a teaching resource and should not be written for learners.

## Tone

Senior/enterprise positioning, not new-grad.

- Lead with substance. No "aspiring", "passionate", "highly skilled graduate",
  "countless hours", or "always up for a challenge" phrasing.
- Quantified outcomes over adjectives: "cut API latency 60%", not "skilled in
  performance tuning".
- Availability is stated once, confidently, next to the work-authorization note.
  No "actively looking", no "open to any opportunity".
- Stack stays curated to the current one. Do not re-add technologies the page
  deliberately dropped: WordPress, jQuery, Laravel, PHP, Ruby, Flutter.

## Structure

Current section order, which should be preserved:

1. Centered header — name, one-line positioning, `<kbd>` role chips, badge links
2. What I'm building now
3. What I'm looking for (availability + work authorization)
4. Selected impact (3 quantified one-liners)
5. Stack (skillicons rows + text for things without good icons)
6. Where I work (short — employer is a small part)
7. Reach me

## Do not reintroduce

Cut deliberately; should not come back unless Manan asks:

- Animated GIF header (giphy waving hand) and `readme-typing-svg` typing banner
  — he chose a static header explicitly, twice
- The u8views profile view counter
- The ~50-badge "Tech Stack" wall
- A full experience/career-history section with per-role bullets

**No GitHub stats, top-languages, or streak cards.** This is a considered
decision, not an oversight: the public repos are mostly 2021–22 grad-school
coursework (SWE645, GMU Survey, Redball, Online-Quiz, Currency-Convertor), so a
top-langs card would surface HTML/CSS/Jupyter and a contribution card would show
thin public activity. Both would undercut a Software Engineer III. Revisit only
once there is substantial public work.

## Content rules

- **Internal Walmart work** (AuthForge, Wayfinder, service names) lives in
  company repos. Describe at resume level only — no links, no code, no internals
  beyond what the resume states — and keep it brief.
- **`mcp-observatory` is the flagship public project** and the page's main piece
  of provable work: <https://github.com/ManankumarThakkar/mcp-observatory>, a
  security scanner for the MCP server ecosystem. As of 2026-09-21 it has real
  substance (analyzer with crawler/fetcher/scanner/CLI, 69 tests, CI on
  3.11/3.12 with SHA-pinned actions, CodeQL, DECISIONS.md, a design spec), so it
  **is now linked** — the earlier no-link rule applied only while the repo was
  empty.
  **Do not overclaim it.** The project is pre-launch and its own README
  describes an intended layout, not a finished one. As of 2026-09-21: only 1 of
  5 rules is implemented (`unicode_conceal`); `analyzer/triage/`,
  `analyzer/report/` and `evals/harness/` do not exist; there is no tree-sitter
  and no SARIF in the code (zero runtime dependencies); no ecosystem-wide
  numbers are published. Describe the design and say pre-launch; never present
  unbuilt stages as shipped. Re-verify before changing these claims.
- **Canonical career data** — titles, dates, bullets, metrics — lives in the
  private `resume-builder` skill at `data/profile.json`. Source facts from there
  instead of re-deriving them, and never invent a metric or title.
- `resume/Manankumar-Thakkar-Resume.pdf` is the committed resume linked from the
  header. It contains a phone number and city, permanently in git history.
- **Canonical email is `mananaiya@gmail.com`. It is the only one.**
  `thakkarmanan20@gmail.com` is retired — never reintroduce it anywhere
  (README, resume, cover letters, LinkedIn, the resume-builder profile).
- Contact surface is deliberately: email, LinkedIn, Calendly, WhatsApp.
- **No portfolio link** until the new site ships. Both `mananthakkar.tech` and
  `manankumarthakkar.github.io/portfolio` were non-resolving as of 2026-09.
- LinkedIn slug is `manan-t-93239a151`. The older `manankumar-t-93239a151` is
  stale — do not use it.
- **Never invent personal details.** Hobbies, reading lists, and interests must
  come from Manan. A "one short human line" is wanted but was left out pending
  his own words.

## Markdown gotchas

- GitHub does **not** render a single newline as a line break in `.md` files.
  Text that must break needs a blank line or an explicit `<br>`.
- Keep shields.io badge URLs ASCII. Non-ASCII label text (e.g. "Résumé") risks
  encoding problems; use "Resume" inside the URL.

## Environment notes (Claude Code on the web)

- Outbound egress is restricted. `shields.io`, `skillicons.dev` and
  `linkedin.com` all fail (`connect_rejected` / HTTP `000`). Badge and icon
  rendering **cannot be verified** from a web session — say so rather than
  claiming it renders.
- `pdftotext`/poppler is not installed, and `apt-get install poppler-utils`
  fails. To read a PDF: `pip3 install pypdf`; if it then fails with
  `ModuleNotFoundError: No module named '_cffi_backend'`, run
  `pip3 install --upgrade cffi` first.
- Public repos outside this session's scope can still be read: clone them
  anonymously through the git proxy with
  `GIT_LFS_SKIP_SMUDGE=1 git clone --depth 1 <url>`.

## Profile hygiene (outside this repo)

These cannot be done from a Claude Code session — GitHub exposes no API for
them and no tool here covers them. They are UI actions for Manan, tracked here
so they are not forgotten:

- **Pin `mcp-observatory`** on <https://github.com/ManankumarThakkar> and unpin
  the 2021–22 coursework repos (SWE645-HW2, Geroge-Mason-Survey-FullStack,
  George-Mason-Survey-BackEnd, Forgot-Password-Reset-Angular,
  Speech-Synthesis-TTS, Online-Quiz-using-Java, swe642). Pinned repos are what a
  recruiter's eye lands on before any README text.
- **Give `mcp-observatory` a description and topics.** As of 2026-09-21 it has
  neither, and a pinned card renders the description — an empty one wastes the
  pin. Suggested description: "Read-only security scanning for the MCP server
  ecosystem, published with its own measured error rate. Pre-launch." Suggested
  topics: `mcp`, `model-context-protocol`, `security`, `static-analysis`,
  `supply-chain-security`, `python`.
- Consider archiving the coursework repos rather than deleting them, so they
  stop reading as current work.
