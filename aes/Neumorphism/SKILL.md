---
name: neumorphism
description: Neumorphism ("Soft UI", late 2019–2021) is a low-contrast interface aesthetic in which buttons, cards, tiles and widgets appear extruded from or dented into a background of the exact same matte color — off-white, light gray, soft blue or pastel, with a charcoal dark-mode variant. Its signature is the paired shadow rule: one soft light shadow top-left, one soft dark shadow bottom-right, inverted to inner shadows for pressed states, with rounded corners and no borders anywhere. Typical subjects are app screens, widget panels, icon tile grids, toggles/sliders/clocks and soft plastic hardware renders such as keyboards and remotes.
metadata:
  tier: Rich
  community: 0
  neighbors: [Glassmorphism, Claymorphism, Flat Design, Skeuomorphism, Minimalism]
  n_images_on_disk: 14
  visual_payload: sheets=2 exemplars=2 individual=0
  source: https://aesthetics.fandom.com/wiki/Neumorphism
  skill_version: v2
  generated_by: qwen skill-writer pipeline
  generated_on: 2026-09-06
  text_license: CC-BY-SA 3.0 (Aesthetics Wiki)
---

# Neumorphism (Soft UI / New Skeuomorphism)

Neumorphism is a user-interface design trend of the late 2010s that treats the screen as a single sheet of soft, matte material — extruded plastic or embossed paper — from which every element is pressed out or pushed in. Nothing floats, nothing is layered: a button is not placed *on* the surface, it *is* the surface, deformed. Shapes are defined exclusively by shadow physics rather than borders or color contrast, which gives the whole style its whisper-quiet, tactile, almost haptic character. Conceptually it sits midway between Skeuomorphism's heavy material realism and Flat Design's borderless color planes, and it lived a short, intense viral life on Dribbble and Behance around 2020 before accessibility criticism pushed it aside in favor of Glassmorphism.

## Visual Identity

### Palette

The rule is monochromy: background and elements share one base color, and legibility comes from shadow, not hue. The dominant family is cool off-white and light gray; soft blue and muted pastels are the sanctioned tints; a fully dark charcoal monochrome variant exists (attested in the corpus by matte black hardware renders) and obeys the same shadow logic with inverted values. Saturated color appears only as a tiny accent — a toggle knob, a dot, a glyph — never as a field.

| Role | Hex range (rule, not recipe) |
|---|---|
| Base surface (light mode) | `#E6E9F0` – `#F2F4F8` (cool off-white / light gray); warm paper variant `#EFEDE8` – `#F4F1EC` |
| Tinted bases | soft blue `#DCE6F2` – `#C9D8EC`; lavender `#E2E0F0`; blush `#F3E3DE`; peach `#F5E6DA` |
| Light shadow (top-left) | `#FFFFFF` – `#FDFEFF`, soft and diffuse |
| Dark shadow (bottom-right) | `#A9B0C0` – `#C6CBD6`, i.e. a gray-blue several steps below the base, never black |
| Dark-mode base | `#1E2023` – `#2E3134`, with `#000000`-ish dark shadow and `#3A3E43` – `#4A4E54` light shadow |
| Sparse accent | one cobalt/azure `#3E7BFA` – `#4A6CF0`, or coral `#F0705A`, kept under ~5% of canvas |
| Typography ink | slate gray `#3A4150` – `#5A6272`, never pure black |

Faint pastel gradient washes (peach-to-lavender waves, a soft sun glow) may breathe at the edges of an otherwise monochrome canvas; they are ambient atmosphere, not element fills.

### Signature motifs, ranked by how firmly the text documents them

1. **The dual-shadow extrusion.** Every raised element carries exactly two shadows: a light one on the top-left edge (the light source) and a dark one on the bottom-right. This pair is the style's fingerprint; without it, nothing else reads as neumorphism.
2. **Element-as-surface monochromy.** Buttons, cards, dials and tiles are the same solid color as the background; depth is the only differentiator.
3. **Pressed/inset states.** Interaction is shown by inverting the shadows: inner shadow top-left, inner highlight bottom-right, so the element looks dented into the sheet. Raised and inset states often appear side by side (an "on" toggle sunk into its track, a keypad with alternating convex and concave keys).
4. **Rounded corners and soft edges everywhere.** Generous radii, circles, squircles and pill shapes; sharp 90° corners and hard outlines are essentially absent.
5. **No borders, no strokes.** Contours exist only where shadow meets highlight.
6. **Extruded plastic / embossed paper material.** Matte, slightly powdery, uniformly thick — like vacuum-formed plastic or pressed pulp, never glossy, never transparent.
7. **Shallow, quiet depth.** Extrusion height is a few millimeters of implied relief; panels hover just above the ground plane on a soft ambient occlusion shadow.

### Materials and textures

One material per image: matte soft-touch plastic, silicone, or thick embossed paper. Surfaces are uniform and poreless with a subtle powdery grain; highlights are broad and diffuse, never specular. There is no wood, leather, metal, glass, fabric, stitching or texture map of any kind — the material is abstract "processed softness."

### Recurring subjects

The text documents the style almost exclusively as interface design, and the corpus agrees: mobile app screens (banking, VPN, weather, music), widget and control-center panels with clocks and toggles, grids of app-icon tiles, dashboards, cards, pill buttons, sliders, radio dots, calculators, keypads. A secondary subject family extends the same logic to physical objects rendered as concept products: MIDI keyboards, remotes, thermostats, switches, headphones — any hardware reimagineable as a single slab of soft matte plastic with extruded and inset controls. Icon sets and icon-tile grids (including the partial macOS Big Sur adoption) form a third, looser ring.

### Composition and lighting

- **Lighting:** a single diffuse light source from the top-left (occasionally top-right, but always one direction, consistently). Wide penumbra, no cast shadows with hard edges, no reflections, no rim light.
- **Composition:** centered and symmetrical or gently gridded. A lone panel or phone floating on a seamless same-hue ground; an even grid of square tiles with generous gutters; a full-bleed app screen with cards stacked in calm rows. Margins are large, content sparse, hierarchy flat.
- **Focal devices:** one oversized thin-weight numeral (a clock readout), a single dial, or one accent-colored control carrying the only saturated pixel in frame.
- **Typography:** geometric or neo-grotesque sans-serifs in light/medium weights, slate-gray ink, letter-spaced small caps for labels, thin dividers replaced by spacing.

## Mood & Values

Calm, clinical, hygienic, haptic. Neumorphism sells the pleasure of pressing things: soft keys that yield, dials that sink, switches that click into recesses. Its stated values are minimalism, soft realism, tactile interaction and cleanliness — a world with no noise, no edges, no dirt, lit by window light on a white desk. The flip side, loudly noted by its critics, is fragility: contrast so low the interface dissolves in sunlight, beauty prioritized over legibility. That tension — serene tactility versus near-invisibility — is part of the style's identity.

## Era & Origins

Coined in 2019 by Jason Kelly and Michał Malewicz as a portmanteau of "new" and "skeuomorphism," the style went viral through Alexander Plyuto's 2019 Dribbble banking-app mockup, which replaced skeuomorphic wood and leather with a clean semi-realistic soft plastic. It peaked through 2020 on Dribbble and Behance, was partially absorbed by Apple's macOS Big Sur (November 2020) in its icon geometry and translucency, and declined by 2021 under UX criticism of its accessibility, ceding ground to Glassmorphism. It survives as a recognizable period style and a recurring revival vocabulary rather than a living mainstream practice.

## Generation Guidance

**Principles.**
1. One canvas, one material, one color: elements are deformations of the background, not objects on it.
2. Two shadows per raised element — light top-left, dark bottom-right — and their inversion (inner shadows) for pressed, active or inset states.
3. Zero strokes, zero borders; silhouette comes from shadow differential alone.
4. Keep element-to-background contrast deliberately low; let ink and the single accent carry readability.
5. Round everything: corner radii, pill terminals, circular dials, squircle tiles.
6. Light with one soft diffuse source; matte surfaces only; depth shallow and ambient.
7. Restraint in content: few elements, generous whitespace, quiet typography.

**Variation axes.**
- *Subject:* any interface artifact (app screen, widget, dashboard, icon grid, toggle, slider, clock, keypad) or any physical object recast as soft matte plastic (keyboard, remote, thermostat, console, switch panel, toy); even an abstract poster of extruded and inset geometric forms qualifies if the shadow physics hold.
- *Color handling:* cool off-white/light gray is default; soft blue, lavender, blush or peach monochromes are equally correct; a charcoal dark-mode version is correct; edge-washes of pastel gradient and one small saturated accent are optional seasonings.
- *Composition:* lone centered panel, orthogonal tile grid, full-screen UI, three-quarter hardware render, or macro close-up of a single button pair (raised vs. pressed).
- *Lighting:* intensity may range from whisper-soft embossing to slightly deeper relief, and the source may sit top-left or top-right, but it must remain single, diffuse and consistent.
- *Mood:* from clinical laboratory calm to warm pastel playfulness.

A correct image can use any subject within this range; it should echo the style's rules, not any reference image. A neumorphic still life of kitchen timers or a dark-mode car dashboard, never seen in any reference, is fully in style if the monochrome surface, dual shadows, inset states and rounded softness are honored.

**Avoid.**
- Borders, outlines, strokes, or hairline rules defining shapes.
- Transparency, background blur, frosted glass, or light semi-transparent edge strokes (Glassmorphism).
- Puffy inflated 3D volumes in vibrant per-object pastels with deep float shadows (Claymorphism).
- Flat color blocks with no shadows, hard "long shadows," or bold high-contrast palettes (Flat Design).
- Literal real-world materials: wood grain, leather, stitching, brushed metal, glass reflections (Skeuomorphism).
- Glossy specular highlights, mirror reflections, chrome, bevels with hard edges.
- Pure black text, pure white cards on dark grounds, or any high-contrast figure/ground split.
- Sharp 90° corners, pointed shapes, thin angular iconography.
- Multiple or conflicting light sources; hard-edged cast shadows.
- Busy layouts, photography, outlined illustration, decorative patterns, multi-hue gradients painted across element fills.

## Discrimination Cues

| Neighbor | Tell that separates it from Neumorphism |
|---|---|
| **Glassmorphism** | Glass panels are semi-transparent with visible blurred background behind them, float *above* the wallpaper, and carry a light semi-transparent white border stroke. Neumorphic elements are opaque, same-color as the ground, borderless, and extrude *from* it. |
| **Claymorphism** | Clay objects are chunky inflated 3D bodies in vibrant pastels, clearly separate from the background, with deep outer drop shadows plus inner shadows for puffiness. Neumorphic relief is shallow, monochrome, and continuous with the surface. |
| **Flat Design** | Flat work has no shadow physics at all (or stylized hard long shadows), uses bold contrasting color blocks and crisp edges. Neumorphism is monochrome and entirely shadow-defined. |
| **Skeuomorphism** | Skeuomorphism imitates specific real materials — wood, leather, metal, paper texture, stitching — with high-detail realism and often gloss. Neumorphism's material is abstract soft plastic/embossed paper with no literal texture reference. |
| **Minimalism** | Minimalism may share the sparse layout and muted palette but permits flat fills, thin borders, black-on-white contrast and no depth cues. Neumorphism is minimalism *plus* tactile shadow physics; remove the dual shadows and it stops being neumorphism. |

**One-glance test:** same-color element and background, no outline, one soft light shadow top-left plus one soft dark shadow bottom-right, rounded corners, matte plastic feel, contrast barely there. If all five hold, it is neumorphism.

---

*Skill written from Aesthetics Wiki text (CC-BY-SA 3.0) and 4 reference image(s) sampled from 14 on the wiki. Source: https://aesthetics.fandom.com/wiki/Neumorphism*