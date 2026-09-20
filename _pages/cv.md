---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download full CV (PDF)](/files/cv.pdf){: .btn}

Education
======
* **M.Sc. in Control Science and Engineering**, Shanxi University, 2026 (GPA: 3.50/4.00)
  * Research focus: wind power forecasting, time-series foundation models, and large-scale model training.
* **Visiting Research Student (Government-Sponsored)**, The University of Western Australia, Nov. 2024 – May 2025
  * Host supervisor: Professor Tongming Zhou. AI-driven wind power forecasting and large-scale experiments.
Work experience
======
* **Meteorological Foundation Model Algorithm Engineer**, Ming Yang Smart Energy Group Beijing Technology Co., Ltd. (Jul. 2026 – Present)
  * Develop weather forecasting foundation models for renewable-energy applications using large-scale numerical weather prediction, reanalysis, and observational data.
  * Build data-processing, training, inference, evaluation, and deployment workflows informed by state-of-the-art weather models (Pangu-Weather, GraphCast, Aurora).
  * Adapt meteorological foundation-model outputs to downstream wind and solar power forecasting.

Research experience
======
* **DeepWind: A Domain Foundation Model for Wind Power Forecasting** (Sep. 2025 – May 2026)
  * First author and lead developer. Decoder-only Transformer with Regime-Aware Mixture-of-Experts; 560B data points; up to 1.3B parameters on 64 AMD MI250X GPUs across eight Pawsey nodes; 20.86% reduction in zero-shot nMAE.
* **FSDIformer: Frequency-Aware Transformer for Wind Power Forecasting** (Nov. 2024 – May 2025)
  * First author and lead developer. Frequency-sparse attention and downsampling interaction blocks; 11.87% / 5.97% error improvement for ultra-short-term / short-term forecasting.
* **Intelligent Wind and Solar Power Forecasting** (Jun. 2024 – Oct. 2024)
  * Team leader, State Grid competition; researcher, complex-terrain wind forecasting project.

Skills
======
* **Weather AI:** weather forecasting foundation models; Pangu-Weather, GraphCast, Aurora; meteorological data processing; model adaptation, evaluation, inference, and deployment.
* **Energy AI:** wind and solar power forecasting; deterministic and probabilistic prediction; zero-shot and few-shot transfer; graph neural networks for spatiotemporal modelling.
* **Foundation Models:** Transformer and mixture-of-experts architectures, Mamba, long-sequence modelling, pretraining, fine-tuning, and post-training.
* **Distributed Training:** PyTorch, PyTorch Lightning, Hugging Face, DDP, FSDP, DeepSpeed, mixed precision, multi-node multi-GPU training.
* **Data & Systems:** Python, NumPy, pandas, SQL, GluonTS, Linux, Shell, SLURM, Git, HPC experiment management, model deployment.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors and Awards
======
* National Scholarship for Graduate Students, Ministry of Education, 2025
* Outstanding Master's Thesis Award, Shanxi Province, 2026
* Graduate Academic Scholarship, Shanxi University, 2025
* Outstanding Graduate, Henan Institute of Science and Technology, 2023
