# Diffusion-Based Knowledge Distillation for Effective Multi-Organ Segmentation with Reduced Computational Time

## 🔬 Overview
This repository contains the official implementation of our proposed model 3DKD-DiffuseNet. Our approach incorporates a lightweight student model via diffusion-augmented knowledge distillation. Our framework integrates a forward-reverse diffusion process during training to improve robustness without inference overhead, which achieves superior accuracy with 2-3× faster computation.

<p align="center">
  <img src="https://github.com/abdurrahman4127/3DKD-DiffuseNet/blob/main/figs/model_ARchitecture.png" alt="3DKD-DiffuseNet Architecture" width="1000"/>
</p>

## Key Features

> **Novel Training-Time Diffusion Regularizer:** Enhances feature robustness without inference cost.

> **Architecture-Agnostic Distillation:** Transfers knowledge to flexible student models.

> **Synergistic Loss Approach:** Couples diffusion-based feature learning with output distillation.

## 📁 Repository Structure and Usages

Will be updated soon

## 📊 Dataset

The model is experimented on 2 different categories of data: (1) the publicly available datasets of the BraTS benchmark datasets, and (2) the RAOS dataset.

🔗 To access RAOS, contact the authors at [github.com/Luoxd1996/RAOS](https://github.com/Luoxd1996/RAOS)

## Citation

*Will be updated soon.*

## Acknowledgement

We are grateful to the authors of [https://arxiv.org/abs/2406.13674](https://arxiv.org/abs/2406.13674) for giving us access to the RAOS dataset.
