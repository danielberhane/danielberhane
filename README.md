### Daniel Berhane Araya

I build agentic AI systems for regulated domains and evaluate them the way a model-risk team would: against criteria fixed before the first run, with every decisive output traced to its source. My background is model development and evaluation, first in academic research on energy data and then in banking.

<a href="https://github.com/danielberhane/finvet"><img src="finvet-pipeline.png" alt="FinVet pipeline" width="520"></a>

#### Agentic systems

**[FinVet](https://github.com/danielberhane/finvet)** · agentic financial claim verification

A LangGraph pipeline that checks a financial claim against SEC filings, market data and news. The model interprets the claim and gathers the evidence; deterministic code compares the figure and decides the verdict; a claim without a source-traced figure is declined rather than guessed. Evaluated on 325 held-out claims about 72 US-listed companies, with two models, four runs each, and acceptance criteria defined before testing began.

**[forest-carbon-mcp](https://github.com/danielberhane/forest-carbon-mcp)** · an MCP server giving AI models structured access to 24 years of Global Forest Watch deforestation and carbon data across 165+ countries, built with Erasmus.AI for ClimateGPT.

#### Evaluation and forecasting

**[neighborcast](https://github.com/danielberhane/neighborcast)** · 12-month home price forecasts for 21,605 US neighborhoods, with leakage-tested rolling-origin backtests.

#### Applied ML and systems

**[wattnorm](https://github.com/danielberhane/wattnorm)** · real-time energy anomaly detection for buildings: a LightGBM quantile model with CUSUM, from MQTT through TimescaleDB to Grafana.

**[cuda-kmeans](https://github.com/danielberhane/cuda-kmeans)** · k-means in CUDA C, benchmarked against MPI, OpenMP and a sequential baseline.

#### Earlier work

**[FinVet v1](https://github.com/danielberhane/finvet-v1)** · IEEE BigData 2025, with Duoduo Liao · [paper](https://ieeexplore.ieee.org/document/11400848)

#### Contact

[LinkedIn](https://www.linkedin.com/in/dberhane)
