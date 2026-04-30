# texocad-skills

This is a modular Agent Skills pack for CAD-as-code and manufacturing-aware engineering workflows.

Install the repository as a single skill pack. Agents load the root `SKILL.md` as a small router, then read only the child skill needed for the task.

## Included Skills

- `build123d-skill`: Designs, edits, debugs, validates, assembles, and exports `build123d` CAD models.
- `dfm-skill`: Reviews designs for manufacturability across 3D printing, CNC machining, laser cutting, sheet metal, and injection molding.
- `shared`: Holds cross-skill conventions for units, export formats, tolerances, and reporting.

## Easiest Way

Add this repository or folder as a skill in your AI coding tool.

- In Cursor: open Settings, go to Rules, add a remote rule or skill, and choose this repository.
- In Claude Code or Codex: add this folder to your skills directory.

After that, just ask your AI agent to use it.

## Example Prompts

```text
Use the texocad skills to design a parametric build123d bracket.
```

```text
Use the texocad skills to fix this CAD model, review it for 3D printing, and export a STEP file.
```

```text
Use the DFM skill to review this enclosure for CNC machining constraints.
```

## Manual Install Paths

If your tool asks where skills live, use one of these:

- Cursor: `~/.cursor/skills/texocad-skills`
- Claude Code: `~/.claude/skills/texocad-skills`
- Codex: `~/.agents/skills/texocad-skills`

Some tools also let you invoke the skill pack directly with `/texocad-skills` or `$texocad-skills`.

## Repository Layout

```text
texocad-skills/
├── SKILL.md
├── build123d-skill/
│   ├── SKILL.md
│   └── references/
├── dfm-skill/
│   ├── SKILL.md
│   └── references/
└── shared/
    └── references/
```
