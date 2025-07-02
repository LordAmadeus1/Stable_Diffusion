# Stable Diffusion Image Generation with Diffusers

This project implements an image generation workflow using the **Stable Diffusion model** from Hugging Face's `diffusers` library.  
The notebook focuses on prompt-based image synthesis through the pre-built Stable Diffusion pipeline.

## Project Overview

A complete inference pipeline was created to:
- Load the pre-trained Stable Diffusion model from Hugging Face.
- Generate images conditioned by a text prompt using the `StableDiffusionPipeline`.
- Adjust parameters such as inference steps, image dimensions, and guidance scale.
- Display the generated images in the notebook environment.

## Technologies Used

- Python
- PyTorch
- Hugging Face Diffusers
- Transformers
- PIL

## Project Structure

Stable_Diffusion/

┣ stable_diffusion_pipeline.ipynb

┣ stable_diffusion_pipeline.ipynb

┣ outputs/

┣ README.md

┣ requirements.txt

## How to Run the Project

1. Clone this repository:
   
     git clone https://github.com/LordAmadeus1/Stable_Diffusion.git
     cd Stable_Diffusion
   
2. Install the required dependencies:

   pip install -r requirements.txt


3. Open the notebook:
   
- Launch `stable_diffusion_pipeline.ipynb` in Google Colab or a local Jupyter environment.
- Run each cell sequentially to load the model and generate images based on your selected prompt.

## Results

The notebook successfully generates images from text prompts using the official Stable Diffusion pipeline.  
It allows simple adjustments to inference parameters and saves the final images in the `/outputs/` directory.

The implementation can be extended by integrating alternative schedulers, adding negative prompts, or customizing the sampling loop.
