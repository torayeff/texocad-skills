# Process Selection

Use this reference when the manufacturing process is unspecified or when comparing process fit.

## Inputs To Capture

- Quantity: one-off prototype, pilot batch, production, or mass production.
- Material requirements: strength, temperature, chemical exposure, compliance, surface finish, and color.
- Geometry: envelope, wall thickness, undercuts, internal channels, sharp corners, deep pockets, flat profiles, bends, and assembly count.
- Tolerances: cosmetic only, functional fit, bearing/alignment, sealing, or inspected drawing tolerances.
- Lead time and tooling budget.

## Default Process Heuristics

- Use 3D printing for fast prototypes, complex internal geometry, low quantity, and geometry that would require many machining setups.
- Use CNC machining for strong isotropic parts, tight tolerances, known engineering materials, flat datums, and low to medium quantity.
- Use laser or 2D cutting for flat profiles, sheet stock, tabs, slots, brackets, panels, and quick low-cost parts.
- Use sheet metal for folded enclosures, brackets, chassis, springy clips, and production parts made from constant-thickness sheet.
- Use injection molding for high quantity plastic parts when tooling cost is justified and the design can support draft, gates, ejectors, and uniform walls.

## Cross-Process Checks

- If a design has constant thickness and bends, evaluate sheet metal before machining it from billet.
- If a design is mostly a 2D profile, evaluate laser cutting before CNC milling.
- If a design needs tight bearing bores or flat sealing surfaces, additive alone may need secondary machining.
- If a design needs thousands of identical plastic parts, evaluate molding even if 3D printing works for prototypes.
- If internal cavities cannot be cleaned, supported, or inspected, avoid processes that trap material or support residue.
