# Changelog


## [2026-02-10] — Changes `d47e40b` to `0b1f373`

### 📝 Documentation
- docs: update changelog and README with KnockKnock agent and Nemo README merge

### 📦 Other
- Merge pull request #5 from lshade/feature/knock-knock
- Knock Knock Who's There
- Merge pull request #4 from ZacharyLuz/main
- 🐠 Merged README: Nemo mascot + auto-doc engine + full swarm guide
- 🐠 Nemo README — Just keep pushing! Contribution guide for the swarm

<details><summary>Files changed</summary>

```
 CHANGELOG.md                    |  13 +++
 KnockKnock/.env.example         |   2 +
 KnockKnock/.gitignore           |   5 ++
 KnockKnock/README.md            |  58 ++++++++++++
 KnockKnock/knock_knock_agent.py |  88 ++++++++++++++++++
 KnockKnock/requirements.txt     |   2 +
 README.md                       | 191 +++++++++++++++++++++++++++++-----------
 7 files changed, 306 insertions(+), 53 deletions(-)
```
</details>

---



## [2026-02-10] — Knock Knock + Nemo README (`711526e` to `978201f`)

### 🆕 New Features
- **KnockKnock/knock_knock_agent.py**: Add AI-powered knock-knock joke agent using OpenAI API. Every response is a knock-knock joke.
- **KnockKnock/requirements.txt**: Add dependencies (openai, python-dotenv).
- **KnockKnock/.env.example**: Add API key template for agent configuration.
- **KnockKnock/README.md**: Add setup guide and usage instructions for the knock-knock agent.

### 📝 Documentation
- **README.md**: Major rewrite with Nemo ASCII art mascot, contribution guide, swarm table, and consolidated project documentation (PR #4 by ZacharyLuz).

---

## [2026-02-10] — Swarm awakens (`a5885fd` to `b3855fc`)

### 🆕 New Features
- **vibe_oracle.py**: Add the Vibe Oracle — a chaotic vibe generator with randomized vibes, intensity levels, and prophecies. Run with `python vibe_oracle.py [query]`.
- **swarm_mascot.py**: Add ASCII art mascot and swarm banner for the All the Vibes Agent Swarm. Run with `python swarm_mascot.py`.

### ⚙️ Configuration
- **.gitignore**: Add Python, Node.js, and OS-specific ignore rules.

### 📝 Documentation
- **README.md**: Merge PR #2 adding the changelog generator skill, prompts, instructions, and CI workflow.

<details><summary>Files changed in PR #2</summary>

```
 .github/copilot-instructions.md                    |  39 +++++++
 .../instructions/changelog-format.instructions.md  |  27 +++++
 .github/instructions/readme-update.instructions.md |  24 +++++
 .github/prompts/generate-change-readme.prompt.md   |  66 ++++++++++++
 .github/prompts/generate-full-readme.prompt.md     |  39 +++++++
 .github/prompts/summarize-changes.prompt.md        |  31 ++++++
 .github/workflows/auto-readme.yml                  | 112 +++++++++++++++++++++
 .vscode/skills/readme-changelog-generator/SKILL.md |  98 ++++++++++++++++++
 CHANGELOG.md                                       |  18 ++++
 README.md                                          |  86 ++++++++++++++++
 10 files changed, 540 insertions(+)
```
</details>

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
