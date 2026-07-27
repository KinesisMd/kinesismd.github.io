# KINESIS MD — One System (review site)

Private preview of the KINESIS MD "One System" scroll experience and its supporting docs.
Hosted on GitHub Pages, deploys on push to `main`. All pages are `noindex` (link-only).

## Pages
- `index.html` — **Site V2** (current design; the new story)
- `v1.html` — Site V1 (earlier design, for old-vs-new comparison)
- `storyboard.html` — V2 storyboard + full copy deck
- `brand.html` — brand guide (story, voice, color, type, elements)
- `roadmap.html` — H2 2026 roadmap

The "···" menu (top-right of each page) flips between them.

## Notes
Each page is a self-contained HTML file (fonts/images/JS inlined) — nothing to 404, no build step.
Canonical editable source lives outside this repo in `website-redesign/v2/`
(`KINESIS - One System V2.html` + `motion-study/*.js`). This repo can be refactored into
split source files later without changing the live URL.

Mobile-first: verified at 360 / 390 / 430 px. Desktop unchanged from the original design.
