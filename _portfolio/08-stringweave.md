---
title: "StringWeave"
excerpt: "Convert any photo into string art — generate the pin sequence and simulate the weaving pattern for physical or digital creation<br/><img src='/images/portfolio/08-stringweave.png'>"
collection: portfolio
date: 2026-06-26
liveurl: https://stringweave.crubio.fyi/
---

## Overview

Turns any image into string art. Upload a photo, pick pins and strokes, and watch the drawing build itself — one straight line at a time. A greedy algorithm scores every candidate nail by how much it darkens the remaining image, running off the main thread so the picture emerges in real time as strokes stream to the canvas.

## Key Features

- Upload JPEG/PNG/WebP (up to 5 MB), choose 120–640 pins and up to 5,000 strokes
- Generation runs in a Web Worker, streaming line batches to the canvas as it computes
- Export the nail sequence as `.txt` or the final canvas as PNG
- Player tab replays any sequence stroke by stroke, with timeline scrubbing, step forward/back, and 0.25×–4× playback speed

## Impact

Makes string art generation — normally a slow, iterative manual process — instant and interactive, while also producing a portable pin sequence that can be followed to build the piece physically with real thread and nails.

## Technologies Used

- **[Next.js](https://nextjs.org/)**
- **[TypeScript](https://www.typescriptlang.org/)**
- **[React](https://react.dev/)**

## Links

- **GitHub Repository:** [https://github.com/cristianrubioa/stringweave](https://github.com/cristianrubioa/stringweave)
- **Live:** [https://stringweave.crubio.fyi/](https://stringweave.crubio.fyi/)
