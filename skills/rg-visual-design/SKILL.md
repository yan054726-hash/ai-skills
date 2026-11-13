---
name: rg-visual-design
description: Generate and review RG-branded charts, diagrams, infographics, presentation visuals, posters, and campaign assets. Use when a task requests an RG visual asset, asks to apply RG CI, or needs visual consistency with RG brand guidelines.
---

# RG Visual Design Skill

Use this skill to plan, generate, edit, and quality-check visual assets that follow RG.Experience's brand identity.

## Required workflow

1. Identify the asset type, audience, communication objective, required content, canvas dimensions, output formats, and editability needs.
2. Read [brand-principles.md](brand-principles.md) before designing. Treat official RG CI rules as authoritative.
3. Read [visual-tokens.json](visual-tokens.json) for approved values. Do not invent missing brand values; distinguish verified values from proposed defaults.
4. Select the relevant task guide:
   - [chart-guidelines.md](references/chart-guidelines.md)
   - [infographic-guidelines.md](references/infographic-guidelines.md)
   - [poster-guidelines.md](references/poster-guidelines.md)
5. Use [master-prompt.md](templates/master-prompt.md) as the common instruction layer, then add the relevant task template.
6. For a family of assets, establish one approved master reference and shared design decisions before generating individual outputs.
7. Generate with the most suitable workflow:
   - Use image generation for photographic, illustrative, or complex raster imagery.
   - Use SVG, HTML/CSS, or native chart/code workflows for precise typography, geometry, data, and editable layouts.
   - Combine approaches when necessary; do not ask an image model to render exact logos or long blocks of required text.
8. Validate against the checklist below. Correct specific failures rather than relying on vague requests such as "make it more professional."
9. Deliver the requested raster preview and editable source when required. State any limitations honestly.

## Source-of-truth rules

- Official RG Brand Guideline v1.2 and approved original assets take priority.
- This skill records the available CI information but does not replace the official guideline.
- Never fabricate logo geometry, clear-space measurements, grid values, font availability, or unverified component specifications.
- Where a value is marked UNVERIFIED or PROPOSED, do not present it as an official RG rule.
- Do not transfer RG brand colors, logo, or proprietary graphic elements to another brand's work unless explicitly requested and authorized.

## Global visual direction

- Build clear information hierarchy and structured compositions.
- Use RG's documented building-block concept, square-based forms, blocks, lines, and tube/light effects where appropriate.
- Treat light effects as conditional, not mandatory decoration.
- Prioritize clarity, content accuracy, and legibility over ornament.
- Keep typography, color roles, graphic treatment, spacing, and recurring components coherent across related assets.
- Avoid mixing unrelated flat icons, glossy 3D objects, photographic elements, gradients, lighting styles, and materials without an intentional art direction.

## Mandatory content integrity

- Preserve supplied wording, numbers, units, labels, relationships, and source attributions.
- Never invent chart data, process steps, product claims, or missing facts.
- Do not distort, redraw, approximate, or AI-regenerate the official RG logo.
- Flag conflicts or missing inputs instead of silently guessing.

## Output requirements

When requested, provide both:
- Raster preview: PNG or JPG at the specified dimensions/resolution.
- Editable source: SVG, HTML/CSS, native chart specification, or the requested design source format.

Keep text editable where practical, separate major elements logically, and verify that exported files render correctly. An SVG or HTML file is not automatically fully editable in every design application.

## Quality gate

P0 — must pass:
- Correct brand assets and no unauthorized logo modification.
- Accurate text, data, units, and relationships.
- All required content present.
- Explicit dimensions and delivery constraints met.

P1 — visual quality:
- Clear focal point and information hierarchy.
- Consistent typography, colors, spacing, and graphic language.
- Legible labels and appropriate contrast.
- No unnecessary clutter or incompatible styles.

P2 — technical delivery:
- Files open and render correctly.
- No clipping, missing fonts, broken links, or missing assets.
- Editability matches the stated requirement.
- Raster export has adequate resolution.

Any P0 failure blocks delivery. P1/P2 issues must be fixed when they affect intended use or explicit requirements.

## Completion report

For each deliverable, briefly report:
- Asset type and intended use.
- Files and formats produced.
- Any brand rules applied.
- Any assumptions or unverified items.
- QA issues found and whether they were resolved.
