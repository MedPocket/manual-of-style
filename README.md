# Medpocket Manual of Style (Agent Skill)

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](./SKILL.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

Guide to maintaining visual, linguistic, and structural consistency across medical documentation, user interfaces, and learning materials. Designed as a standardized **AGENTS SKILL** (following the [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) pattern) for AI Agents (such as Claude, Jules, ChatGPT, Copilot) to easily parse, adhere to, and keep documentation in sync across repositories.

---

## Key Features

- **Agent-Ready AGENTS.md Skills:** Formatted with version headers, priority-impact tables of contents, and actionable guidelines for AI Agents.
- **Version Management via Headers:** Version numbers are defined directly in skill document headers (`**Version X.Y.Z**`) and `CHANGELOG.md`, removing external single-line version files.
- **Bilingual Support (EN / VI):** Full support for English (`skills/en/AGENTS.md`) and Vietnamese (`skills/vi/AGENTS.md`) documentation standards based on the _AMA Manual of Style (11th Edition)_.
- **Cross-Repository Reference:** Easily referenced from any project's `AGENTS.md`.

---

## Repository Structure

```text
├── SKILL.md           # Entry point skill file with frontmatter & Agent directives
├── CHANGELOG.md       # Version history and release notes
├── LICENSE            # MIT License details
├── README.md          # Repository overview and usage instructions
└── skills/
    ├── en/
    │   └── AGENTS.md  # English Medical Writing & Documentation Style Guide (Skill)
    └── vi/
        └── AGENTS.md  # Vietnamese Medical Writing & Documentation Style Guide (Skill)
```

---

## How to Use in Other Projects (`AGENTS.md`)

To make AI Agents automatically recognize and adhere to this style guide in another project, add the following snippet to your project's `AGENTS.md` file:

### Example `AGENTS.md` Integration Snippet

```markdown
## Documentation Style & Standards Skill

- **Skill Name:** Medpocket Manual of Style
- **Current Version:** 1.0.0
- **Skill Reference:** https://github.com/medpocket/manual-of-style/blob/main/SKILL.md
- **English Skill:** https://github.com/medpocket/manual-of-style/blob/main/skills/en/AGENTS.md
- **Vietnamese Skill:** https://github.com/medpocket/manual-of-style/blob/main/skills/vi/AGENTS.md

### Instructions for Agents:

1. Before drafting or editing documentation, check the version header (`**Version X.Y.Z**`) in `SKILL.md` or `skills/en/AGENTS.md` at the links above.
2. If the skill version is newer than `1.0.0`, notify the maintainer or sync the version tag in `AGENTS.md`.
3. Select the appropriate language guide:
   - **English:** Refer to `skills/en/AGENTS.md` in the skill repo.
   - **Vietnamese:** Refer to `skills/vi/AGENTS.md` in the skill repo.
4. Enforce AMA 11th Edition guidelines, person-first language, IMRAD document architecture, and statistical formatting rules.
```

---

## Versioning & Changelog

- **Header-Based Versioning:** Version numbers are tracked in document headers (`**Version X.Y.Z**`) and documented in [`CHANGELOG.md`](./CHANGELOG.md).
- **Semantic Versioning:** Follows `MAJOR.MINOR.PATCH`.
  - `MAJOR`: Breaking changes to style rules or document architecture.
  - `MINOR`: New guidelines, language support, or additional feature sections.
  - `PATCH`: Bug fixes, typo corrections, or minor clarifications.

---

## Contributing

We welcome updates and refinements to our style guide!

1. Fork this repository and create a new feature branch.
2. Make your proposed changes in the relevant language skill file (`skills/en/AGENTS.md` or `skills/vi/AGENTS.md`).
3. Update the `**Version X.Y.Z**` header in the file and record your changes in `CHANGELOG.md`.
4. Open a **Pull Request** detailing the rationale behind the update.

---

## License

This repository is distributed under the [MIT License](./LICENSE).
