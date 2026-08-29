---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Below are the projects I have worked on so far, both published and ongoing, starting from the most recent one. Also on [Google Scholar](https://scholar.google.com/citations?user=MDAYFawAAAAJ&hl=en) and [ORCID](https://orcid.org/0009-0005-1742-0137).

Equal contribution denoted by \*.

---

## Density-Informed Pseudo-Counts for Calibrated Evidential Deep Learning

Pietro Carlotti\*, **Nevena Gligić**\*, Arya Farahi. *STAI-X*, 2026. &nbsp;<span style="color:#a51c30">**Best Paper Award**</span>

[arXiv](https://arxiv.org/abs/2602.01477) · [Code](https://github.com/NevenaGligic/DIP-EDL) · [Poster](/files/dip_edl_poster.pdf)
{: .notice--info}

**Research Question.** How to make an AI system more reliable under distributional shifts, when the data it sees comes from a different distribution than the data it was trained on?

**Approach.** Introduced DIP-EDL, an EDL parametrization that decouples class prediction from the magnitude of uncertainty by separately estimating the conditional label distribution and the marginal covariate density. This separation preserves evidence in high-density regions while shrinking predictions toward a uniform prior for OOD data.

**Applications.** Fraud detection, medical diagnosis, autonomous driving, and disaster response management — domains where a confidently wrong answer is far more costly than an abstention.

**Methods.** Normalizing flows (MAF), evidential deep learning.

---

## Robust-by-Design Distributional Learning from Contaminated Samples

**Nevena Gligić**, Arya Farahi. *Under review, 2026.*

Paper and code coming soon. · [Video](https://www.youtube.com/watch?v=rRlbWiD3NBs)
{: .notice--info}

**Research Question.** How to achieve a distributional objective when the training sample is contaminated?

**Approach.** CC-MMD (contamination-corrected maximum mean discrepancy) is a design-based estimator that combines cheap, noisy proxy scores over the full sample with audited residual corrections over a small verified subset, to recover the oracle MMD that would have been measured on clean data.

**Applications.** Galaxy population inference with star contamination, LLM-assisted filtering of political content, and species-distribution inference from environmental DNA.

**Methods.** Normalizing flows (IAF), VAE, GAN, MLP.

---

## Unsupervised Bayesian Probabilistic Signal Detection in Noisy Environments

**Nevena Gligić**, Arya Farahi. *In preparation.*

Paper and code coming soon. · [Poster](/files/bpsd_poster.pdf)
{: .notice--info}

**Research Question.** How to detect a signal in a low signal-to-noise ratio (SNR) regime without labels, and without assumptions on the signal distribution?

**Approach.** BPSD models the data and noise distributions explicitly with normalizing flows and uses Bayesian inference to assign a detection probability to each candidate. Because the signal distribution is never assumed, the framework transfers across domains where the noise is well characterised but the target is not.

**Applications.** Gravitational-wave detection, galaxy detection, medical imaging, radar systems, and other applications where target signal is not observed clean.

**Methods.** Normalizing flows (MAF), CNN, GMM, autoencoders.

---

## AI-Driven Utility Monitoring and Anomaly Detection for City-Operated Buildings

**Nevena Gligić**, Vineet Burugu, Arya Farahi, Matt Kammer-Kerwick. *In preparation.* In collaboration with the City of Austin.

Paper coming soon.
{: .notice--info}

**Research Question.** How to detect extreme energy consumption across a portfolio of city-operated buildings in real time?

**Approach.** A forecasting and anomaly-detection pipeline built on a time-series foundation model, paired with an interactive dashboard that translates each flagged event into estimated cost and CO₂ impact. This allows the people acting on the alerts to triage them by consequence rather than by anomaly score.

**Applications.** Improved operational efficiency, reduced waste, lower emissions, and lower costs.

**Methods.** Chronos Bolt time-series foundation model, transformers, ARIMA baselines.

*The dashboard is deployed with the City of Austin and is not publicly accessible.*
