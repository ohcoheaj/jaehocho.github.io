---
title: "EPAR — Multi-Modal Industrial Anomaly Detection"
excerpt: "Embedding predictive adaptation and refinement for RGB–3D industrial anomaly detection (WACV 2027)."
header:
  teaser: epar_feature_adaptation.png
collection: portfolio
---

Official implementation of **EPAR: Embedding Predictive Adaptation and Refinement for Multi-Modal Industrial Anomaly Detection** (WACV 2027).

* Stage 1: multi-level embedding prediction (EMA target encoders, VIC regularization) adapts RGB and 3D point-cloud features.
* Stage 2: a Noise Suppression Network trained on synthesized pseudo anomalies refines memory-bank anomaly maps.
* Code: [github.com/ohcoheaj/EPAR](https://github.com/ohcoheaj/EPAR)

{% include base_path %}
![EPAR feature adaptation]({{ base_path }}/images/epar_feature_adaptation.png)
