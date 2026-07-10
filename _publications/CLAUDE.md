# _publications/CLAUDE.md

Valid categories: `books`, `manuscripts`, `conferences`, `preprints`.

## Required frontmatter

| Field | manuscripts / conferences | preprints |
|---|---|---|
| `title` | yes | yes |
| `collection` | `publications` | `publications` |
| `category` | yes | `preprints` |
| `permalink` | `/publication/<slug>` | `/publication/<slug>` |
| `excerpt` | yes | yes |
| `date` | yes | yes |
| `venue` | yes | no |
| `paperurl` | yes | yes |
| `citation` | yes | optional |
| `slidesurl` | optional | optional |

## Required body sections

| Section | manuscripts / conferences | preprints |
|---|---|---|
| `## Abstract` | yes | yes |
| `## Conference Details` | yes | no |
| `## Keywords` | yes | optional |

## Example — conferences/manuscripts

```yaml
---
title: "Paper title"
collection: publications
category: conferences
permalink: /publication/2024-01-01-slug
excerpt: 'Short summary.'
date: 2024-01-01
venue: 'Conference/journal name'
paperurl: 'https://doi.org/...'
citation: 'Authors, &quot;Title,&quot; <i>Venue</i>, year.'
---

## Abstract
...

## Conference Details
- **Conference:** ...
- **Date:** ...
- **Location:** ...
- **DOI:** ...

## Keywords
keyword1, keyword2
```

## Example — preprints

```yaml
---
title: "Paper title"
collection: publications
category: preprints
permalink: /publication/2024-01-01-slug
excerpt: 'Short summary.'
date: 2024-01-01
paperurl: 'https://www.preprints.org/...'
---

## Abstract
...
```
