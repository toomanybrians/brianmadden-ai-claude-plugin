# brianmadden-ai plugin

A Claude Cowork plugin that connects to [brianmadden.ai](https://brianmadden.ai) — Brian Madden's expert knowledge module for AI.

## What this does

This plugin gives your Claude access to Brian Madden's expert knowledge module: his published arguments, analytical frameworks, evolving positions, and current frontier thinking on AI's transformation of knowledge work and the enterprise.

Install the plugin, and your Claude can:

- **Get Brian's position** on any topic he's written about
- **Apply his frameworks** (the invisible 80%, factory electrification, post-application era, and more) to your own problems
- **Track his frontier thinking** — where his head is right now, not just what he's published
- **Challenge your arguments** from his perspective using his reasoning style and evidence base

## Commands

| Command | What it does |
|---------|-------------|
| `/brian:position <topic>` | Get Brian's published and evolving position on a topic |
| `/brian:framework <name>` | Load and explain one of Brian's analytical frameworks |
| `/brian:thinking` | Surface Brian's current frontier thinking |
| `/brian:challenge <argument>` | Challenge a claim from Brian's perspective |

## Skills (auto-activated)

- **knowledge-navigation** — How to navigate Brian's knowledge hierarchy and find the right sources
- **apply-frameworks** — How to apply Brian's mental models to new situations
- **voice-and-reasoning** — How Brian thinks, argues, and communicates

## Available frameworks

- `invisible-80-percent` — Why corporate AI strategies miss the tacit knowledge that drives real value
- `factory-electrification` — The 1880s-1920s playbook for understanding AI transformation timelines
- `post-application-era` — Why AI dissolves the application layer entirely
- `workspace-as-control-plane` — The enterprise workspace as AI governance infrastructure
- `7-stage-roadmap` — The progression from AI-as-assistant to AI-as-autonomous-colleague
- `subscribable-brains` — Why experts should publish knowledge repos, not content

## How it works

The plugin connects to the brianmadden.ai MCP server — a live knowledge API backed by Brian's expert knowledge module. The content updates as Brian thinks. His `thinking.md` changes frequently, `synthesis.md` updates when new posts are published, frameworks evolve as arguments develop.

This is a proof of concept for the [subscribable brains](https://brianmadden.ai) thesis: the first expert knowledge module shipped as a Cowork plugin.

## About Brian Madden

VP Technology Officer & Futurist at Citrix. 32 years in end-user computing and digital workplace. 6 books, 2,000+ articles, 1,000+ talks globally. Writes about how AI reshapes knowledge work at the Citrix blog and on LinkedIn.

- [Citrix blog](https://www.citrix.com/blogs/?s=bmadden&type=author)
- [LinkedIn](https://www.linkedin.com/in/bmadden/)
- [brianmadden.ai](https://brianmadden.ai)

## License

Dual-licensed. Code and configuration (JSON) under MIT. Written content (skills and commands) under CC-BY-4.0.
