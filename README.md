### Simulation and AI for energy plants

I work on the simulation and design of energy plants — cryogenic hydrogen storage, process plants and fusion facilities — and on applying AI to that work.
My approach: check the physics model first (analytic solutions, published results), then put surrogate models and LLM agents on top, and check AI output against the solver or a published expert worksheet.

#### Projects

| | |
|---|---|
| **[pigsim-surrogate](https://github.com/NNOOHHDD/pigsim-surrogate)**<br>A transient pipeline-pig solver reproduced from a published paper, and ML surrogates for it compared against simple baselines: Gaussian process, MLP ensemble, DeepONet, anomaly detection, valve control with RL, and an MCP server that exposes the solver and surrogate as tools for LLM clients. | <img src="https://raw.githubusercontent.com/NNOOHHDD/pigsim-surrogate/main/docs/overview.png" width="360"> |
| **[hazop-agent](https://github.com/NNOOHHDD/hazop-agent)**<br>A simple domain-specific AI agent that drafts HAZOP worksheets from P&IDs, with an evaluation tool that sorts the reference hazards by how often the AI reproduced them, to suggest where expert time is needed. | <img src="https://raw.githubusercontent.com/NNOOHHDD/hazop-agent/main/docs/report_example.png" width="360"> |

#### How I work
- **Reproduce → validate → predict**, and label which is which.
- **Compare against simple baselines** and report it when they win.
- **Re-verify AI-proposed designs** with the physics solver before trusting them.

Code in these repositories was written with an AI coding assistant (Claude Code) under my direction.

**Interests:** scientific machine learning (surrogates, operator learning), uncertainty quantification, inverse design, domain-specific AI agents (tool calling, MCP).
