# Raghav Chamadiya

Co-founder & CEO at Repowise. I build the codebase intelligence layer for AI coding agents.

[repowise.dev](https://repowise.dev) · [X](https://x.com/RaghavChamadiya) · [LinkedIn](https://linkedin.com/in/raghav-chamadiya)

### Repowise: open-source codebase intelligence

[![Stars](https://img.shields.io/github/stars/repowise-dev/repowise?style=flat&color=black)](https://github.com/repowise-dev/repowise)
[![PyPI downloads](https://img.shields.io/pypi/dm/repowise?style=flat&color=black)](https://pypi.org/project/repowise/)
[![License](https://img.shields.io/badge/license-AGPL--3.0%20%2B%20commercial-black?style=flat)](https://github.com/repowise-dev/repowise/blob/main/LICENSE)

Repowise turns a codebase into structured intelligence AI agents can actually use: a graph layer, git history, generated docs, architectural decisions, and code-health signals, exposed through 10 MCP tools for Cursor, Claude Code, and any MCP client. Runs self-hosted and offline.

```bash
pip install repowise && repowise init
```

What it buys you, measured rather than claimed. On a 48-question agent benchmark against a bare agent and four other context tools (43 questions completed by all six arms, paired), Repowise cut output tokens 31.6% and tool calls from 7.2 to 3.8 per question. On a sealed 42-instance retrieval split, `get_answer` hit 0.876 gold-file coverage against 0.610 for the next best tool. Full method and the results that went against us are in [BENCHMARKS.md](https://github.com/repowise-dev/repowise/blob/main/BENCHMARKS.md).

### Also building

- **[Thita.ai](https://thita.ai)**: AI technical interview prep. ~25K users.
- **[Slate](https://tryslate.live)**: voice-first AI tutor. Talk through an idea; it listens, sketches, and explains.


### Research
 
- **[Beyond QA Pairs: Assessing Parameter-Efficient Fine-Tuning for Fact Embedding in LLMs](https://arxiv.org/abs/2503.01131)**, Good-Data workshop @ AAAI 2025. With Ratnakar, Talasila, Agarwal, Doifode.
- Empirical software engineering on defect prediction and code health. The Repowise code-health layer scores files from 25 deterministic markers with no LLM in the loop, validated at ROC AUC 0.74 across 21 repositories.

Senior Staff Data Scientist at Equinix

Building in public.
