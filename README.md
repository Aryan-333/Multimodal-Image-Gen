# Multimodal Image Generation

A simple PyTorch implementation of Multimodal Image Generation with both command-line and web interface.

## Setup

1. Install requirements:
```bash
pip install -r requirements.txt  
```
2. Download v1-5-pruned-emaonly.ckpt from https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5/tree/main and save it in the data folder


## Usage

### Command Line
Run text-to-image or image-to-image generation:
```bash
python run.py
```

### Web Interface
Start the local web server:
```bash
python app.py
```
Then open `http://localhost:5001` in your browser.

## Features
- Text to Image generation
- Image to Image transformation
- Adjustable parameters (steps, strength, CFG scale)
- CUDA support for faster generation

## DEMO
Uploading WhatsApp Video 2025-02-13 at 15.58.37.mp4…



## Note
Default device is CPU. To enable CUDA/MPS, modify the `ALLOW_CUDA` or `ALLOW_MPS` flags in the code.


