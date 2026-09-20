---
title: "DeepWind: A Domain Foundation Model for Wind Power Forecasting"
excerpt: "1.3B-parameter decoder-only Transformer with Regime-Aware MoE for zero-shot probabilistic wind power forecasting. Sep 2025 – May 2026."
collection: portfolio
---

First author and lead developer. DeepWind is a domain foundation model for zero-shot and few-shot probabilistic wind power forecasting across unseen sites.

- Developed a decoder-only Transformer with a **Regime-Aware Mixture-of-Experts** architecture.
- Curated approximately **560 billion** multi-source time-series data points and designed **WindBench**, an eight-dataset benchmark with strict separation between pretraining and evaluation data.
- Trained models of up to **1.3B parameters** on **64 AMD MI250X GPUs** across eight Pawsey supercomputing nodes using distributed data parallelism, mixed precision, and gradient accumulation.
- Reduced average zero-shot nMAE by **20.86%** relative to the strongest competing time-series foundation model.
- Released source code and model weights publicly.

[Code](https://github.com/Hexian-2001/DeepWind) · [Model weights](https://huggingface.co/Hexian-2001/DeepWind1.0-890M) · [Paper](https://doi.org/10.1016/j.energy.2026.141793)
