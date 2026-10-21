I'm an AI engineer working on agentic systems, LLM evaluation, and AI reliability. My background includes research using energy data and several years in banking, where I developed credit risk models and worked in stress testing and reporting. My focus is making AI results reliable, traceable, and grounded in evidence.

## What I'm working on

**[FinVet](https://github.com/danielberhane/finvet)** checks financial claims, such as "Apple's fiscal 2024 revenue was $391 billion," against SEC filings, market data and news. A LangGraph pipeline routes each claim to a specialized agent. A language model interprets the claim and gathers the evidence, and deterministic code makes the final comparison against the reported figure. When no reliable figure is available, FinVet returns "not enough information."

I evaluated it on 325 held-out claims about 72 publicly traded companies, with two models and four runs each. Beyond accuracy, the evaluation checks which tools each agent called, whether every number traces back to its source, and how consistent the answers are across runs.

<p align="center"><a href="https://github.com/danielberhane/finvet"><img src="finvet-pipeline.png" alt="FinVet pipeline" width="640"></a></p>

## Other projects

- **[forest-carbon-mcp](https://github.com/danielberhane/forest-carbon-mcp)**: an MCP server giving AI models structured access to 24 years of Global Forest Watch deforestation and carbon data, built with Erasmus.AI for ClimateGPT.
- **[neighborcast](https://github.com/danielberhane/neighborcast)**: 12-month home price forecasts for 21,605 US neighborhoods, with leakage-tested rolling-origin backtests.
- **[wattnorm](https://github.com/danielberhane/wattnorm)**: real-time energy anomaly detection for buildings, from MQTT through TimescaleDB to Grafana.
- **[cuda-kmeans](https://github.com/danielberhane/cuda-kmeans)**: k-means in CUDA C, benchmarked against MPI, OpenMP and a sequential baseline.

## Earlier work

**[FinVet v1](https://github.com/danielberhane/finvet-v1)**, IEEE BigData 2025, with Duoduo Liao · [paper](https://ieeexplore.ieee.org/document/11400848)

[Google Scholar](https://scholar.google.com/citations?user=cmeIfQUAAAAJ)

## Contact

[LinkedIn](https://www.linkedin.com/in/dberhane)
