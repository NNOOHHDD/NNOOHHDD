### Domain science × AI modeling

I work on physics-based simulation and AI for energy and plant systems — cryogenic hydrogen storage, process plants and fusion facilities.
My approach: build and validate the physics model first, then put surrogate models and LLM agents on top, and check every AI answer against the solver or the expert.

#### Projects

| | |
|---|---|
| **[pigsim-surrogate](https://github.com/NNOOHHDD/pigsim-surrogate)**<br>A transient pipeline-pig solver reproduced from a published paper, and an honest comparison of ML surrogates on it: Gaussian process, MLP ensemble, DeepONet, anomaly detection, valve control with RL, and an MCP server that lets an LLM agent call the solver. | <img src="https://raw.githubusercontent.com/NNOOHHDD/pigsim-surrogate/main/docs/overview.png" width="360"> |
| **[hazop-agent](https://github.com/NNOOHHDD/hazop-agent)**<br>A simple domain-specific AI agent that drafts HAZOP worksheets from P&IDs, with an evaluation tool that shows which hazards the AI handles reliably and where expert time is needed. | <img src="https://raw.githubusercontent.com/NNOOHHDD/hazop-agent/main/docs/report_example.png" width="360"> |

#### How I work
- **Reproduce → validate → predict**, and label which is which.
- **Compare against simple baselines** and report it when they win.
- **Re-verify AI-proposed designs** with the physics solver before trusting them.

**Interests:** scientific machine learning (surrogates, operator learning), uncertainty quantification, inverse design, domain-specific AI agents (tool calling, MCP).
