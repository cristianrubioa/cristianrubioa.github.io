# _portfolio/CLAUDE.md

## Required frontmatter

| Field | Required |
|---|---|
| `title` | yes |
| `excerpt` | yes — must include `<img src='/images/portfolio/<slug>.png'>` |
| `collection` | `portfolio` |
| `date` | yes |
| `published: false` | optional — draft entries only |
| `liveurl` | optional — set only if `## Links` has a `**Live:**` bullet; must be the same URL, shown on the `/portfolio/` listing card |

## Preview image

500x300px. All preview images referenced from `excerpt` must match this size.

## Body section order

Fixed order, product-first then technical:

1. `## Overview` — required
2. `## Key Features` — required
3. `## Impact` — required
4. `## Technologies Used` — required
5. Optional, only if applicable, in this block: `## Evaluation Metrics`, `## Use Cases`, `## Installation`, `## Recognition`, `## Publication`
6. `## Links` — required
7. `## Acknowledgements` — optional (not `Contributors`, not `Acknowledgement` singular)

`## Links` bullet names, use exactly these when applicable:

| Bullet | When |
|---|---|
| `**GitHub Repository:**` | repo is public — omit entirely if private |
| `**Live:**` | project has a deployed demo (canonical name — not `Demo`, `Try it`, `Live Demo`) |
| `**Deep dive:**` | optional, links to a more detailed external write-up or video. Omit when no such content exists |

## Private repos

If the project's repo is private: omit `**GitHub Repository:**` from `## Links`, and omit `## Installation` entirely (no point documenting install steps nobody can follow). Prefer `**Live:**` instead.

## Example

```yaml
---
title: "Project Title"
excerpt: "Short summary<br/><img src='/images/portfolio/slug.png'>"
collection: portfolio
date: 2024-01-01
liveurl: https://example.com
---

## Overview
...

## Key Features
- ...

## Impact
...

## Technologies Used
- ...

## Links
- **GitHub Repository:** [...](...)
- **Live:** [...](...)
- **Deep dive:** [...](...)
```
