# RG Chart & Diagram Guidelines

**Status:** Initial task guide. Global requirements come from ../brand-principles.md. Exact chart-series color semantics remain to be approved.

## Before design
- Confirm the data source, units, categories, date range, and intended comparison.
- Identify the audience and the single key takeaway.
- Choose a chart type appropriate to the data.
- Record any missing values; never fabricate replacements.

## Chart construction
- Use the approved RG palette from ../visual-tokens.json.
- Keep category-to-color mapping stable across related charts.
- Use the same scale and unit conventions when charts are intended for comparison.
- Label axes, series, units, and significant values clearly.
- Avoid 3D chart effects that distort perceived magnitude.
- Do not truncate axes in a misleading way.
- Use direct labels when they improve comprehension; keep legends concise.
- Use markers, patterns, or labels in addition to color where distinction is important.

## Diagrams and flowcharts
- Define node types before styling.
- Use one consistent shape for each equivalent node type.
- Preserve direction, dependencies, and branching logic exactly.
- Route connectors to minimize crossings and ambiguity.
- Use consistent connector weight, arrowheads, and spacing.
- Keep node text concise and legible.

## Deliverables
Prefer an editable chart specification or structured source plus SVG/PNG export. For diagrams, prefer SVG or HTML/CSS when individual elements must remain editable. Verify all data and relationships after rendering.

## QA
- Data values and totals reconcile with the source.
- Axes and units are correct.
- Category colors remain consistent.
- Labels and legends are readable.
- No relationship, arrow, or dependency has been invented.
- Exported file matches the source layout.
