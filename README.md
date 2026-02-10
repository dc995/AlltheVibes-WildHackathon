# 🌀 AlltheVibes — Wild Hackathon 🚀

A chaotic AI hackathon project combining an agent swarm toolkit, joke bots, vibe oracles, and an automated documentation engine — all powered by vibes.

## 🔮 What's in the Swarm

| Agent | Author | Description | Run it |
|---|---|---|---|
| 🌀 AI Chaos Agent Toolkit | MarziZadeh | 6 AI agents + prompt playground (code reviewer, SQL generator, chaos visualizer, commit whisperer, repo copilot, router) | `python main.py` |
| 🔮 Vibe Oracle | ZacharyLuz | Chaotic vibe generator — ask it anything, receive cosmic wisdom | `python vibe_oracle.py "your question"` |
| 🐝 Swarm Mascot | ZacharyLuz | ASCII art mascot + banner for the swarm | `python swarm_mascot.py` |
| 🚪 Knock Knock Agent | lshade | AI agent that answers everything with knock-knock jokes | `cd KnockKnock && python knock_knock_agent.py` |
| 👨 Dad Joke Agent | lshade | AI agent that answers everything with dad jokes | `cd DadJokes && python dad_joke_agent.py` |
| 📝 Auto-Changelog Engine | dc995 | Copilot skill + GitHub Action that auto-generates CHANGELOG.md on every push | Automatic on push to `main` |
| 📚 Research Docs | gabland-msft | 3IQ Framework + Agent Swarm Architecture research | See `docs/research/` |

## Quick Start

```bash
# Clone the repo
git clone https://github.com/shyamsridhar123/AlltheVibes-WildHackathon.git
cd AlltheVibes-WildHackathon

# Install dependencies
pip install -r requirements.txt

# Run the interactive agent router (Chaos Toolkit)
python main.py

# Or run individual tools
python vibe_oracle.py "what should I build?"
python swarm_mascot.py
cd KnockKnock && python knock_knock_agent.py
cd DadJokes && python dad_joke_agent.py
```

### Environment Setup (for AI agents)
```bash
cp .env.example .env
# Edit .env with your Azure OpenAI or OpenAI API keys
```

## Project Structure

```
AlltheVibes-WildHackathon/
├── main.py                                  # 🌀 Interactive agent router
├── config.py                                # Shared Azure OpenAI config
├── requirements.txt                         # Root dependencies
├── .env.example                             # API key template
├── agents/                                  # 🤖 AI Chaos Agent Toolkit
│   ├── router.py                            # Agent routing logic
│   ├── chaos_visualizer.py                  # Chaos visualization dashboard
│   ├── code_reviewer.py                     # AI code reviewer
│   ├── commit_whisperer.py                  # Commit narration agent
│   ├── repo_copilot.py                      # Repository copilot
│   └── sql_generator.py                     # Natural language → SQL
├── prompts/                                 # 📋 Agent prompt templates
│   ├── chaos.md                             # Chaos visualizer prompts
│   ├── code_review.md                       # Code review prompts
│   ├── sql_generator.md                     # SQL generation prompts
│   └── summarizer.md                        # Summarizer prompts
├── KnockKnock/                              # 🚪 Knock-knock joke agent
│   ├── knock_knock_agent.py                 # OpenAI-powered joke agent
│   └── README.md                            # Setup guide
├── DadJokes/                                # 👨 Dad joke agent
│   ├── dad_joke_agent.py                    # OpenAI-powered dad jokes
│   └── README.md                            # Setup guide
├── docs/research/                           # 📚 Research documentation
│   ├── 3IQ_FRAMEWORK.md                     # Microsoft 3IQ framework analysis
│   ├── AGENT_SWARM_ARCHITECTURE.md          # Enterprise agent swarm patterns
│   └── README.md                            # Research index
├── .github/
│   ├── copilot-instructions.md              # Global Copilot behavior rules
│   ├── instructions/                        # Context-specific Copilot rules
│   ├── prompts/                             # Copilot prompt templates
│   └── workflows/auto-readme.yml            # Auto-changelog GitHub Action
├── .vscode/skills/                          # Copilot skill definitions
├── vibe_oracle.py                           # 🔮 Chaotic vibe generator
├── swarm_mascot.py                          # 🐝 ASCII art swarm mascot
├── CHANGELOG.md                             # Auto-generated changelog
└── README.md                                # This file
```

## How the Auto-Documentation Works

On every push to `main`, a GitHub Action + Copilot skill automatically:
1. Reads commit messages and diffs
2. Categorizes changes (Features, Fixes, Refactors, Config, Breaking Changes)
3. Generates a structured changelog entry
4. Prepends it to `CHANGELOG.md`

You can also run the `generate-change-readme` Copilot prompt manually.

## Recent Changes

See [CHANGELOG.md](CHANGELOG.md) for the full auto-generated history.

## Contributing

1. Fork or clone the repo
2. Build anything — agents, skills, utilities, experiments, vibes
3. Use [Conventional Commits](https://www.conventionalcommits.org/): `feat:`, `fix:`, `docs:`, etc.
4. Push fast — speed over polish 🚀
5. The auto-changelog will document everything

## Team

- @shyamsridhar123
- @gabland-msft
- @ZacharyLuz
- @lshade
- @MarziZadeh
- @dc995

## License

MIT License — Built with ❤️ during Wild Hackathon
