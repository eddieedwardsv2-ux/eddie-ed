# How to build an AI agent: from one prompt to a production setup
Author: Yarchi (@undefinedKi)
Published: 2026-10-10
Type: X long-form article
Source: https://x.com/undefinedKi/status/2108911763257254302
Archive format: original structured synopsis and source pointer, not a verbatim transcript.
Availability: substantial article accessible; detailed third-party company metrics unverified.

## Main ideas
- Agent = model, tools, instructions. Production capability hinges on harness around model.
- Harness elements: model/tool loop; selective context and memory; sandbox; permissions; evaluators; traceability.
- Workflows use fixed code paths; agents choose their own steps. Production stacks often combine both.
- Five common orchestration patterns: chaining, routing, parallelism, orchestrator-workers, evaluator-optimizer.
- Start with one effective agent; split into specialists when genuine responsibilities differ.
- Use checkers, tests, and bounded approval for risky actions.
- Distinguish coding agents, code review agents, migration agents and other specific agent classes.

## Named implementation references (source-linked)
Anthropic Claude Code Action https://github.com/anthropics/claude-code-action
gstack https://github.com/garrytan/gstack
Superpowers https://github.com/obra/superpowers
Trail of Bits Skills https://github.com/trailofbits/skills
Anthropic knowledge-work plugins https://github.com/anthropics/knowledge-work-plugins
Anthropic customer support quickstart https://github.com/anthropics/claude-quickstarts/tree/main/customer-support-agent
GPT Researcher https://github.com/assafelovic/gpt-researcher

## Testable opportunities
Compare one agent versus multiple agents on measured task completion; run identical evaluator cases; enforce repo isolation and human merge review; save execution logs. Third-party reported counts and outcomes must be checked at their source before adoption.
