# texocad-skills

## Deprecated and Archived

This repository is deprecated and archived. Texocad no longer uses this skill pack; it has evolved into a better cloud-based solution.

This content is kept for reference only. Use [texocad.ai](https://texocad.ai) for managed, fully online infrastructure.

This was a modular Agent Skills pack for CAD-as-code and manufacturing-aware engineering workflows.

## API Key
Cloud runs use `TEXOCAD_API_KEY`. To get a free key, visit https://texocad.ai,
click your avatar, open **API keys**, and create a new key.

## Install

Historical installation instructions are preserved below for reference only. New projects should use [texocad.ai](https://texocad.ai) instead.

Copy the [`SKILL.md`](https://api.texocad.ai/SKILL.md) into your coding agent's skills directory. If your tool expects one folder per skill, create a `texocad-skills/` folder and put `SKILL.md` inside it.

Codex:

```sh
curl -fsSL https://api.texocad.ai/SKILL.md -o ~/.agents/skills/texocad-skills/SKILL.md
```

Claude Code:

```sh
curl -fsSL https://api.texocad.ai/SKILL.md -o ~/.claude/skills/texocad-skills/SKILL.md
```

Cursor:

```sh
curl -fsSL https://api.texocad.ai/SKILL.md -o ~/.cursor/skills/texocad-skills/SKILL.md
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

