# RS Decision Pipeline

A single-file, dependency-free animated dashboard that visualises how RS WORLDWIDE MUSIC runs its daily work as a decision pipeline — state comes in, typed questions are scored, a gate applies the rules, and only then does code act.

**Live demo:** https://motivationp81-star.github.io/rs-decision-pipeline/

## What it shows

- **Top HUD** — decisions counter, median latency, cost per 10,000 decisions and a live confidence reading
- **Six rotating cases** — Daily Upload Round, Instagram Reply, New Part Intake, Business Inquiry, GitHub Upkeep and Channel Guard, each with its own scene colour and camera region
- **Five-column decision web** — State / In → Typed Questions → System One → Gate / Route → Code / Acts, with a dense animated graph, energy streams, travelling pulses and node-by-node decision path tracing
- **Bottom strip** — parallel question bars, a live confidence stream, the use-case grid, a `pipeline.py` sketch, a run log, the work split and the guardrails

## Guardrails baked into the demo

- Title length ≤ 100 characters, checked twice
- One channel fails → only that channel stops
- Never delete anything; originals only
- Deals and prices are decided by Vikram
- API-check before any retry

## Tech

One HTML file. Canvas 2D animation, no libraries, no build step. The counters and log are a simulated demo feed — no live account is connected.

## Run it

Open `index.html` in any modern browser, or visit the live demo above.
