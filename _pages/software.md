---
title: "Software"
permalink: /software/
author_profile: true
layout: archive
---

{% if site.author.github %}
  <div class="wordwrap">
    You can also find my projects on 
    <a href="https://github.com/{{ site.author.github | uri_escape }}">{{ site.author.github }}</a>.
  </div>
{% endif %}

Here I list selected software tools, scripts, and research codebases I have developed or contributed to as part of my research and teaching efforts.

---

## Real-Time HD-sEMG Motor Intent Decoder

A MATLAB-based pipeline for real-time decomposition of high-density surface EMG signals for intent-driven control of hand exoskeletons.

<!--
- 🔗 [GitHub Repository](https://github.com/YOUR_USERNAME/hdsemg-decoder)
- 🛠️ Technologies: Python, NumPy, FastICA, PyTorch
- 📄 Description: Extracts motor unit firings from HD-sEMG and decodes finger-level motor intent.
-->

---

## Battery RUL Prediction Toolkit

A machine learning framework to predict remaining useful life of lithium-ion batteries using DNNs and CNNs.

- 🔗 [GitHub Repository](https://github.com/YOUR_USERNAME/battery-rul)
- 🛠️ Technologies: Python, scikit-learn, TensorFlow
- 📄 Description: Provides preprocessing, feature extraction, and time-to-failure estimation tools.

---

## Motion Planning Sandbox

An experimental C++/Python toolkit for benchmarking real-time local path planning algorithms for autonomous driving.

- 🔗 [GitHub Repository](https://github.com/YOUR_USERNAME/path-planning-sandbox)
- 🛠️ Technologies: C++, Python, ROS, RViz
- 📄 Description: Supports motion planning under constraints using MPC and convex solvers.
