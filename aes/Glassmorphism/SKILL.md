---
name: glassmorphism
description: Glassmorphism is the 2020s UI aesthetic of translucent frosted-glass panels floating over vivid gradient backgrounds, defined by lowered fill opacity, Gaussian background blur, and thin semi-transparent white border strokes. Typical subjects are operating-system interfaces, app cards and widgets, icon grids, 3D glass renders and AR/spatial head-up displays, in palettes of electric blue, violet and magenta gradients or their pastel and dark-neon variants. Recognize it by seeing distorted, blurred color bleeding through a matte panel edge-lit by a hairline white stroke — never opaque flat fills, never glossy skeuomorphic reflections.
metadata:
  tier: Rich
  community: 0
  neighbors: [Claymorphism, Neumorphism, Cyberminimalism, Frutiger Aero, Neo-Aero]
  n_images_on_disk: 49
  visual_payload: sheets=2 exemplars=2 individual=0
  source: https://aesthetics.fandom.com/wiki/Glassmorphism
  skill_version: v2
  generated_by: qwen skill-writer pipeline
  generated_on: 2026-09-06
  text_license: CC-BY-SA 3.0 (Aesthetics Wiki)
---

# Glassmorphism

Also called **Frosted Glass** or **Acrylic Material**, Glassmorphism is a user-interface design language that mimics the physical behavior of frosted glass: panels are never fully opaque, their fill is diluted so the background shows through, and — the defining move — everything behind the panel is blurred so text on top stays readable. Coined in 2020 by designer Michał Malewicz to name a blur-heavy resurgence on Dribbble, Behance and Figma, it was subsequently codified inside real design systems (Microsoft Fluent's "Acrylic" and "Mica" brushes, Apple's "Materials" in the Human Interface Guidelines, visionOS, Samsung One UI 7, iOS 26's Liquid Glass, macOS Tahoe). It is the post-Flat-Design interface aesthetic: depth and hierarchy recovered through translucency rather than through skeuomorphic ornament.

## Visual Identity

### Palette

The color language splits into two jobs: **the background carries the saturation, the glass carries the white tint.**

- **Glass fills:** transparent white at roughly 8–45% opacity (`rgba(255,255,255,0.08–0.45)`), sometimes a transparent black tint in dark mode. Never a solid fill.
- **Border stroke:** semi-transparent white hairline, roughly 35–70% white at 1–2 px, on every panel edge.
- **Background gradients (vivid pole):** electric blue `#0A6CFF–#4CC2FF`, violet `#6C4BFF–#A78BFA`, magenta/pink `#FF3DCC–#FF9ACD`; aurora greens and orange-red blooms also appear as wallpaper fields.
- **Pastel pole:** diluted peach `#FFE3D0`, mint `#D9F7EE`, lavender `#E6E1FF`, pale cyan — same rules, lower chroma.
- **Dark-mode pole:** near-black indigo bases `#0B0B14–#1A1035` lit by neon magenta `#FF2ED4` and cyan `#29D8FF` blobs behind the frost.

Any point on this range is valid; the invariant is a saturated or luminous field *behind* a desaturated translucent plane.

### Signature motifs (ranked by how centrally the style documents them)

1. **Translucency / lowered fill opacity** — background context always leaks through the element.
2. **Background blur (Gaussian)** — the separator from mere transparency; shapes behind the panel melt into soft color blobs.
3. **Frosted, matte glass texture** — diffuse, milky, non-reflective surface (the 2020s iteration is explicitly matte, unlike 2000s gloss).
4. **Light semi-transparent white border stroke** — mimics glass thickness, lifts the panel off both dark and light backgrounds.
5. **Vivid colorful gradient backgrounds** — the amplifier that makes the frost legible; aurora blooms, candy gradients, saturated wallpapers.
6. **Floating layered depth** — panels hover above the wallpaper in stacked planes; hierarchy is expressed by blur radius, opacity and subtle shadow, never by extrusion.
7. **Rounded corners and soft ambient shadows** — inherited from Fluent-era systems; shadows exist only to seat a panel in space.
8. **Dynamic vibrancy** — the blur tints itself from whatever sits behind it (wallpaper, room, photo), the principle visionOS uses to ground windows in physical space.
9. **Gentle specular sheen** (late "Liquid Glass" variant, 2025 onward) — a soft light sweep or edge highlight; optional, and always restrained compared to Aero-era gloss.

Supporting objects seen across the style's output: floating 3D glyphs (glass orbs, cubes, inflated ribbons, folder-and-shield renders), app-icon grids on gradient wallpaper, control-center tiles, music players and dial pads, frosted taskbar and menu strips, hand cursors and fingertips touching panels, headset wearers surrounded by hovering HUD windows.

### Materials and textures

Frosted acrylic glass is the only hero material. Secondary materials are gradient light fields, soft-focus photography (for AR/spatial scenes), and occasional matte-soft 3D accents (spheres, capsules, ribbons) that sit *behind or beside* the glass to give the blur something to diffuse. Surfaces are clean: no grain, no paper tooth, no brushed metal, no chrome.

### Recurring subjects

Operating-system interfaces first and foremost — desktop windows, menus, sidebars, control centers, notification shelves, taskbars — followed by mobile app mockups (cards, widgets, tipping dials, weather and music panels), icon sets and 3D icon renders, product-marketing hero renders, and augmented-reality views where frosted windows hang in a photographed room or workshop. Abstract compositions with no UI at all (glass sheets, 3D typography cast in frosted letters) also belong, as long as the blur-translucency-stroke triad holds.

### Composition and lighting

Composition is depth-staging: two to four planes stacked at different blur and opacity levels, a hero panel centered or cascading diagonally over a gradient field, icon grids aligned over saturated wallpaper, or a single macro strip of frosted bar cropped tight. Background elements are deliberately placed as color masses so the frost has content to smear. Lighting is diffuse and even — soft studio light, backlit edge glow through panel rims, or ambient room light in AR scenes — with faint ambient-occlusion shadows under floating panels. No harsh directional key light, no cast shadow drama.

## Mood & Values

The style expresses **depth, hierarchy, modernity, seamlessness**. It feels weightless, hygienic and calmly futuristic: interfaces that hover rather than sit, technology as clear air rather than hard object. There is a spatial-computing optimism in it — digital windows agreeing to coexist with physical rooms — and a premium, product-launch serenity even in its candy-colored variants.

## Era & Origins

2020s, named in 2020. Precursors: Windows Aero (Vista/7, 2007) with its glossy transparent window borders; iOS 7 (2013) introducing flat translucent blurred layers; Microsoft Fluent (2017) with translucency, rounded corners and soft gradients. The modern iteration went mainstream through macOS Big Sur (2020), Windows 11 (2021), visionOS (2024), Samsung One UI 7 and iOS 26 / macOS Tahoe (2025). It reacts against Flat Design's opacity and against Neumorphism's monochrome embossing, and it deliberately rejects the high-gloss skeuomorphic glass of the 2000s in favor of matte frost. It is expected to succeed Flat Design as the dominant interface aesthetic around 2026–2027.

## Generation Guidance

**Principles**

- Pair every translucency with blur: a panel through which the background shows *sharp* is transparency, not Glassmorphism.
- Give every floating panel a hairline semi-transparent white stroke and a whisper of ambient shadow; the stroke is what reads as glass thickness.
- Always stage color behind the glass — gradient blobs, orbs, photography, icon grids — so the frost visibly diffuses something.
- Keep type legible: tune blur radius and fill opacity until text on the panel reads cleanly.
- Build depth by layering planes (sharp background mass → blurred mid-plane → crisp foreground type), not by extruding or embossing.
- Round the corners; keep surfaces matte-frosted, adding at most a soft edge highlight.
- Let the background own the chroma and the glass own the milky white tint.

**Variation axes**

- *Subject:* desktop OS scene, phone UI, widget collage, icon grid, abstract 3D glass sculpture, frosted typography, advertising hero, AR headset view over a real room, product render with hovering HUD. A correct image can use any subject within this range; it should echo the style's rules, not any reference image.
- *Palette:* candy magenta/pink, corporate blue/cyan, pastel peach-mint-cream, lavender-periwinkle, dark indigo with neon accents, or monochrome frost over photography.
- *Composition:* full-bleed interface, floating panel collage, centered hero card, diagonal cascade, tight macro of a single frosted strip, orderly grid.
- *Lighting:* diffuse studio, backlit rim glow, ambient daylight in spatial scenes, dusk neon in dark mode.
- *Mood:* playful candy, calm enterprise, spatial-futurist, editorial-minimal.

**Avoid**

- Opaque flat fills, or transparency without background blur.
- Missing border stroke, letting panels dissolve into the background.
- Neumorphic dual shadows (light top-left plus dark bottom-right) and same-color embossed surfaces.
- Matte clay or inflatable Play-Doh objects as the hero material.
- Frutiger Aero nature gloss: water droplets, bubbles, skies, fish, lens flares.
- Aero/Neo-Aero smoky reflective glass with hard specular streaks and skeuomorphic sheen.
- Stark monochrome minimal geometry with no gradient vibrancy behind the planes.
- Grain, noise, chrome, beveled metal, wood or leather textures; cluttered unblurred detail under text.

## Discrimination Cues

- **Claymorphism:** objects are solid, opaque, puffy pastel clay with deep outer and inner shadows; nothing blurs through them. Glassmorphism panels are semi-transparent with blurred backgrounds and light strokes.
- **Neumorphism:** elements are the same monochrome color as the surface, extruded with one light and one dark shadow, no borders, no blur. Glassmorphism elements float *above* a differently-colored, vivid background.
- **Cyberminimalism:** flat, opaque, stark minimal geometry and typography with high contrast and no material illusion; lacks frost, blur, strokes and gradient vibrancy.
- **Frutiger Aero:** glossy 2000s skeuomorphic optimism built on nature photography — water, bubbles, grass, sky — with hard reflections; Glassmorphism is matte, abstract and gradient-based.
- **Neo-Aero:** revival of Vista/7 glass — smoky tinted panes, glossy reflective borders, specular streaks, skeuomorphic sheen. Glassmorphism replaces reflection with uniform Gaussian blur and a thin white stroke, and sits on saturated gradients rather than desktop photography.

Quick test: if you can identify what is behind a panel only as soft color masses, and a white hairline outlines that panel against a vivid field, you are looking at Glassmorphism.

---

*Skill written from Aesthetics Wiki text (CC-BY-SA 3.0) and 4 reference image(s) sampled from 49 on the wiki. Source: https://aesthetics.fandom.com/wiki/Glassmorphism*