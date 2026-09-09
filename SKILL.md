---
name: medpocket-manual-of-style
version: 1.0.0
description: Medical Writing & Documentation Style Guide Skill for AI Agents
languages:
  - en
  - vi
default_language: en
skill_paths:
  en: skills/en/AGENTS.md
  vi: skills/vi/AGENTS.md
changelog_file: CHANGELOG.md
---

# Medpocket Manual of Style (Agent Skill)

**Version 1.0.0**
Medpocket Engineering
September 2026

> **Purpose:** Standardized guide and prompt rules for AI Agents generating, updating, and synchronizing medical writing and clinical documentation across projects.

---

## Instructions for AI Agents

When an AI Agent is tasked with generating or updating medical documentation in a repository referencing this skill:

1. **Version Detection & Sync Verification:**
   - Check the version header (`**Version X.Y.Z**`) in the target skill document (`skills/en/AGENTS.md` or `skills/vi/AGENTS.md`).
   - Compare the version in your current project's `AGENTS.md` against `CHANGELOG.md` or the header in this repository.
   - If a higher version is available, notify the user or update the version reference in `AGENTS.md`.

2. **Language Selection:**
   - Determine target language for the documentation:
     - For English documentation, refer to [`skills/en/AGENTS.md`](./skills/en/AGENTS.md).
     - For Vietnamese documentation, refer to [`skills/vi/AGENTS.md`](./skills/vi/AGENTS.md).
   - If not specified, default to English (`skills/en/AGENTS.md`).

3. **Core Compliance Rules:**
   - Follow AMA 11th Edition citation and statistical guidelines.
   - Use person-first and non-stigmatizing medical terminology.
   - Follow IMRAD structure for research/technical guides where applicable.
   - Ensure accurate reporting of confidence intervals (95% CI) and exact _P_ values (_P_ < .001, _P_ = .003, no leading zero).

---

## Quick Language Links

- 🇬🇧 [English Medical Writing Style Guide](./skills/en/AGENTS.md)
- 🇻🇳 [Hướng dẫn Phong cách Viết Y khoa Tiếng Việt](./skills/vi/AGENTS.md)

---

## Changelog & Version History

See [`CHANGELOG.md`](./CHANGELOG.md) for full details on version updates.
