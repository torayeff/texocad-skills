# texocad-skills

This is a modular Agent Skills pack for CAD-as-code and manufacturing-aware engineering workflows.

## Install

Copy the root [`SKILL.md`](SKILL.md) into your coding agent's skills directory. If your tool expects one folder per skill, create a `texocad-skills/` folder and put `SKILL.md` inside it.

That file is a small bootstrap. It tells agents to fetch the latest canonical skill router from GitHub:

```text
https://raw.githubusercontent.com/torayeff/texocad-skills/main/skills/SKILL.md
```

The full online skill pack lives in [`skills/`](skills/).

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

- Cursor: `~/.cursor/skills/texocad-skills/SKILL.md`
- Claude Code: `~/.claude/skills/texocad-skills/SKILL.md`
- Codex: `~/.agents/skills/texocad-skills/SKILL.md`

Some tools also let you invoke the skill pack directly with `/texocad-skills` or `$texocad-skills`.

