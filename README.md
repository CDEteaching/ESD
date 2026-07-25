# CDE ESD Services — Home Page

> **Target repo:** [github.com/CDEteaching/ESD](https://github.com/CDEteaching/ESD)
> **Target live URL (once Pages is enabled):** `https://cdeteaching.github.io/ESD/`

Home page for CDE's Education for Sustainable Development (ESD) services. It is the hub the
hexagon diagram points to: one hexagon per service category, five of which describe services that
live outside this repo (mentoring, individual/institutional capacity strengthening, networking,
study programmes), and one — *knowledge resources & materials* — which links out to the existing
[cdeteaching.github.io](https://cdeteaching.github.io) landing page.

---

## ⚠️ Before publishing — review needed

The card text for five of the six service categories is **drafted placeholder copy**, written from
the category names alone (no source material was available in the vault). Each is marked with a
`draft` flag in the page itself. Review and rewrite before this goes live:

- [ ] Mentoring & Coaching
- [ ] Individual Capacity Strengthening
- [ ] Networking & Exchange within CoP
- [ ] CDE Study Programmes & Continuing Education
- [ ] Institutional Capacity Strengthening

Only **Knowledge Resources & Materials** is real/confirmed — it links to the live CDE Teaching site.

All five draft cards currently link out to `https://www.cde.unibe.ch` as a placeholder "Contact CDE"
— replace with real service-specific URLs or contact paths once known.

---

## What this repo contains

| File | Purpose |
|------|---------|
| `index.html` | The complete home page — single self-contained file, no build step |
| `README.md` | This file |

---

## Structure

1. **Hero** — About tagline + interactive hex diagram (all six categories, each linking either to an on-page anchor or, for knowledge resources, out to CDE Teaching)
2. **About** (`#about`) — CDE's ESD mission/framing, plus the draft-status banner
3. **Services** (`#services`) — one card per category, anchors matching the hex diagram (`#mentoring`, `#individual`, `#networking`, `#study`, `#institutional`, `#knowledge`)
4. **Footer** — CDE contact, links, license

## Local preview

```bash
start index.html         # Windows
open index.html          # macOS
```

## Deployment

Once content is reviewed:
1. Push `index.html` (and this `README.md`) to the `main` branch of `CDEteaching/ESD`
2. Enable GitHub Pages (Settings → Pages → source: `main`, root)
3. Update the green "knowledge resources" hex on `cdeteaching.github.io`'s own page if you want it
   to link back here instead of (or in addition to) `#courses`

## Design

Same brand system as `cdeteaching.github.io` (Inter typeface, CDE green/teal, no JS framework).
Category colors match the hex diagram 1:1 — see `:root` custom properties at the top of `index.html`.

## License

Page code released under [MIT](https://opensource.org/licenses/MIT). Any linked teaching materials
retain their own license (CC BY 4.0 by default across CDEteaching repos).

---

*Centre for Development and Environment (CDE) · University of Bern · [www.cde.unibe.ch](https://www.cde.unibe.ch)*
