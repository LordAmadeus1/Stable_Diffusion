# Stable Diffusion Image Generation with Diffusers

This project implements an image generation workflow using the **Stable Diffusion model** from Hugging Face's `diffusers` library.  
The notebook focuses on prompt-based image synthesis through the pre-built Stable Diffusion pipeline.

## Project Overview

The notebook covers the following steps:
- Load the pre-trained Stable Diffusion model from Hugging Face.
- Define a custom text prompt.
- Generate an image based on the prompt using the `StableDiffusionPipeline`.
- Display the resulting image within the notebook interface.

## Technologies Used

- Python
- PyTorch
- Hugging Face Diffusers
- Transformers
- PIL

## Project Structure

Stable_Diffusion/

┣ dreambooth_kawaii.ipynb

┣ Kawaii Generated/

┣ README.md

┣ requirements.txt

## How to Run the Project

1. Clone this repository:
   
     git clone https://github.com/LordAmadeus1/Stable_Diffusion.git
   
     cd Stable_Diffusion
   
3. Install the required dependencies:

   pip install -r requirements.txt


4. Open the notebook:
   
- Launch `dreambooth_kawaii.ipynb` in Google Colab or a local Jupyter environment.
- Enter your custom text prompt when requested.
- Run the remaining cells to generate and view the corresponding image.

## Results

The notebook successfully generates images from text prompts using the official Stable Diffusion pipeline.  
Users can easily modify the input prompt to experiment with different image generations.

Possible future extensions include adding negative prompts, adjusting inference steps and integrating alternative schedulers.
