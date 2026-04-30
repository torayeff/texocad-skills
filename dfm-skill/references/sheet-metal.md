# Sheet Metal DFM

Use this reference for bent, punched, laser-cut, or stamped sheet parts.

## Checks

- Constant thickness: sheet metal parts should normally derive from one sheet thickness.
- Bend radius: use a realistic inside bend radius for material, thickness, and tooling.
- Bend relief: add reliefs where flanges would tear or collide during bending.
- K-factor and flat pattern: identify bend allowance assumptions before relying on flat dimensions.
- Hole-to-bend distance: keep holes, slots, and cutouts away from bend lines unless distortion is acceptable.
- Flange length: check minimum flange lengths for tooling and bend sequence.
- Bend order: verify the part can be bent without tool collision or trapped geometry.
- Hardware: plan PEM nuts, studs, rivets, tabs, or welds with edge distance and access.

## Common Actions

- Convert machined blocks or printed boxes into folded sheet plus fasteners when constant wall thickness is acceptable.
- Add bend reliefs, corner reliefs, and fillets at flange intersections.
- Move holes away from bend zones or mark them as post-bend operations.
- Add tabs, slots, hemmed edges, or joggles for alignment and stiffness.
- Use DXF for flat profiles and STEP plus drawings for formed parts.
