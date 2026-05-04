# texocad-skills

This is a modular Agent Skills pack for CAD-as-code and manufacturing-aware engineering workflows.

## API Key
Cloud runs use `TEXOCAD_API_KEY`. To get a free key, visit https://texocad.ai,
click your avatar, open **API keys**, and create a new key.

## Install

Copy the [`SKILL.md`](https://texocad.ai/SKILL.md) into your coding agent's skills directory. If your tool expects one folder per skill, create a `texocad-skills/` folder and put `SKILL.md` inside it.

Codex:

```sh
curl -fsSL https://texocad.ai/SKILL.md -o ~/.agents/skills/texocad-skills/SKILL.md
```

Claude Code:

```sh
curl -fsSL https://texocad.ai/SKILL.md -o ~/.claude/skills/texocad-skills/SKILL.md
```

Cursor:

```sh
curl -fsSL https://texocad.ai/SKILL.md -o ~/.cursor/skills/texocad-skills/SKILL.md
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

