# Agent Templates

Opinionated templates and example agent blueprints to help teams quickly create safe, auditable autonomous agents.

While exploring autonomous agents (inspired by some impressive setups I encountered in [Google Jules](https://jules.google.com/session)), I discovered a pattern for building agents that truly shine. These agents spot opportunities, confidently tackle a SINGLE task, execute it with precision, and even create a pull request (PR) in your repo—all autonomously! I reverse-engineered the core mechanics and distilled them into a simple, reusable template.

This repository contains:

- `AGENT_TEMPLATE.md` — Full, configurable agent specification template with mission, boundaries, process, and journaling.
- `AGENT_TEMPLATE_LITE.md` — Compact template for small, single-purpose agents.
- `agent.architect.md`, `agent.bolt.md`, `agent.palatte.md`, `agent.sentinel.md` — Example persona blueprints showing typical responsibilities and process loops.

Getting started
- Copy `AGENT_TEMPLATE.md` and replace the `{{PLACEHOLDERS}}` to create a new agent spec.
- Or you can also use `architect` agent to create your own agent. `architect` is designed to ask you questions and build agent you want in an interactive manner.
- Use the persona examples for guidance on mission, boundaries, and verification steps.

Contributing
- Open an issue or PR with improvements to the templates or additional persona examples.
