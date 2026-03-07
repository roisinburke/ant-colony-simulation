# 🐜 Ant Colony Simulation

Miniproject for the Vivarium agent-based simulation course (UPF 2026).

📄 [Project Plan](https://docs.google.com/document/d/1Bn9EGM0mxK09gDamZxnGkyCQGGfJvC4v/edit?usp=sharing&ouid=102026026231210699095&rtpof=true&sd=true)

## Files

- `miniproject_template.ipynb` — main notebook with scenario description, entity plan, and step-by-step implementation guide
- [Original Vivarium template](https://github.com/flowersteam/vivarium/blob/upf2026/notebooks/sessions/miniproject_template.ipynb) — unmodified reference notebook

## Setup

Follow the [Vivarium install instructions](https://github.com/flowersteam/vivarium/tree/upf2026/notebooks/sessions) to get the simulator running, then open the notebook from the Vivarium interface.

## How to use

The notebook is divided into sections that follow the build order:

1. **Setup** — connect to the simulator and register subtypes
2. **Entity Initialization** — assign roles, colors, and sizes to all agents and objects
3. **Behaviours** — implement forager, fighter, and predator behaviours (Step 1: no predator · Step 2: add predator)
4. **Internal States & Routines** — add energy and stress as dynamic behaviour modulators (Step 3)
5. **Environmental Dynamics** — configure food consumption and respawning
6. **Controller Routines** — stun/respawn system and territorial alarm (Step 4)
7. **Data Logging & Plots** — visualise colony dynamics after running the simulation
8. **Utilities** — inspect state, stop everything, clear logs
9. **Stretch Goals** — optional extensions (pheromone trails, queen pulse, seasonal scarcity...)

Work through the sections in order. **Save a backup copy of the notebook each time a step is working** before moving on to the next.