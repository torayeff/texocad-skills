# 3D Printing DFM

Use this reference for FDM, SLA, SLS, MJF, DMLS, and other additive processes. State the assumed process if the user does not provide one.

## Checks

- Wall thickness: verify minimum walls, ribs, pins, and embossed or engraved details for the chosen process and material.
- Clearances: distinguish static clearance, sliding clearance, print-in-place clearance, and post-machined fits.
- Orientation: choose orientation based on strength direction, support scars, surface finish, tolerance stack, and bed volume.
- Overhangs and bridges: identify features likely to need support or redesign.
- Holes and pins: small holes often print undersized; recommend pilot holes, reaming, inserts, or process-specific compensation.
- Warping: watch for large flat areas, uneven wall thickness, sharp transitions, and high-shrink materials.
- Threads and inserts: prefer heat-set inserts, captive nuts, or printed coarse threads when appropriate.

## Common Actions

- Add fillets at stress concentrations and wall transitions.
- Split parts to reduce supports or improve strength orientation.
- Add chamfers to bottom edges to reduce elephant foot issues.
- Increase clearance or specify post-processing for functional fits.
- Use 3MF when material, color, metadata, or multipart print preparation matters; use STL only for simple mesh handoff.
