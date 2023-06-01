# Diffusion Models 101

Diffusion models have been around for a while, but it wasn't until stable diffusion in 2022 that they became mainstream. In this workshop, we'll explore their inner workings, and how they accomplish the transformation of random noise into beautiful images and develop a simple diffusion model from the ground up, step-by-step. We'll start by adding random noise to images, and how the process itself can be optimized and automated using schedulers. Next, we'll explore the reverse diffusion process using both Denoising Diffusion Probabilistic Models (DDPMs) and the more efficient Denoising Diffusion Implicit Models (DDIM). We'll also discuss guided diffusion, and diffusion in latent space, the approach taken by stable diffusion. The goal of this session is to get you familiarized with diffusion models, their inner workings, and different approaches to data generation. We'll use Google Colab to build and train a simple diffusion model. You should be comfortable using Jupyter Notebooks, and training simple models in PyTorch.

- Module 1: The Diffusion Process: adding random noise to images
- Module 2: Denoising Diffusion Probabilistic and Implicit Models (DDPMs/DDIMs): reversing the diffusion process
- Module 3: Fine-tuning Pretrained Models and Guided Generation Process: telling the model what you want
- Module 4: Diffusion in Latent Space and Guided Diffusion: less (dimensions) is more (speed)
- Module 5: HuggingFace Diffusers

The goal of this session is to get you familiarized with diffusion models, their inner workings, and different approaches to data generation. We'll use Google Colab to build and train simple diffusion models. You should be comfortable using Jupyter Notebooks, and training simple models in PyTorch.

Open the notebook using [Google Colab](https://colab.research.google.com/github/dvgodoy/DiffusionModels101_ODSC_Europe2023/blob/main/DiffusionModels101.ipynb).
