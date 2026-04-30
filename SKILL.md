---
name: texocad-skills
description: Routes coding agents to Texocad modular skills for CAD-as-code, build123d modeling, DFM review, validation, manufacturing constraints, units, and exports. Use when a task involves mechanical CAD code, manufacturability, tolerances, process constraints, or skill discovery in this repository.
license: MIT
---

# Texocad Skills Router

This root skill is an index. Do not solve domain tasks from this file alone; read the matching child `SKILL.md` before planning or editing.

## Routing

Read exactly one child skill first unless the task clearly spans multiple domains:

- `build123d-skill/SKILL.md`: Use for coding CAD with build123d: parametric parts, sketches, assemblies, selectors, workplanes, joints, technical drawings, exports, debugging, and model validation.
- `dfm-skill/SKILL.md`: Use for manufacturability review: 3D printing, CNC machining, laser cutting, sheet metal, injection molding, tolerances, clearances, wall thickness, tool access, and process-specific design constraints.

Read `shared/references/units-and-outputs.md` only when multiple skills need common guidance for units, export formats, tolerances, or final reporting.

## Tie-Breakers

- If the user asks to create, edit, refactor, debug, or export CAD code, load `build123d-skill/SKILL.md` first.
- If the user asks whether a design can be manufactured, printed, machined, molded, cut, bent, or assembled, load `dfm-skill/SKILL.md` first.
- If the task combines CAD creation and manufacturability, load `build123d-skill/SKILL.md` first, then load `dfm-skill/SKILL.md` before final validation.
- If the task asks only how this skills pack is organized, answer from this router and load child skills only when their details matter.

## Shared Workflow

1. Route the task to the smallest relevant skill set.
2. Read the selected child `SKILL.md`.
3. Follow that skill's reference routing; do not browse every reference file by default.
4. Use shared references only for cross-skill conventions.
5. Before finalizing, apply the selected skill's validation or review checklist.