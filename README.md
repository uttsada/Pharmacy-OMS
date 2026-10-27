# PharmaOMS — Product Owner Case Study

A case study by **Kiki Novalia**: a web order management system that lets pharmacy
staff serialize medicine that is already packed — generate a unique serial number
per item, validate each item with a scan, and print a GS1-compliant label without
reopening the package.

**Live page:** https://uttsada.github.io/Pharmacy-OMS/

## What's inside

- The problem and proposed success targets
- An interactive prototype of the Release 1 scope (sign in → cart → serials → scan → label → release)
- Four key product decisions with their trade-offs
- A 20-week roadmap: Sprint 0 plus three releases, with gate criteria
- A 20-story backlog with MoSCoW priority and story points
- Acceptance criteria in Given / When / Then
- Definition of Done at story and release level

## Prototype

Runs entirely in the browser — no build step, no backend. Demo accounts use the
password `demo1234`:

| Username | Role |
| --- | --- |
| `rina.s` | Operator |
| `dewi.a` | Supervisor |
| `andi.p` | Admin |
| `maya.l` | Auditor |

All products, orders, people and serial numbers are fictional.

## Running it locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Publishing on GitHub Pages

Repository **Settings → Pages → Source: Deploy from a branch → `main` / `root`**.

---

© 2026 Kiki Novalia. Please ask before reusing any part of this case study.
