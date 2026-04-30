# CNC Machining DFM

Use this reference for milled, turned, drilled, and routed parts.

## Checks

- Tool access: verify every feature can be reached from a reasonable setup without impossible undercuts.
- Internal radii: internal corners need radius at least as large as the cutter radius; larger radii reduce chatter and cost.
- Pocket depth: deep narrow pockets increase tool deflection, chatter, and cycle time.
- Hole depth and diameter: deep small holes may need special drills, peck cycles, or design changes.
- Datums and setups: identify primary setup datums and whether flips or soft jaws are needed.
- Stock: leave realistic allowance for facing, workholding, tabs, and cleanup.
- Threads: check thread depth, tap access, blind-hole relief, and insert alternatives.
- Tolerance stack: reserve tight tolerances for functional features, not every surface.

## Common Actions

- Add corner reliefs or dogbones where square mating corners are required.
- Increase internal radii and reduce pocket depth where function allows.
- Split the part or redesign features to reduce setup count.
- Replace tiny milled features with drill, ream, broach, EDM, insert, or secondary-operation notes when appropriate.
- Prefer STEP or BREP for CAM handoff, plus drawings for toleranced features.
