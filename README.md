# Text-to-Video: Generating Engaging Videos from Textual Stories

This project presents a novel methodology for creating engaging videos from textual story prompts, focusing on the popular Indian animated character Chhota Bheem. By combining advanced techniques in natural language processing, image generation, and video interpolation, we aim to simplify and democratize the video creation process.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)

## Overview

Traditional video creation often requires specialized skills, resources, and significant time investment. This project addresses these barriers by providing an automated system that transforms textual narratives into visually captivating comic videos featuring Chhota Bheem.

## Features

- Text-to-video generation based on user-provided story prompts
- Fine-tuned Stable Diffusion model for Chhota Bheem-specific image generation
- Coreference resolution for maintaining narrative coherence
- Frame interpolation for smooth video animations
- Performance evaluation using CLIP Score

## Installation

To clone and set up this project, follow these steps:

```bash
git clone https://github.com/aryanntated/Text-to-Video.git
cd Text-to-Video
```

## Methodology

Our approach integrates several key components:

1. **Fine-tuned Stable Diffusion Model**: Generates contextually relevant anchor frames based on the input prompts.
2. **SpanBERT-large Model**: Performs coreference resolution to maintain narrative coherence.
3. **Google's Frame Interpolation (FILM) Algorithm**: Creates smooth transitions between anchor frames.

## Results

- The system demonstrates effectiveness in generating coherent videos, particularly for shorter prompts.
- Performance is evaluated using the CLIP Score, showing improved results compared to baseline models.
- Challenges in maintaining coherence with longer and more complex prompts have been identified and discussed.

## Contributing

We welcome contributions to improve this project. Please feel free to submit issues or pull requests.

