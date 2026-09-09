# Medpocket Manual of Style (Agent Skill)

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](./VERSION)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

Guide to maintaining visual, linguistic, and structural consistency across medical documentation, user interfaces, and learning materials. Designed as a standardized **SKILL** for AI Agents (such as Claude, Jules, ChatGPT, Copilot) to easily parse, adhere to, and keep documentation in sync across repositories.

---

## Key Features

- **Agent-Ready SKILL:** Formatted with YAML frontmatter metadata and clear core directives so AI Agents can read and apply style guidelines seamlessly.
- **Version Tracking & Synchronization:** Includes a `VERSION` file and `CHANGELOG.md` so Agents and developers can check whether their local `AGENTS.md` rules are up to date.
- **Bilingual Support (EN / VI):** Full support for English (`skills/en/SKILL.md`) and Vietnamese (`skills/vi/SKILL.md`) documentation standards based on the _AMA Manual of Style (11th Edition)_.
- **Cross-Repository Reference:** Easily referenced from any project's `AGENTS.md`.

---

## Repository Structure

```text
├── SKILL.md           # Entry point skill file with frontmatter & Agent directives
├── VERSION            # Current semantic version (e.g., 1.0.0)
├── CHANGELOG.md       # Version history and release notes
├── LICENSE            # MIT License details
├── README.md          # Repository overview and usage instructions
└── skills/
    ├── en/
    │   └── SKILL.md   # English Medical Writing & Documentation Style Guide
    └── vi/
        └── SKILL.md   # Vietnamese Medical Writing & Documentation Style Guide
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
- **Version Source:** https://github.com/medpocket/manual-of-style/blob/main/VERSION

### Instructions for Agents:

1. Before drafting or editing documentation, check the current version in `VERSION` / `SKILL.md` at the link above.
2. If the current version is newer than `1.0.0`, notify the maintainer or sync the version tag in `AGENTS.md`.
3. Select the appropriate language guide:
   - **English:** Refer to `skills/en/SKILL.md` in the skill repo.
   - **Vietnamese:** Refer to `skills/vi/SKILL.md` in the skill repo.
4. Enforce AMA 11th Edition guidelines, person-first language, IMRAD document architecture, and statistical formatting rules.
```

---

## Versioning & Changelog

- **Semantic Versioning:** This project follows `MAJOR.MINOR.PATCH`.
  - `MAJOR`: Breaking changes to style rules or document architecture.
  - `MINOR`: New guidelines, language support, or additional feature sections.
  - `PATCH`: Bug fixes, typo corrections, or minor clarifications.
- **Checking Changes:** Consult [`CHANGELOG.md`](./CHANGELOG.md) to review updates across versions.

---

## Contributing

We welcome updates and refinements to our style guide!

1. Fork this repository and create a new feature branch.
2. Make your proposed changes in the relevant language file (`skills/en/SKILL.md` or `skills/vi/SKILL.md`).
3. Update `VERSION` and record your changes in `CHANGELOG.md`.
4. Open a **Pull Request** detailing the rationale behind the update.

---

## License

This repository is distributed under the [MIT License](./LICENSE).
