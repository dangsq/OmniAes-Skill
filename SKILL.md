---
name: omni-aes
description: OmniAes is a knowledge base of 1,040 aesthetic styles, each summarized from Aesthetics Wiki page text into structured SKILL.md documents containing visual identity rules, generation guidance, and discrimination cues.
metadata:
  source: https://aesthetics.fandom.com
  total_styles: 1040
  license: CC-BY-SA 3.0
  skill_version: v2
  generated_on: 2026-09-07
  text_license: CC-BY-SA 3.0 (Aesthetics Wiki community content)
---

# OmniAes — Aesthetic Knowledge Base

OmniAes is a curated collection of **1,040 aesthetic styles** summarized from [Aesthetics Wiki](https://aesthetics.fandom.com), each equipped with a structured SKILL.md document containing visual identity rules, generation guidance, and discrimination cues.

## Structure

- **`aes/`** — 1,040 subdirectories, one per aesthetic style
- **`aes/{Style}/SKILL.md`** — Self-contained skill document per style
- **`SKILL.md`** — This project-level overview
- **`README.md`** — Project documentation

Each SKILL.md is summarized from the original Aesthetics Wiki page text and contains:

| Section | Content |
|---|---|
| Visual Identity | Color palette, signature motifs, materials, textures |
| Mood & Values | Emotional register, cultural values, philosophical stance |
| Era & Origins | Historical timeline and cultural influences |
| Generation Guidance | Principles, variation axes, and rules for image generation |
| Avoid | Explicit anti-patterns and style boundaries |
| Discrimination Cues | How to distinguish from visually similar styles |

## Quick Start

Read any style's skill document:

```
read aes/Vaporwave/SKILL.md
read aes/Dark_Academia/SKILL.md
```

## License

- **Text/metadata**: CC-BY-SA 3.0 from Aesthetics Wiki
- See [ATTRIBUTION.md](ATTRIBUTION.md) for full details

## Source

All content summarized from [Aesthetics Wiki](https://aesthetics.fandom.com) page text.
