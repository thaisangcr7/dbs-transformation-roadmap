# DBS Transformation Roadmap · ISM 6346 Group 2

Week 6 group project: a Crawl/Walk/Run roadmap, governance RACI and QBR dashboard for DBS Bank's 2014–2025 digital transformation.

Live site: https://thaisangcr7.github.io/dbs-transformation-roadmap/

## Naming contract

Every page links to the others by these exact lowercase names. Don't rename them.

| File | Owner | Contents |
|---|---|---|
| index.html | Sang Thai (Member A + Site Editor) | About Us: team, target audience, benefits, novelty statement, source log; links to the three pages below |
| roadmap.html | Sang Thai (Member A, Roadmap Sequencer) | Crawl/Walk/Run roadmap with dependency annotations |
| raci.html | Jorge Ayala (Member B, Governance Designer) | RACI matrix with the Accountable rationale for each row |
| dashboard.html | Fabianne Santos (Member C, Dashboard Designer) | QBR dashboard (HTML) |

## How we work

- `main` is protected. Every page reaches `main` through a pull request approved by someone other than its author.
- Branches: `roadmap-page`, `about-page`, `raci-page`, `dashboard-page`.
- Reviewer rotation (team of three): roadmap → Jorge, raci → Fabianne, dashboard → Sang, about → Fabianne.
