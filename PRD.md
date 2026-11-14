# Product Requirements Document — SADEEM OUTPOST 72

## Product
A Roblox cooperative narrative and STEM mission trainer, set in 2045, featuring Saudi astronauts and a fictional abandoned Moon/Mars base.

## Users and goal
Primary educational audience: ages 7–12. Intended play: 1–4 players, including cooperative crews. Players learn to balance engineering constraints and explain why a decision helps one system while costing another.

## Core flow
Briefing → destination selection → cinematic travel → base repair → destination exploration → three lost-message fragments and puzzle → 72-hour survival → second destination → final report.

## Core functional requirements (target design)
- FR1: Brief tutorial, accessible controls, clear goals, and readable feedback.
- FR2: Moon/Mars selection and location-specific educational content.
- FR3: Multiplayer lobby with host/start flow, maximum four players, synchronized mission state.
- FR4: Interactable base equipment for power, oxygen, communications and shielding.
- FR5: Three discoverable message fragments and a solvable, testable archive puzzle.
- FR6: 72 simulated hours with visible resource indicators, timed hazards, and win/loss outcomes.
- FR7: Every major choice has a cost or consequence, and the result is explained in simple language.
- FR8: NASA archive entries identify source, mission/date where relevant, and whether data are archived or live.
- FR9: A final report summarizes resource outcomes, scientific observations, and choices.

## NASA-grounded mechanics (planned; not verified as implemented)
- DONKI solar events → solar hazard scenario; archived event dates and types shown.
- Mars Trek / Mars mission data → Mars terrain and site information.
- Lunar LRO/LOLA → lunar terrain and site choice.
- OSDR/RadLab → contextual radiation and health education, with correct measurement units and context.
- CSA food production toolkit → greenhouse trade-off educational material (partner resource, not NASA data).

## Acceptance tests
1. Player can start, understand objectives and complete the tutorial without external explanation.
2. Selecting Moon vs Mars changes the mission environment and data cards.
3. Resource actions change at least two linked outcomes (e.g. energy and oxygen).
4. All three fragments can be found, assembled, and lead to a valid puzzle solution.
5. A hazard can be mitigated with a meaningful resource cost.
6. Multiplayer users see consistent shared resource state.
7. The 72-hour timer can reach a clear win/loss state and produce a final report.
8. Every NASA-derived fact shown has a source and is not labeled live unless fetched live.

## Scope note
These are planned requirements. Implementation must be checked against the Roblox place before claiming completion.
