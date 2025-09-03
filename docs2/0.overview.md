# Multi-Spectral Image Translator
An AI-Powered Visualization Engine for Astronomical Data

## Objective
To develop a deep-learning system that automatically transforms raw, multi-spectral grayscale data from space telescopes (e.g., Hubble, JWST) into scientifically meaningful and high-fidelity color images. The project aims to create a consistent, replicable, and efficient alternative to manual colorization, enhancing both scientific analysis and public outreach.

## Core Technology
Data Source: Publicly available raw and calibrated data from astronomical archives (e.g., NASA's MAST, ESA's ESASky) in FITS format.

AI Model: An image-to-image translation network, likely a Conditional Generative Adversarial Network (cGAN) or a Diffusion Model, trained on a curated dataset of aligned multi-spectral and scientifically validated color composite images.

Tech Stack: Python, utilizing libraries such as PyTorch/TensorFlow for model development, Astropy for FITS data handling, and NumPy/OpenCV for image processing.

### Models used 
1. **Pix2Pix (Conditional GAN)**: This is the classic, go-to model for your task. It is a type of Generative Adversarial Network (cGAN) designed specifically to learn the mapping from a specific input image to a specific output image, which is exactly what you need.
2. **Conditional Diffusion Model**: This is the more modern, state-of-the-art approach. It is more complex but can produce higher-quality and more detailed images than a GAN, often with more stable training.