---
title: "DeepWind: A foundation model for zero-shot wind power forecasting"
collection: publications
category: manuscripts
permalink: /publication/2026-deepwind-foundation-model
excerpt: "DeepWind is a 1.3B-parameter domain foundation model for zero-shot and few-shot probabilistic wind power forecasting across unseen sites."
date: 2026-09-01
venue: "Energy"
paperurl: "https://doi.org/10.1016/j.energy.2026.141793"
citation: "Hexian Wang, Tongming Zhou, Chengzhen Jia, Yushan Liu, and Lingmei Wang. &quot;DeepWind: A foundation model for zero-shot wind power forecasting.&quot; <i>Energy</i>, vol. 360, 141793, 2026."
---

DeepWind is a domain foundation model for wind power forecasting built on a decoder-only Transformer with a **Regime-Aware Mixture-of-Experts** architecture for zero-shot and few-shot probabilistic forecasting across unseen sites. It was trained on approximately **560 billion** multi-source time-series data points and evaluated on WindBench, an eight-dataset benchmark with strict separation between pretraining and evaluation data. Models of up to **1.3B parameters** were trained on 64 AMD MI250X GPUs across eight Pawsey supercomputing nodes. DeepWind reduced average zero-shot nMAE by **20.86%** relative to the strongest competing time-series foundation model. First author; Journal Impact Factor: 10.1.

[Paper (DOI)](https://doi.org/10.1016/j.energy.2026.141793) · [Code](https://github.com/Hexian-2001/DeepWind) · [Model weights](https://huggingface.co/Hexian-2001/DeepWind1.0-890M)
