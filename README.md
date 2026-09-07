# OmniAes — Aesthetic Styles Knowledge Base

OmniAes is an open knowledge base of **1,040 aesthetic styles** (互联网美学 / 视觉风格 / 美学百科), each summarized into a structured `SKILL.md` document derived from [Aesthetics Wiki](https://aesthetics.fandom.com). Every entry documents a style's color palette, key motifs, mood, generation guidance, and how to tell it apart from visually similar styles — useful for image generation, style classification, visual retrieval, and research.

## What's Inside

| Resource | Count |
|---|---|
| Aesthetic styles | 1,040 |
| SKILL.md documents | 1,040 |
| License | CC-BY-SA 3.0 |

## Moodboard

All images are AI-generated from prompts based on each style's `SKILL.md`.

![OmniAes aesthetic style moodboard](assets/moodboard.png)

## Popular Aesthetics

Quick links to the most-searched styles. Each links to its full `SKILL.md`.

### Internet & Retro-Future
[Y2K Futurism](aes/Y2K_Futurism/SKILL.md) · [Neo-Y2K](aes/Neo-Y2K/SKILL.md) · [Y3K](aes/Y3K/SKILL.md) · [Vaporwave](aes/Vaporwave/SKILL.md) · [Synthwave](aes/Synthwave/SKILL.md) · [Signalwave](aes/Signalwave/SKILL.md) · [Frutiger Aero](aes/Frutiger_Aero/SKILL.md) · [Frutiger Eco](aes/Frutiger_Eco/SKILL.md) · [Liminal Space](aes/Liminal_Space/SKILL.md) · [Webcore](aes/Webcore/SKILL.md) · [Glitchcore](aes/Glitchcore/SKILL.md) · [Dreamcore](aes/Dreamcore/SKILL.md) · [Weirdcore](aes/Weirdcore/SKILL.md) · [Traumacore](aes/Traumacore/SKILL.md)

### Academia & Cozy
[Dark Academia](aes/Dark_Academia/SKILL.md) · [Light Academia](aes/Light_Academia/SKILL.md) · [Cottagecore](aes/Cottagecore/SKILL.md) · [Goblincore](aes/Goblincore/SKILL.md) · [Cabincore](aes/Cabincore/SKILL.md) · [Cottagegoth](aes/Cottagegoth/SKILL.md)

### Punk & Sci-Fi
[Cyberpunk](aes/Cyberpunk/SKILL.md) · [Steampunk](aes/Steampunk/SKILL.md) · [Dieselpunk](aes/Dieselpunk/SKILL.md) · [Atompunk](aes/Atompunk/SKILL.md) · [Solarpunk](aes/Solarpunk/SKILL.md) · [Biopunk](aes/Biopunk/SKILL.md) · [Aetherpunk](aes/Aetherpunk/SKILL.md) · [Afrofuturism](aes/Afrofuturism/SKILL.md) · [Retrofuturism](aes/Retrofuturism/SKILL.md)

### Cute & Kawaii
[Kawaii](aes/Kawaii/SKILL.md) · [Gyaru](aes/Gyaru/SKILL.md) · [Harajuku Fashion](aes/Harajuku_Fashion/SKILL.md) · [Lolita](aes/Lolita/SKILL.md) · [Animecore](aes/Animecore/SKILL.md) · [Fairycore](aes/Fairycore/SKILL.md) · [Kidcore](aes/Kidcore/SKILL.md) · [Mermaidcore](aes/Mermaidcore/SKILL.md) · [Angelcore](aes/Angelcore/SKILL.md) · [Devilcore](aes/Devilcore/SKILL.md)

### Dark & Alt
[Goth](aes/Goth/SKILL.md) · [Grunge](aes/Grunge/SKILL.md) · [Emo](aes/Emo/SKILL.md) · [Scene](aes/Scene/SKILL.md) · [Punk](aes/Punk/SKILL.md) · [Dark Romanticism](aes/Dark_Romanticism/SKILL.md) · [Whimsigothic](aes/Whimsigothic/SKILL.md)

### Feminine & Trend
[Coquette](aes/Coquette/SKILL.md) · [Barbiecore](aes/Barbiecore/SKILL.md) · [Old Money](aes/Old_Money/SKILL.md) · [Mob Wife](aes/Mob_Wife/SKILL.md) · [Clean Girl](aes/Clean_Girl/SKILL.md) · [That Girl](aes/That_Girl/SKILL.md) · [Vanilla Girl](aes/Vanilla_Girl/SKILL.md) · [Soft Girl](aes/Soft_Girl/SKILL.md) · [VSCO Girl](aes/VSCO_Girl/SKILL.md) · [Balletcore](aes/Balletcore/SKILL.md) · [Tenniscore](aes/Tenniscore/SKILL.md) · [Blokecore](aes/Blokecore/SKILL.md) · [Gorpcore](aes/Gorpcore/SKILL.md) · [Normcore](aes/Normcore/SKILL.md)

### Art & Design
[Minimalism](aes/Minimalism/SKILL.md) · [Maximalism](aes/Maximalism/SKILL.md) · [Brutalism](aes/Brutalism/SKILL.md) · [Art Deco](aes/Art_Deco/SKILL.md) · [Art Nouveau](aes/Art_Nouveau/SKILL.md) · [Baroque](aes/Baroque/SKILL.md) · [Rococo](aes/Rococo/SKILL.md)

## All Styles

The complete catalog of 1,040 styles is available as a CSV: [`assets/styles.csv`](assets/styles.csv) (columns: `name`, `location`, `description`).

## Directory Layout

```
OmniAes/
├── SKILL.md              # Project-level skill document
├── README.md             # This file
├── assets/
│   ├── styles.csv        # All styles with descriptions
│   └── moodboard.png     # Visual moodboard
└── aes/
    ├── Vaporwave/
    │   └── SKILL.md
    ├── Dark_Academia/
    │   └── SKILL.md
    └── ...               # 1,038 more styles
```

## SKILL.md Format

Each `aes/{Style}/SKILL.md` contains:

- **YAML frontmatter** — name, description, tier, neighbors, source URL
- **Visual Identity** — color palette (with hex codes), signature motifs ranked by importance, materials/textures
- **Generation Guidance** — principles, variation axes, "Avoid" section
- **Discrimination Cues** — comparison against visually similar styles

## License

This project is licensed under the **Creative Commons Attribution-ShareAlike 4.0 International License (CC-BY-SA 4.0)**.

- See [LICENSE](LICENSE) for the full license text.
- See [ATTRIBUTION.md](ATTRIBUTION.md) for attribution requirements.
- Content derived from [Aesthetics Wiki](https://aesthetics.fandom.com) (CC-BY-SA 3.0 community content).

## Source

All content summarized from [Aesthetics Wiki](https://aesthetics.fandom.com) page text.
