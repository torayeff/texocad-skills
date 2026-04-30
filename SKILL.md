---
name: texocad-skills
description: Loads the latest Texocad skills from GitHub for CAD-as-code, build123d modeling, DFM review, validation, manufacturing constraints, tolerances, units, and exports. Use when a task involves mechanical CAD code, manufacturability, process constraints, or skill discovery in this repository.
license: MIT
---

# Texocad Skills

This file is only a bootstrap. Do not answer Texocad domain tasks from this file alone.

Set:

`BASE_URL=https://raw.githubusercontent.com/torayeff/texocad-skills/main/skills/`

Fetch and read the latest canonical router from:

`${BASE_URL}SKILL.md`

Resolve all relative skill and reference paths from `BASE_URL`. When a remote markdown file links to another markdown file, resolve the link relative to the file that contains it.