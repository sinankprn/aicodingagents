# From Chatbots to Agents

A 13-slide deck on how AI coding agents work, tracing the path from chatbots to augmented LLMs, agentic chatbots and AI coding agents. The technical reference is [How Claude Code works](https://code.claude.com/docs/en/how-claude-code-works).

The slide sources live in `deck/project/`. `deck.json` is the index, and each slide is one file in `slides/`. The animated diagrams (cover, chatbot, augmented LLM, agentic loop, coding environment, gather/act/verify, summary) run as small embedded SVG and JS layers that sit on top of static diagrams, so the static version still reads correctly when exported to PDF or PPTX.

## Design system

- Typefaces: Geist (display and text) and Geist Mono (labels, code and metadata)
- Colour roles: model `#5B8CFF`, tools and actions `#3EE0F0`, environment `#A48BFF`, feedback and observations `#FFB86B`, neutral `#ECEEF3` on `#08090D`
