# undefinedKi / Yarchi — Second Brain OS follow-up research
Research date: 2026-10-15
Status: PARTIAL — X articles index gated; this is not a complete account export.
Author: https://x.com/undefinedKi
Official repo: https://github.com/undefined-ui/second-brain-os
Guide: https://secondbrainos.dev

## Timeline and source index
- 2026-06-20: Original X article "How to Build an AI Second Brain With Claude and Obsidian That Gets Smarter Every Day" https://x.com/undefinedKi/status/2068306794116501544 . Note: original article predates the September repo release. Covers Obsidian/Claude, MCP, CLAUDE.md interview, projects, skills, live connectors, schedules, least-privilege controls.
- 2026-09-07: Initial repo publication date indicated by secondary reporting; confirm against first commit before treating as exact.
- 2026-09-25: Cursor agent harness token-efficiency teardown added: https://github.com/undefined-ui/second-brain-os/commit/e6100f96d4e6aaf30e2cf099334b502e906b737e
- 2026-09-27: Palantir AIP architecture mapped to home-scale agents: https://github.com/undefined-ui/second-brain-os/commit/c850f4e93383b2f388105a7164bea59217fd187d
- 2026-09-28: Seven-module agent course from prompt to production (context, loop, gate, harness, evals): https://github.com/undefined-ui/second-brain-os/commit/85309787f1038668f989012ac7278cc2a92b70a7
- 2026-09-29: Installable Claude Code agents-course plugin with context-audit, goal-test, evals-bootstrap and loop critic, later gate-check/harness-audit: https://github.com/undefined-ui/second-brain-os/commit/fd3a52337f034457f2f735328db7099196ba9f6d https://github.com/undefined-ui/second-brain-os/commit/245ba2cb07ab5e5b048626e7b2360091d0305e17
- 2026-10-07: Interactive 3D website graph generated from real linked documentation and new secondbrainos.dev domain: https://github.com/undefined-ui/second-brain-os/commit/812f9efc7e2b386b08926520f34969ef001d869d https://github.com/undefined-ui/second-brain-os/commit/c7fa35bd955ef9ea9a0d8fb04d2b80b8f6ad6c1f
- 2026-10-10: Long X article "How to build an AI agent: from one prompt to a production setup" https://x.com/undefinedKi/status/2108911763257254302 . Discusses model/tools/instructions; harness, loops, context, sandboxes, guardrails, verification, workflows vs agents, five orchestration patterns, company case studies, installable repositories. Independent verification of cited metrics still required.
- 2026-10-13: Post about CMU small-model harness optimisation study and test-driven iterative edits; author-reported figures not independently checked: https://x.com/undefinedKi/status/2110034831941709935
- 2026-10-14: Post urging readers to implement the free playbook rather than bookmark it: https://x.com/undefinedKi/status/2110411761719312846
- 2026-10-14: AI creator tool roundup: OpenMontage, Higgsfield skills and CLI, community Higgsfield skills, Phantom video. Claims of tool capabilities/costs not independently checked: https://x.com/undefinedKi/status/2110483138413801661
- 2026-10-14: GitHub website analytics update: https://github.com/undefined-ui/second-brain-os/commit/9173e03d4c40cf1a9ccd3314d0cd4194bcd7afe3

## Higher-level synthesis
What changed: from a concrete, local Markdown + Obsidian knowledge workflow to a public agent-engineering curriculum, audits/evals tools, and an explorable graph documentation website.
Key practical principles:
1. Separate enduring wiki concepts from time-bound project inputs/process/outputs/feedback.
2. Preserve source links and contradictions when ingesting; test retrieval not just graph appearance.
3. Build agent harnesses with scoped tool rights, test-defined completion and tracing.
4. Test cheaper routing/classification against strong models, measure equal quality before replacement.
5. Prefer reproducible benchmarks and isolated fixtures over importing another framework wholesale.
6. Do not treat GitHub MIT licence as a licence to reproduce all X articles verbatim.

## Research limitations
- X article index at https://x.com/undefinedKi/articles returned a login wall.
- Profile only exposed some recent posts; cannot claim comprehensive post enumeration.
- Referenced images/screenshots, quote posts, replies and linked research papers not exhaustively captured or independently verified.
- This record stores links, brief paraphrases and evidence, not full third-party copyrighted X articles.
- No installation or changes to Test-environment- have been made.
## Next audit checkpoints
- Enumerate X articles and original posts with authorised account access if available.
- Inspect image media and inspect external claims independently.
- Check docs and plugin version diffs, then test context-audit, goal-test and evals-bootstrap in an isolated repository.
