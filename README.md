# TDD-method

This repository hosts the open-source code and performance statistics for the **TDD-method** (Time-Distributed Data method), developed to enhance immersive VR applications using **neuromorphic data transformations**. The method was introduced in the paper:

**"Neuromorphic Data Transformations for Sustainable VR Art Applications"**  
*Anna Shvets (University of Nottingham, UK)*  
*Anthony Trzepizur (iMSA, France)*  
This research paper was presented at the [**International XR-Metaverse Conference (XRM 2025)**](https://xr-metaverse.org/](https://www.xrm2025.com/) held in **Maastricht**.

## Overview

The **TDD-method** provides an energy-efficient, visually expressive solution for integrating 2D audio-visual artworks into immersive Virtual Reality (VR) environments. Inspired by **spiking neural networks** and **neuromorphic computing**, the approach converts 2D visual input into a series of **time-distributed spike matrices** that are projected into a VR scene.

Key features:
- Improved **VR performance** (higher frame rates, fewer stale frames)
- **Reduced disk space** and **carbon footprint**
- Enhanced **colour palette preservation** through neuromorphic masking
- Real-time interaction and audio-reactive particle systems in **Unreal Engine 5**

## Applications

The TDD method was implemented in the immersive music VR application **Interlace**, which premiered at multiple international festivals including:
- *Sœurs Jumelles Festival* (France, 2024)
- *Festival of Science and Curiosity* (UK, 2024)
- *SXSW Film & TV Festival* (US, 2025)

## Repository Contents

- `/code/`: Python preprocessing pipeline based on pixel-to-spike-time conversion with 3 methods used in the experiment
- `/experiments/`: CSV logs and benchmarking scripts for performance, memory, and sustainability metrics

## Methodology

The TDD-method uses a **pixel-to-firing-time encoding** function that mimics biological latency coding found in the retina. Key steps include:

1. **Color channel separation** and normalization using OpenCV
2. **Spike time encoding** based on Leaky Integrate-and-Fire neuron models
3. **Masking-based preprocessing**, allowing for color fidelity and noise reduction
4. Projection into **Niagara particle systems** in Unreal Engine 5 for real-time rendering
