# Changelog

## [2026-02-10] — Swarm awakens (`a5885fd` to `b3855fc`)

### 🆕 New Features
- **vibe_oracle.py**: Add the Vibe Oracle — a chaotic vibe generator with randomized vibes, intensity levels, and prophecies. Run with `python vibe_oracle.py [query]`.
- **swarm_mascot.py**: Add ASCII art mascot and swarm banner for the All the Vibes Agent Swarm. Run with `python swarm_mascot.py`.

### ⚙️ Configuration
- **.gitignore**: Add Python, Node.js, and OS-specific ignore rules.

### 📝 Documentation
- **README.md**: Merge PR #2 adding the changelog generator skill, prompts, instructions, and CI workflow.

---

## [2026-02-10] — Initial setup

### 🆕 New Features
- **README.md**: Add project README with structure, usage, and contributing guide.
- **.vscode/skills/readme-changelog-generator/SKILL.md**: Add Copilot skill for automated changelog generation.
- **.github/prompts/generate-change-readme.prompt.md**: Add prompt to generate changelog from recent changes.
- **.github/prompts/summarize-changes.prompt.md**: Add prompt to summarize changes since last entry.
- **.github/prompts/generate-full-readme.prompt.md**: Add prompt to generate a full README.

### ⚙️ Configuration
- **.github/copilot-instructions.md**: Add global Copilot instructions for the repo.
- **.github/instructions/changelog-format.instructions.md**: Add changelog formatting rules.
- **.github/instructions/readme-update.instructions.md**: Add README update rules.
- **.github/workflows/auto-readme.yml**: Add GitHub Action for automatic changelog generation on push.

---
