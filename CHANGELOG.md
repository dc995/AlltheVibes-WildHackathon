# Changelog


## [2026-02-10] — AI Chaos Toolkit + Dad Jokes + Research Docs (`87952b8` to `eb78981`)

### 🆕 New Features
- **main.py**: Add interactive agent router — CLI entry point for all 6 AI agents.
- **agents/router.py**: Add agent routing logic for directing queries to the right agent.
- **agents/chaos_visualizer.py**: Add chaos visualization dashboard agent.
- **agents/code_reviewer.py**: Add AI-powered code review agent.
- **agents/commit_whisperer.py**: Add commit narration agent.
- **agents/repo_copilot.py**: Add repository copilot agent.
- **agents/sql_generator.py**: Add natural language to SQL generator agent.
- **prompts/chaos.md**: Add chaos visualizer prompt template.
- **prompts/code_review.md**: Add code review prompt template.
- **prompts/sql_generator.md**: Add SQL generation prompt template.
- **prompts/summarizer.md**: Add summarizer prompt template.
- **DadJokes/dad_joke_agent.py**: Add Dad Joke Agent — pun-powered AI comedy companion using OpenAI.
- **DadJokes/README.md**: Add setup and usage guide for the Dad Joke Agent.

### 📝 Documentation
- **docs/research/3IQ_FRAMEWORK.md**: Add comprehensive analysis of Microsoft's 3IQ unified intelligence framework.
- **docs/research/AGENT_SWARM_ARCHITECTURE.md**: Add enterprise agent swarm architecture patterns and research.
- **docs/research/README.md**: Add research index documenting framework principles and architecture.
- **README.md**: Update swarm inventory with KnockKnock agent and current project structure.

### ⚙️ Configuration
- **config.py**: Add shared Azure OpenAI config with credential loading from .env.
- **requirements.txt**: Add root dependencies (openai, python-dotenv, rich).
- **.env.example**: Add API key template for Azure OpenAI.
- **.gitignore**: Add additional ignore rules.

---

## [2026-02-10] — Knock Knock + Nemo README (`711526e` to `978201f`)

### 🆕 New Features
- **KnockKnock/knock_knock_agent.py**: Add AI-powered knock-knock joke agent using OpenAI API. Every response is a knock-knock joke.
- **KnockKnock/requirements.txt**: Add dependencies (openai, python-dotenv).
- **KnockKnock/.env.example**: Add API key template for agent configuration.
- **KnockKnock/README.md**: Add setup guide and usage instructions for the knock-knock agent.

### 📝 Documentation
- **README.md**: Major rewrite with Nemo ASCII art mascot, contribution guide, swarm table, and consolidated project documentation (PR #4 by ZacharyLuz).

<details><summary>Files changed</summary>

```
 KnockKnock/.env.example         |  2 +
 KnockKnock/.gitignore           |  5 +++
 KnockKnock/README.md            | 58 +++++++++++++++++++++++++++
 KnockKnock/knock_knock_agent.py | 88 +++++++++++++++++++++++++++++++++++++++++
 KnockKnock/requirements.txt     |  2 +
 5 files changed, 155 insertions(+)
```
</details>

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
