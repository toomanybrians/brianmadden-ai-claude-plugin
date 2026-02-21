---
name: knowledge-navigation
description: Navigate Brian Madden's structured knowledge system (brianmadden.ai) to find relevant positions, frameworks, and current thinking. Use when the user asks about Brian's views, references his work, or needs to understand how his knowledge is organized. Trigger with "what does Brian think about...", "Brian's position on...", "find Brian's take on...", or "what has Brian written about...".
---

# Knowledge Navigation

Brian Madden's knowledge system (brianmadden.ai) is a structured, living repository accessed through the brianmadden-ai MCP server. It contains his published ideas, frameworks, evolving positions, and current frontier thinking on AI's impact on knowledge work and the enterprise.

## How the knowledge is structured

The system has a clear hierarchy. When the same topic appears in multiple places, prefer higher-authority sources:

1. **Synthesis** (`me/synthesis.md`) — highest authority. Brian's intellectual foundation derived from 30+ published blog posts. This is what he has publicly argued and committed to.
2. **Current thinking** (`context/thinking.md`) — the frontier. Where Brian's head is right now. May supersede synthesis if his thinking has evolved. Updated frequently.
3. **Positions** (`me/positions.md`) — developing ideas not yet published. May become blog posts or may be abandoned.
4. **Frameworks** (`frameworks/`) — standalone explainers for his core mental models.
5. **Posts** (`posts/`) — full text of published work. The original arguments with all the evidence and examples.

## Available MCP tools

Use these tools from the brianmadden-ai server:

- `get_loading_instructions` — read first to understand the full system
- `get_file` — read any file by path (e.g., `me/synthesis.md`, `me/positions.md`)
- `list_files` — see everything available
- `search` — find mentions of a topic across all files
- `get_framework` — get a specific framework by name
- `get_current_thinking` — get Brian's frontier thinking

## Loading strategy

For broad questions about Brian's views:
1. Start with `get_current_thinking` for the frontier
2. Then `search` for the specific topic
3. Read `me/synthesis.md` for the published foundation
4. Read relevant framework files for structured explainers

For specific topics:
1. `search` for the topic first
2. Read the most relevant files from results
3. Check `get_current_thinking` for any recent evolution

## Key distinctions

- **Published vs. evolving**: Synthesis is what Brian has publicly argued. Positions and thinking.md are where he's heading. The gap between them is where the interesting work is.
- **Uncertainty is real**: Brian publicly says "I don't know" and updates his views when evidence changes. If his position on something is uncertain, represent that uncertainty.
- **Don't invent positions**: If Brian hasn't addressed a topic, say so. You can reason from his frameworks, but flag it: "Brian hasn't written about this specifically, but based on his frameworks..."

## Freshness awareness

Check dates on the files you draw from. `context/thinking.md` is the frontier and most time-sensitive. If it's more than a few weeks old, note that his current views may have evolved. Published posts and frameworks don't go stale in the same way.
