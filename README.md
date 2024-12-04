# Text-to-Video Synthesis through Context-Aware Fine-Tuning and Frame Interpolation

This project presents a novel methodology for creating engaging videos from textual story prompts, focusing on the popular Indian animated character Chhota Bheem. By combining advanced techniques in natural language processing, image generation, and video interpolation, we aim to simplify and democratize the video creation process.

## Table of Contents
- [Overview](#overview)
- [Introduction](#introduction)
- [Related Works](#related-works)
- [Features](#features)
- [Installation](#installation)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)

## Overview

https://github.com/user-attachments/assets/9c143062-69fb-4acd-8016-084e671902af



This repository hosts the code, datasets, and results for the paper "Text-to-Video Synthesis through Context-Aware Fine-Tuning and Frame Interpolation". The project introduces a novel architecture for generating high-quality videos from textual descriptions, leveraging advanced AI techniques like fine-tuned Stable Diffusion models, coreference resolution, and frame interpolation.

## Introduction
- Discusses the growing importance of video-based storytelling in the digital age.
- Highlights the challenges of transforming written narratives into engaging videos.
- Overview of the proposed architecture, which uses:
    - Fine-tuned Stable Diffusion for frame generation.
    - FILM algorithm for smooth frame interpolation.
    - Google Text-to-Speech for audio narration.
![Example](https://github.com/HiyaJain22/Text-to-Video/blob/main/Images\chotta_bheem.mp4?raw=true)

## Related Works
- Text-to-Video Synthesis:
    Discussion of existing models like IRC-GAN, Tune-A-Video, and VideoFusion.
    Comparisons of performance metrics (FVD, KVD, CLIP Score).
- Text-to-Image-to-Video Approaches:
    Role of models like TiVGAN and Text2Video-Zero.
- Research Gaps:
    - Challenges in fine-tuning models for domain-specific data.
    - Issues with maintaining contextual coherence across frames.
    - Balancing complexity and coherence in text prompts.

## Features

- Text-to-video generation based on user-provided story prompts
- Fine-tuned Stable Diffusion model for Chhota Bheem-specific image generation
- Coreference resolution for maintaining narrative coherence
- Frame interpolation for smooth video animations
- Performance evaluation using CLIP Score

## Installation

To clone and set up this project, follow these steps:

```bash
git clone https://github.com/HiyaJain22/Text-to-Video
cd Text-to-Video
```
- The main code lies in Final_IPD.ipynb
## Methodology
![architecture](https://github.com/HiyaJain22/Text-to-Video/blob/main/Images/architecture.png?raw=true)

- **Coreference Resolution:**
    - SpanBERT-based model ensures consistency in context across video frames.
- **Stable Diffusion Fine-Tuning:**
    - Adapted for domain-specific datasets (e.g., Chhota Bheem) to generate     accurate video frames.
- **Latents to Frames:**
    - Frame generation using spherical linear interpolation and denoising techniques.
- **Frame Interpolation:**
    - FILM algorithm for seamless transitions and improved motion dynamics.
- **Text-to-Speech Integration:**
    - Google TTS for audio narration, enhancing storytelling with synchronized visuals and sound.

## Results
- Dataset:
    - Custom dataset of Chhota Bheem images and captions.
    - Fine-tuning details, including hyperparameters and preprocessing steps.
- Performance Evaluation:
    - Comparison of baseline and fine-tuned Stable Diffusion models using CLIP Score.
- Prompt Comparison:
    - Analysis of 1-line and multi-line prompts, highlighting the custom model's superior contextual understanding.

## Conclusion
- Summary of contributions, emphasizing advancements in text-to-video synthesis.
- Advantages of fine-tuning models for domain-specific applications.
- Practical applications in education, storytelling, and entertainment.

