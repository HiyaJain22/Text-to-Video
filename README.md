# Text-to-Video: Generating Engaging Videos from Textual Stories

This project presents a novel methodology for creating engaging videos from textual story prompts, focusing on the popular Indian animated character Chhota Bheem. By combining advanced techniques in natural language processing, image generation, and video interpolation, we aim to simplify and democratize the video creation process.

## Table of Contents
- [Overview](#overview)
- [Introduction](#introduction)
- [Related Works](#related-works)
- [Features](#features)
- [Installation](#installation)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)

## Overview

This repository hosts the code, datasets, and results for the paper "Text-to-Video Synthesis through Context-Aware Fine-Tuning and Frame Interpolation". The project introduces a novel architecture for generating high-quality videos from textual descriptions, leveraging advanced AI techniques like fine-tuned Stable Diffusion models, coreference resolution, and frame interpolation.

## Introduction
- Discusses the growing importance of video-based storytelling in the digital age.
- Highlights the challenges of transforming written narratives into engaging videos.
- Overview of the proposed architecture, which uses:
    - Fine-tuned Stable Diffusion for frame generation.
    - FILM algorithm for smooth frame interpolation.
    - Google Text-to-Speech for audio narration.

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
![arcchitecture](https://github.com/HiyaJain22/Text-to-Video/blob/main/Images/architecture.png?raw=true)

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

- The system demonstrates effectiveness in generating coherent videos, particularly for shorter prompts.
- Performance is evaluated using the CLIP Score, showing improved results compared to baseline models.
- Challenges in maintaining coherence with longer and more complex prompts have been identified and discussed.

## Contributing

We welcome contributions to improve this project. Please feel free to submit issues or pull requests.

