# Text-to-Video Diffusion Model

This project implements a text-to-video diffusion model using the [Hugging Face Diffusers library](https://huggingface.co/docs/diffusers/index). The model generates short videos based on textual prompts. This project leverages pre-trained diffusion models and fine-tunes them to create high-quality video content.

## Features
- **Text-to-Video Generation:** Generate videos from text prompts using a diffusion model.
- **Model Offloading:** Efficiently manages memory by offloading models to CPU and slicing the VAE.
- **Customizable Output:** Allows users to specify the number of frames and apply negative prompts for fine-tuning quality.

## Project Structure
- `notebook/`: Contains the Colab notebook used for generating the video.
- `src/`: Source code files (if any additional scripts are included).
- `requirements.txt`: Lists all Python dependencies needed to run the project.
- `README.md`: This documentation file.

## Installation

To install the required dependencies, run the following:

```bash
pip install -r requirements.txt

