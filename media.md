---
layout: default
title: Media
permalink: /media
---

# Code

## TagGen
This is the project page of TagGen published in *Magnetic Resonance in Medicine*:  
[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.30422).

### TagGen: Diffusion-based generative model for cardiac MR tagging super resolution
We developed a diffusion-based generative super-resolution model for MR tagging images and demonstrated its potential to integrate with parallel imaging to reconstruct highly accelerated cine MR tagging images acquired in three heartbeats with enhanced tag grid quality.

<p align="center">
  <img src="{{ '/assets/figures/main-architecture.png' | relative_url }}" width="70%" alt="Main architecture">
</p>

## Results

### Evaluation on synthetic data
- Synthetic low-resolution MR tagging images for a patient with a rate-3.3 acceleration of the two-chamber view at end-diastole and end-systole.
<p align="center">
  <img src="{{ '/assets/figures/figure-2.png' | relative_url }}" width="70%" alt="Figure 2">
</p>

- Quantitative comparisons of REGAIN and TagGen…
<p align="center">
  <img src="{{ '/assets/figures/figure-5.png' | relative_url }}" width="70%" alt="Figure 5">
</p>

### Evaluation on prospective data
- Volunteer, rate-10, 1.5T.
<p align="center">
  <img src="{{ '/assets/figures/figure-3.png' | relative_url }}" width="70%" alt="Figure 3">
</p>

- Patient, nominal rate-10, 3T.
<p align="center">
  <img src="{{ '/assets/figures/figure-4.png' | relative_url }}" width="70%" alt="Figure 4">
</p>

- TagGen enhancing cine tagging MRI (two-, three-, four-chamber views), 1.5T.
<p align="center">
  <img src="{{ '/assets/figures/figure-s1.gif' | relative_url }}" width="60%" alt="Figure S1">
</p>

## Citation
If this work is helpful for your research, please consider citing:

- **TagGen: Diffusion-based generative model for cardiac MR tagging super resolution**  
  Sun C, Thornburgh C, Wang Y, Kumar S, Altes TA.  
  *Magnetic Resonance in Medicine*, 2025; 94(1):362–372.
