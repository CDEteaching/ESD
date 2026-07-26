# CDE ESD Services — Home Page

> **Target repo:** [github.com/CDEteaching/ESD](https://github.com/CDEteaching/ESD)
> **Target live URL:** https://cdeteaching.github.io/ESD/

Home page for CDE's Education for Sustainable Development (ESD) services. It is the hub the
hexagon diagram points to: one hexagon per service category, five of which describe services that
live outside this repo (mentoring, individual/institutional capacity strengthening, networking,
study programmes), and one — *knowledge resources & materials* — which links out to the existing
[cdeteaching.github.io](https://cdeteaching.github.io) landing page.

---

## What this repo contains

| File | Purpose |
|------|---------|
| `index.html` | The complete home page — single self-contained file, no build step |
| `README.md` | This file |
| `cde_logo.jpg` | CDE logo fetched from www.cde.unibe.ch |

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


## Design

Same brand system as `cdeteaching.github.io` (Inter typeface, CDE green/teal, no JS framework).
Category colors match the hex diagram 1:1 — see `:root` custom properties at the top of `index.html`.

## License

Page code released under [MIT](https://opensource.org/licenses/MIT). Any linked teaching materials
retain their own license (CC BY 4.0 by default across CDEteaching repos).

---

*Centre for Development and Environment (CDE) · University of Bern · [www.cde.unibe.ch](https://www.cde.unibe.ch)*
