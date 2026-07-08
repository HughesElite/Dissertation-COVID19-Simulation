# COVID-19 Transmission Simulation (Dissertation)

A real-time 3D simulation built in Unity, modelling COVID-19 transmission through a population of AI-driven NPCs in a scaled urban environment.

![Simulation overview](./Production%20Project%20Screenshots/Product%20Screenshots/1.png)

## What it does

Applies a modified SIR (Susceptible-Infected-Recovered) model with proximity-based infection detection, tracking spread through up to 50 NPCs using NavMesh pathfinding. Infection checks run on a cached 0.1 second interval rather than per frame for performance.

![Infection spread](./Production%20Project%20Screenshots/Product%20Screenshots/infection-spread.png)

## NPC behaviour

NPCs follow structured routines or random movement, and once infected, adjust behaviour probabilistically — some take avoidance paths, some stay home entirely, some ignore it. This mimics real variation in social distancing compliance rather than following a single scripted response.

## Live statistics

A live R-value calculator and population statistics update in real time as the simulation runs, alongside dynamic population and weather controls.

![Statistics tracking](./Production%20Project%20Screenshots/Product%20Screenshots/statistics-tracking.png)

![Population and weather controls](./Production%20Project%20Screenshots/Product%20Screenshots/population-weather-controls.png)

## Performance

Maintained 250+ FPS with 50 active agents. Validated across 50 simulation runs, developed in four agile phases with MoSCoW prioritisation.

## Stack

C# · Unity Engine · NavMesh
