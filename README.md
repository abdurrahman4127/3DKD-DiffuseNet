# Diffusion-Based Knowledge Distillation for Effective Multi-Organ Segmentation with Reduced Computational Time

## 🔬 Overview
This repository contains the official implementation of our proposed model 3DKD-DiffuseNet. Our approach incorporates a  lightweight student model via diffusion-augmented knowledge distillation. Our framework integrates a forward-reverse diffusion process during training to improve robustness without inference overhead, achieving superior accuracy with 2-3× faster computation.

<p align="center">
  <img src="https://github.com/abdurrahman4127/3DKD-DiffuseNet/blob/main/figs/model_ARchitecture.png" alt="Lung Model Architecture" width="1000"/>
</p>

## Key Features

> a novel training-time diffusion regularizer that enhances feature robustness without inference cost

> an architecture-agnostic distillation framework that transfers knowledge to flexible student models

> a synergistic loss approach that couples diffusion-based feature learning with output distillation

> demonstrated efficacy on multiorgan 3D data
  
## 📁 Repository Structure and Usages

    Will be updated soon

## 📊 Dataset

The model is experimented on 2 different categories of data: (1) the publicly available datasets of the BraTS benchmark datasets, and (2) the RAOS dataset. 

🔗 To access RAOS, contact the authors at [github.com/Luoxd1996/RAOS](https://github.com/Luoxd1996/RAOS)


## Citation

Will be updated soon.

## Acknowledgement

We are greatful to the authors of [arxiv.org/abs/2406.13674](arxiv.org/abs/2406.13674) for giving us the access to the RAOS dataset
