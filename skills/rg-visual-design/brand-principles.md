# RG Brand Visual Principles
## AI Visual Design Guidelines

**Version:** 1.0.0  
**Status:** Initial implementation draft — validate against the official RG Brand Guideline v1.2 before production use.  
**Brand:** RG.Experience  
**Scope:** AI-generated charts, diagrams, infographics, presentation visuals, posters, campaign graphics, and other visual assets.

---

## 1. Purpose and scope

This document translates the available RG brand-guideline information into operational principles for AI-assisted visual production. It aims to maintain recognizable brand expression, reduce arbitrary variation across tools, support raster and editable deliverables, and make review repeatable.

These principles apply to data charts, flowcharts, architecture diagrams, infographics, presentation and report visuals, posters, social graphics, and digital communication assets.

Task-specific requirements may add constraints but must not silently override official brand rules.

## 2. Source of truth and rule status

Apply this priority order:

1. Official RG Brand Guideline and approved original brand assets.
2. Approved RG visual tokens and component specifications.
3. Approved RG design references and annotated examples.
4. Task-specific requirements that do not conflict with the above.
5. AI suggestions.

Rule labels:
- **MANDATORY** — must be followed.
- **CONDITIONAL** — applies only in a relevant context.
- **FLEXIBLE** — may adapt to content or canvas.
- **UNVERIFIED** — requires confirmation against the source guideline or asset.
- **PROPOSED** — a working recommendation, not an official CI requirement.

If sources conflict or a required value is missing, flag the issue. Do not invent a precise brand specification.

## 3. Core visual principles

### 3.1 Structured composition — MANDATORY
- Organize information into clear sections and visual groups.
- Establish one primary message or focal point.
- Align related elements consistently.
- Use whitespace to distinguish content groups.
- Keep the composition orderly at different content densities.
- Avoid overcrowding and unnecessary decoration.

### 3.2 Building-block logic — CONDITIONAL
RG's documented graphic concept includes building blocks and square-based graphic elements.
- Use modular geometric forms when extending the RG graphic language.
- Preserve consistent proportions and spacing among repeated forms.
- Use grouping and alignment to communicate structure.
- Do not introduce unrelated decorative geometry without a communication purpose.
- Refer to approved source artwork for exact construction; do not approximate proprietary geometry.

### 3.3 Light and depth — CONDITIONAL
The guideline describes tube-like structures and light effects as part of the RG visual language.
- Use light to support depth, hierarchy, connection, or a visual concept.
- Maintain coherent light direction, intensity, and material treatment within one asset.
- Do not add glow indiscriminately.
- Ensure effects do not reduce text or data legibility.
- Light effects are not mandatory in every asset.

### 3.4 Clarity before decoration — MANDATORY
- Prioritize communication, accuracy, and legibility.
- Every effect or decorative element must serve hierarchy, meaning, or brand expression.
- Avoid gratuitous gradients, shadows, textures, 3D objects, and highlights.
- Maintain adequate foreground/background contrast.

### 3.5 Controlled creativity — MANDATORY
AI may adapt composition, crop, grouping, and visual emphasis. It must not independently redefine approved brand colors, official logo construction, approved typography, or the core RG graphic language.

## 4. Color system

### 4.1 Colors recorded from RG Brand Guideline v1.2

| Token | Hex | Recorded role |
|---|---|---|
| RG Navy | #19376D | Primary brand color |
| RG Red | #C62128 | Primary brand color / emphasis |
| RG Light Blue | #D7E5F5 | Secondary color |
| RG Light Green | #DAF2D0 | Secondary color |
| RG Light Yellow | #FFFFCC | Secondary color |
| RG Light Pink | #FBE2D5 | Secondary color |

These values are transcribed from the available guideline. Exact component-by-component semantic mapping is not fully specified here and must be checked against the relevant CI page or approved examples.

### 4.2 Color application — MANDATORY
- Use approved RG colors rather than inventing brand colors.
- Keep primary and secondary roles distinct.
- Use red selectively for emphasis.
- Do not force every palette color into one asset.
- Maintain sufficient contrast for text, chart labels, axes, markers, and legends.
- Keep color mapping consistent for the same category across related charts.

### 4.3 Charts — CONDITIONAL
Use a restrained subset of the approved palette. Define series/category mapping before styling. Do not use color alone to communicate status; supplement it with labels, patterns, or markers where needed. The exact series sequence and semantic meanings require a separately approved chart specification.

### 4.4 Image filter — CONDITIONAL / VERIFY
The guideline example records filter color #546198 with 75% transparency. Apply only to the image treatment for which the guideline specifies it. Do not apply it automatically to every photograph or generated image.

### 4.5 Prohibited color behavior
- Arbitrary new brand colors without approval.
- Competing accent palettes within one visual family.
- Excessive saturation or contrast that harms hierarchy.
- Unverified semantic color assignments.

## 5. Typography

### 5.1 Font preferences recorded in the guideline

| Language | Preferred | Substitute |
|---|---|---|
| English | Roboto | Calibri |
| Chinese | 汉仪旗黑 | 等线 |

Use the preferred font when available and appropriately licensed. Use the documented substitute when necessary. Verify actual font availability in the target environment.

### 5.2 Hierarchy example
The guideline gives a proportional example:
- Heading: X (example 64 pt)
- Summary: 0.5X (example 32 pt)
- Body: 0.3X (example 19.2 pt)
- Caption: 0.25X (example 16 pt)

These are example proportions, not universal point sizes. Adapt sizes to canvas dimensions while preserving hierarchy.

### 5.3 Application
- Follow the documented left-alignment treatment where applicable.
- Use red as a highlight color where appropriate.
- Make line breaks intentional.
- Avoid emphasizing the same word with both red and bold in the documented text treatment.
- Preserve clear distinctions among heading, summary, body, and caption.

### 5.4 Text integrity — MANDATORY
- Preserve supplied wording unless rewriting is requested.
- Do not invent labels, figures, claims, or captions.
- Check clipping, overlap, missing glyphs, and awkward wrapping.
- Keep text editable where practical.
- Do not use AI-generated lettering as a replacement for the official logo.

## 6. Logo usage

### 6.1 Integrity — MANDATORY
- Use official RG logo files.
- Preserve proportions, internal spacing, and approved configuration.
- Never redraw, stretch, distort, rotate, crop, or reconstruct the logo.
- Follow official clear-space, minimum-size, and background rules.
- Do not invent logo variants.

### 6.2 Placement
Use the official guideline's placement and clear-space specifications. Exact measurements are **UNVERIFIED in this implementation document** and must be read from the source guideline before enforcing numeric values.

### 6.3 Co-branding
The available guideline information records different logo ordering for RG/partner materials and customer/RG materials, and use of a grey separator line where specified. Follow the exact relevant co-branding example in the official CI; do not generalize beyond its stated context.

### 6.4 AI restriction
AI must not generate or approximate the RG logo. Place the original supplied asset using a layout or code-based workflow.

## 7. Graphic elements and visual language

### 7.1 Building blocks and square elements
- Treat building blocks as modular components that can be combined to express structure and relationships.
- Preserve the geometric character and proportions of approved forms.
- Use official vector artwork as the source for exact geometry.
- Avoid arbitrary deformation or unrelated decorative combinations.

### 7.2 Blocks, lines, and dots
The guideline describes blocks and lines as ways to express stability, structure, flow, change, and connection.
- Use blocks for structure and grouping.
- Use lines for connection, direction, or movement.
- Use dots only where consistent with the approved graphic system.
- Keep stroke weights and spacing coherent.
- In diagrams, connector meaning and direction take priority over decoration.

### 7.3 Tube and light effects
The guideline describes a tube effect built by positioning and joining square-based forms to create an illusion of light. Use the official construction as reference. Keep lighting coherent and avoid using the effect as generic decoration.

### 7.4 Location-specific elements
The guideline identifies a Shanghai skyline silhouette for designs that imply the location of the RG office. Use only when location is relevant; do not add it as a generic motif.

## 8. Image and illustration principles

- Select imagery according to communication objective.
- The guideline references abstract lighting and industry-related imagery as image directions.
- Use a consistent treatment within one visual family.
- Apply filters only in the documented context.
- Do not mix incompatible lighting, rendering, or photographic styles without deliberate art direction.
- Check perspective, object integrity, shadows, and unintended AI artifacts.
- Keep imagery subordinate to essential information when used as a background.

Photography, illustration, and realistic objects are not categorically prohibited; they must be art-directed coherently.

## 9. Layout and composition

### 9.1 General rules — MANDATORY
- Establish a clear focal point.
- Group information logically.
- Align related elements.
- Maintain intentional margins and spacing.
- Separate headings, body copy, graphics, and CTAs.
- Adapt layout to canvas ratio and content density.

### 9.2 General information hierarchy
Unless the task requires another structure:
1. Primary message or title.
2. Main visual or key information.
3. Supporting explanation.
4. Secondary labels, notes, and sources.
5. Optional branding or navigation.

Not every asset needs all five levels.

### 9.3 Flexible layout variables
Composition, image crop, object placement, content density, and canvas ratio may change. Do not stretch components to fit a new ratio. Define exact spacing, grid, margins, and safe areas in component specifications rather than guessing.

## 10. Charts, diagrams, and infographics

### Charts
- Select chart type according to the data and comparison.
- Preserve values, units, categories, scales, and proportions.
- Use consistent category colors across related charts.
- Keep axes, legends, labels, and markers legible.
- Never invent or silently alter data.

### Flowcharts and architecture diagrams
- Use consistent shapes for equivalent node types.
- Preserve real relationships, direction, dependencies, and branching.
- Minimize connector crossings.
- Keep labels readable and line weights consistent.

### Infographics
- Establish a clear narrative or information sequence.
- Distinguish the main message from supporting details.
- Use icons only when they improve comprehension.
- Preserve source attributions, qualifications, and required wording.

Detailed axis, node, connector, card, legend, and icon specifications belong in separate component guides.

## 11. Cross-asset consistency

### Fixed attributes
Within one visual family, maintain consistency in approved colors, typography, logo treatment, core graphic language, icon style, rendering/lighting approach, recurring components, and spacing principles.

### Controlled variables
Composition, focal-point placement, crop, canvas dimensions, content density, background imagery, and section arrangement may adapt to content.

### Mixed-style prevention
Avoid combining unrelated flat icons, glossy 3D objects, photographic elements, gradients, lighting, and materials without a clear art direction. Consistency means a shared underlying system, not identical layouts.

### Master-reference workflow
1. Define the shared visual direction.
2. Approve one master reference.
3. Define reusable components and fixed attributes.
4. Generate individual assets using the shared system.
5. Review all assets together.
6. Correct inconsistencies before export.

## 12. AI generation workflow

### Inputs
Provide relevant brand guideline pages, official assets, tokens, approved references, component specs, required content/data, canvas dimensions, output formats, and special constraints.

### Process
1. Understand asset type, audience, objective, and content.
2. Load applicable brand rules and references.
3. Define information hierarchy and composition.
4. Choose a suitable generation method.
5. Generate the asset.
6. Validate brand, content, visual, and technical quality.
7. Correct specific violations.
8. Save approved output, source, prompt, and review notes.

### Tool selection
- Image generation: photography, illustration, complex raster imagery.
- SVG/HTML/CSS/code: exact typography, geometry, charts, and editable layout.
- Hybrid: generate imagery separately, then assemble exact text, logo, and layout in structured tools.

Do not assume every AI tool can enforce exact color, spacing, typography, or text equally well.

## 13. Output and editability

| Need | Preferred format |
|---|---|
| Scalable chart or diagram | SVG |
| Structured layout / text-heavy graphic | HTML/CSS or SVG |
| Editable data visualization | Native chart specification plus export |
| Final digital image | PNG or JPG |
| Complex raster imagery | PNG or JPG |
| Mixed imagery and precise typography | Editable layout source plus raster export |

When editability is required:
- Keep text editable where practical.
- Separate major components logically.
- Avoid flattening all content into one image.
- Use clear layer/component names.
- Reopen the source in the intended environment to verify editability.

A file extension alone does not guarantee practical editability.

## 14. Prohibited behaviors

1. Inventing brand colors, fonts, logos, or official graphic elements.
2. Modifying the official logo without authorization.
3. Mixing unrelated visual styles without art direction.
4. Adding effects that undermine clarity.
5. Letting decoration compete with the main message.
6. Altering supplied data, labels, units, or factual claims.
7. Delivering distorted or unreadable required text.
8. Changing recurring component styles arbitrarily across related assets.
9. Ignoring dimensions, formats, or editability requirements.
10. Treating unreviewed AI outputs as approved brand references.

## 15. Quality assurance

### P0 — mandatory
- Brand assets are correct and unmodified.
- Text, data, units, and relationships are accurate.
- Required content is present.
- Explicit output constraints are met.

### P1 — visual quality
- Clear focal point and hierarchy.
- Consistent typography, color, spacing, and graphic language.
- Legible labels and adequate contrast.
- No unnecessary clutter or incompatible styles.

### P2 — technical delivery
- Files open and render correctly.
- No clipping, missing fonts, broken links, or missing assets.
- Editability matches the requirement.
- Raster export has adequate resolution.

Any P0 failure blocks delivery. P1/P2 issues must be corrected when they affect intended use or explicit requirements.

## 16. Exceptions and governance

Document every intentional deviation with the rule changed, reason, affected assets/channels, approval status, and whether it is temporary or reusable. An exception for one asset does not become a global rule.

Use semantic versioning:
- MAJOR: fundamental changes to the visual system.
- MINOR: approved components, templates, or reusable rules added.
- PATCH: clarification, corrections, and non-breaking documentation updates.

Only reviewed assets may enter the approved reference library. Record reference ID, category, source, applicable rules, allowed variations, known failure modes, approval status, and editable source.

## 17. Items requiring validation

Before treating this document as a fully production-ready specification, verify:
- Exact logo clear-space and minimum-size values for each configuration.
- Grid, spacing, margin, and safe-area measurements.
- Official vector geometry for building blocks and tube effects.
- Exact secondary-color mapping to components.
- Chart-series color order and semantic meaning.
- Image-treatment rules for each image category.
- Icon, illustration, and photography specifications.
- Minimum font sizes by platform.
- Any additional restrictions in the official guideline.

Do not invent precise values or present proposals as official RG requirements.

---

## Final principle

Every AI-generated RG visual should preserve the established brand identity while adapting its composition to the task. Consistency comes from shared rules, reusable components, approved references, and verifiable output requirements — not vague stylistic descriptions alone.
