# IITISoC – Diffusion Models for Image Generation

This project was developed as part of IIT Indore Summer of Code 2025. It explores resource-efficient image generation using latent diffusion models (Stable Diffusion) under constrained hardware environments (16GB GPU).

## Features

- Uses Hugging Face Transformers + Diffusers
- Prompts processed via CLIP encoder
- Scheduler-controlled latent diffusion
- LPIPS-based similarity scoring
- Tiling + mixed precision support
- GitHub-compatible notebooks (cleaned metadata)

## How to Run

```bash
# Set up venv and install dependencies
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# Execute the notebook
jupyter nbconvert --to notebook --execute IITISOC-2025.ipynb --inplace
