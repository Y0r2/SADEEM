# NASA Data and Sources — SADEEM | OUTPOST 72

This document lists the NASA resources that inspired SADEEM's mechanics, how each is (or is planned to be) used in gameplay, and its current verification status.

> **SADEEM is an independent educational project and is not endorsed by NASA.**
> The story (Saudi crew, Outpost 72, 2045) is fictional. Resource numbers (power, oxygen, shielding, etc.) are **game-balance values**, not NASA measurements.

## Status legend
- **Planned** — in the design, not yet confirmed in the Roblox build.
- **Implemented (archived)** — fixed data embedded in the game, labeled as archived.
- **Implemented (live)** — fetched live at runtime. *None verified yet.*

## Sources

| Resource | Link | Gameplay use | Data type | Status |
|---|---|---|---|---|
| NASA Open APIs | https://api.nasa.gov/ | Entry point to NASA public APIs | n/a | Planned |
| DONKI (Space Weather Database) | https://ccmc.gsfc.nasa.gov/tools/DONKI/ | Solar hazard scenario; show archived event type and date | Archived | Planned |
| Mars Trek | https://trek.nasa.gov/mars/ | Mars terrain and landing/site information | Archived | Planned |
| Lunar Reconnaissance Orbiter (LRO) / LOLA | https://trek.nasa.gov/moon/ | Lunar terrain and site choice | Archived | Planned |
| NASA Open Science Data Repository (OSDR) / RadLab | https://osdr.nasa.gov/ | Radiation and health education, with correct units and context | Archived | Planned |


## Labeling rules
1. Every NASA-derived fact shown in-game must name its source (and mission/date where relevant).
2. Data are labeled **Archived** unless fetched live at runtime.
3. Fictional events and game-balance numbers must not be presented as NASA facts.

## Verification
Live API integration is **not yet verified**. Update the Status column only after testing in the Roblox build (see [TESTING.md](../TESTING.md)).

## Asset licenses
*(List third-party models, sounds, images and their licenses here before submission.)*
