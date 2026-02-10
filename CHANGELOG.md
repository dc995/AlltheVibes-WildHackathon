# Changelog


## [2026-02-10] — Changes `697d4b0` to `520f59f`

### 🆕 New Features
- feat: add Dad Joke Agent - pun-powered AI comedy companion

### 📦 Other
- Merge pull request #11 from lshade/feature/knock-knock

<details><summary>Files changed</summary>

```
 DadJokes/.env.example      |  2 ++
 DadJokes/README.md         | 65 ++++++++++++++++++++++++++++++++++
 DadJokes/dad_joke_agent.py | 88 ++++++++++++++++++++++++++++++++++++++++++++++
 DadJokes/requirements.txt  |  2 ++
 4 files changed, 157 insertions(+)
```
</details>

---




## [2026-02-10] — Changes `89af5f0` to `e1a3f6c`

### 🆕 New Features
- feat: add AI Chaos Agent Toolkit - 6 agents + prompt playground

### 📦 Other
- Merge pull request #8 from MarziZadeh/feature/marzi

<details><summary>Files changed</summary>

```
 .env.example               |   4 ++
 .gitignore                 |   3 ++
 agents/__init__.py         |   1 +
 agents/chaos_visualizer.py | 126 +++++++++++++++++++++++++++++++++++++++++++++
 agents/code_reviewer.py    |  97 ++++++++++++++++++++++++++++++++++
 agents/commit_whisperer.py |  84 ++++++++++++++++++++++++++++++
 agents/repo_copilot.py     | 121 +++++++++++++++++++++++++++++++++++++++++++
 agents/router.py           | 114 ++++++++++++++++++++++++++++++++++++++++
 agents/sql_generator.py    |  83 +++++++++++++++++++++++++++++
 config.py                  |  34 ++++++++++++
 main.py                    |  92 +++++++++++++++++++++++++++++++++
 prompts/chaos.md           |  24 +++++++++
 prompts/code_review.md     |  20 +++++++
 prompts/sql_generator.md   |  23 +++++++++
 prompts/summarizer.md      |  20 +++++++
 requirements.txt           |   3 ++
 16 files changed, 849 insertions(+)
```
</details>

---




## [2026-02-10] — Changes `9ec00ba` to `978201f`

### 📦 Other
- Merge pull request #5 from lshade/feature/knock-knock
- Knock Knock Who's There

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




## [2026-02-10] — Changes `65b66d8` to `b3855fc`

### 🆕 New Features
- feat: add README changelog generator skill with prompts, instructions, and CI workflow

### 📦 Other
- Merge pull request #2 from dc995/feat/readme-changelog-generator

<details><summary>Files changed</summary>

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
