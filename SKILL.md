---
name: medpocket-manual-of-style
version: 1.0.0
description: Medical Writing & Documentation Style Guide Skill for AI Agents
languages:
  - en
  - vi
default_language: en
skill_paths:
  en: skills/en/SKILL.md
  vi: skills/vi/SKILL.md
version_file: VERSION
changelog_file: CHANGELOG.md
---

# Medpocket Manual of Style (Agent Skill)

> **Version:** 1.0.0
> **Purpose:** Standardized guide and prompt rules for AI Agents generating, updating, and synchronizing medical writing and clinical documentation across projects.

---

## Instructions for AI Agents

When an AI Agent is tasked with generating or updating medical documentation in a repository referencing this skill:

1. **Version Detection & Sync Verification:**
   - Check the `version` field in this `SKILL.md` (or `VERSION` file).
   - Compare the version in your current project's `AGENTS.md` (e.g. `Medpocket Manual of Style v1.0.0`) against `CHANGELOG.md` or `VERSION` in this repository.
   - If a higher version is available, notify the user or update the version reference in `AGENTS.md`.

2. **Language Selection:**
   - Determine target language for the documentation:
     - For English documentation, refer to [`skills/en/SKILL.md`](./skills/en/SKILL.md).
     - For Vietnamese documentation, refer to [`skills/vi/SKILL.md`](./skills/vi/SKILL.md).
   - If not specified, default to English (`skills/en/SKILL.md`).

3. **Core Compliance Rules:**
   - Follow AMA 11th Edition citation and statistical guidelines.
   - Use person-first and non-stigmatizing medical terminology.
   - Follow IMRAD structure for research/technical guides where applicable.
   - Ensure accurate reporting of confidence intervals (95% CI) and exact _P_ values (_P_ < .001, _P_ = .003, no leading zero).

---

## Quick Language Links

- 🇬🇧 [English Medical Writing Style Guide](./skills/en/SKILL.md)
- 🇻🇳 [Hướng dẫn Phong cách Viết Y khoa Tiếng Việt](./skills/vi/SKILL.md)

---

## Changelog & Version History

See [`CHANGELOG.md`](./CHANGELOG.md) for full details on version updates.
