---
title: "Erdős Unit Distance Explorer"
excerpt: "Interactive explorer for unit-distance graphs, comparing Erdős's 1946 lattice construction against the 2025 OpenAI construction that disproved his conjecture<br/><img src='/images/portfolio/07-erdos-unit-distance.png'>"
collection: portfolio
date: 2026-05-25
liveurl: https://erdos.crubio.fyi/
---

## Overview

Interactive explorer for unit-distance graphs on two rings: Erdős's classic 1946 lattice construction, and the construction from OpenAI's 2025 result that disproved the Erdős unit distance conjecture.

In 1946, Paul Erdős asked how many pairs of points on a plane can be at distance exactly 1 from each other. Every edge drawn in the app connects two points exactly one unit apart — the **Grid (Gauss)** mode shows Erdős's original lower bound on the integer lattice; the **CM** mode shows the cyclotomic-ring construction that proves his conjecture false, with each point participating in far more unit distances than any lattice allows.

## Key Features

- Two interactive constructions: Grid (Gauss) and CM (cyclotomic)
- Adjustable scale, glow, and rotation
- Live point/edge counters
- PNG export (phone, desktop, custom sizes)

## Impact

Makes an abstract 2025 discrete-geometry result — the disproof of a nearly 80-year-old conjecture — visually intuitive: the density difference between the two constructions *is* the counterexample, seen rather than just read.

## Technologies Used

- **[TypeScript](https://www.typescriptlang.org/)**
- **[Vite](https://vitejs.dev/)**
- **[Vitest](https://vitest.dev/)**

## Links

- **Live:** [https://erdos.crubio.fyi/](https://erdos.crubio.fyi/)
- **Paper:** [OpenAI's 2025 disproof of the Erdős unit distance conjecture](https://cdn.openai.com/pdf/74c24085-19b0-4534-9c90-465b8e29ad73/unit-distance-proof.pdf)
- **Article:** [Model disproves discrete geometry conjecture](https://openai.com/index/model-disproves-discrete-geometry-conjecture/)
