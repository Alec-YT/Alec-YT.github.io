---
title: "Active learning with physics-informed neural networks for optimal sensor placement in deep tunneling through transversely isotropic elastic rocks"
collection: publications
category: manuscripts
permalink: /publication/2025-11-15-active-learning-pinn-tunneling
excerpt: "Active learning strategy for optimal sensor placement in tunneling using physics-informed neural networks."
date: 2025-11-15
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2511.20574"
---

<a href="https://arxiv.org/abs/2511.20574" target="_blank">
  <img src="/images/paper_2025_active.png"
       alt="Paper thumbnail"
       style="width:100%; max-width:700px; border-radius:6px; margin-bottom:16px;">
</a>

<div style="display:flex; gap:12px; flex-wrap:wrap; margin-bottom:20px;">

<a href="https://arxiv.org/abs/2511.20574" target="_blank">
<img src="https://img.shields.io/badge/arXiv-2511.20574-b31b1b?style=for-the-badge&logo=arxiv&logoColor=white">
</a>

<a href="https://arxiv.org/pdf/2511.20574.pdf" target="_blank">
<img src="https://img.shields.io/badge/PDF-Download-blue?style=for-the-badge&logo=adobeacrobatreader&logoColor=white">
</a>

<a href="https://github.com/alec-yt" target="_blank">
<img src="https://img.shields.io/badge/GitHub-Code-24292e?style=for-the-badge&logo=github&logoColor=white">
</a>

</div>

---

## Abstract

This paper presents a deep learning strategy to simultaneously solve Partial Differential Equations (PDEs) and back-calculate their parameters in the context of deep tunnel excavation.

A **Physics-Informed Neural Network (PINN)** model is trained with synthetic data that emulate in situ displacement measurements in the host rock and at the cavity wall, obtained from extensometers and convergence monitoring. Because acquiring field observations can be costly, a **sequential training strategy based on active learning** is introduced to determine the most informative locations for new sensors.

Monte Carlo dropout is used to quantify epistemic uncertainty and query new measurements in regions where the model is least confident. This approach reduces the amount of required field data while optimizing sensor placement.

The method is tested on a circular tunnel excavated in **transversely isotropic elastic rock** and successfully reconstructs the displacement field while identifying mechanical parameters such as the Young’s moduli, shear modulus, stress ratio, and bedding orientation.

---

## Figures

<div style="display:flex; gap:20px; flex-wrap:wrap; margin-bottom:20px;">

<div style="flex:1; min-width:300px;">
<img src="/images/pinn_framework.png" style="width:100%; border-radius:6px;">
<p style="text-align:center;"><em>Overview of the active learning framework.</em></p>
</div>

<div style="flex:1; min-width:300px;">
<img src="/images/pinn_results.png" style="width:100%; border-radius:6px;">
<p style="text-align:center;"><em>Prediction of displacement field around the tunnel.</em></p>
</div>

</div>

---

## BibTeX

<details>
<summary><strong>Click to expand citation</strong></summary>

<pre>
@article{tristani2025active,
  title={Active learning with physics-informed neural networks for optimal sensor placement in deep tunneling through transversely isotropic elastic rocks},
  author={Tristani, Alec and ...},
  journal={arXiv preprint arXiv:2511.20574},
  year={2025}
}
</pre>

</details>
