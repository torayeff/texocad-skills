# Laser And 2D Cutting DFM

Use this reference for laser, waterjet, plasma, router, and knife-cut flat profiles.

## Checks

- Material and thickness: confirm the chosen cutting process supports the stock and tolerance needs.
- Kerf: account for process-specific kerf in slots, tabs, press fits, and mating profiles.
- Minimum web: avoid thin bridges between cuts that overheat, warp, or break during handling.
- Internal corners: laser and waterjet can cut sharp-ish internal corners, but mating tabs may still need clearance.
- Lead-ins and pierce marks: keep cosmetic surfaces away from likely pierce points when possible.
- Closed profiles: ensure cut paths are closed, non-self-intersecting, and layer-coded when exported.
- Heat effects: watch for warping, discoloration, and hardened edges depending on material.

## Common Actions

- Add dogbones, reliefs, or slot clearance for tabbed assemblies.
- Add small radii to reduce stress risers and cutting artifacts.
- Separate cut, score, engrave, visible, hidden, and construction layers in DXF/SVG.
- Add labels or etched alignment marks when assembly orientation matters.
- Keep small loose cutouts attached with tabs if they would tip, fall, or be lost.
