# texocad-skills

This is a modular Agent Skills pack for CAD-as-code and manufacturing-aware engineering workflows.

## Install

Copy the root [`SKILL.md`](SKILL.md) into your coding agent's skills directory. If your tool expects one folder per skill, create a `texocad-skills/` folder and put `SKILL.md` inside it.

Codex:

```sh
curl -fsSL https://raw.githubusercontent.com/torayeff/texocad-skills/main/SKILL.md -o ~/.agents/skills/texocad-skills/SKILL.md
```

Claude Code:

```sh
curl -fsSL https://raw.githubusercontent.com/torayeff/texocad-skills/main/SKILL.md -o ~/.claude/skills/texocad-skills/SKILL.md
```

Cursor:

```sh
curl -fsSL https://raw.githubusercontent.com/torayeff/texocad-skills/main/SKILL.md -o ~/.cursor/skills/texocad-skills/SKILL.md
```

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

