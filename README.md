# 🎨 Text-to-Image Generation using Stable Diffusion

An AI-powered Text-to-Image generation system built using Stable Diffusion that converts natural language prompts into high-quality realistic images.

---

## 📌 Project Overview

This project demonstrates how to generate images from text prompts using the Stable Diffusion model.

Stable Diffusion is an open-source deep learning model that creates images by gradually removing noise from random data until a realistic image is formed.

The implementation supports GPU acceleration and follows an industry-style clean pipeline structure.

---

## 🎯 Objective

- To understand diffusion-based generative models.
- To generate high-quality images from text prompts.
- To implement Stable Diffusion using the Hugging Face Diffusers library.
- To demonstrate GPU-based image generation.

---

## 🧠 What is Stable Diffusion?

Stable Diffusion is a latent text-to-image diffusion model capable of generating photo-realistic images from textual descriptions.

It works by:

1. Adding noise to training images.
2. Learning how to remove noise step-by-step.
3. Reconstructing detailed images based on text prompts.

---

## ✨ Features

- 🖼 Text-to-Image generation  
- ⚡ GPU acceleration support (CUDA)  
- 🎯 Prompt & Negative Prompt control  
- 📏 Custom image resolution  
- 🔧 Adjustable inference steps  
- 💾 Automatic image saving  

---

## 🛠 Technologies Used

- Python  
- PyTorch  
- Hugging Face Diffusers  
- Stable Diffusion (runwayml/stable-diffusion-v1-5)  
- PIL (Python Imaging Library)  

---

## ⚙ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/text-to-image-stable-diffusion.git
cd text-to-image-stable-diffusion
```

---

### 2️⃣ Install Dependencies

```bash
pip install torch diffusers transformers accelerate pillow
```

---

## ▶ Usage

### 1️⃣ Run the Script

```bash
python prompt_generating.py
```

---

### 2️⃣ Modify Prompt

Inside the script:

```python
prompt = "A futuristic city at sunset, ultra realistic, cinematic lighting"
negative_prompt = "blurry, low quality"
```

---

## 🔄 How It Works

1. Load Stable Diffusion model.
2. Detect GPU availability.
3. Accept text prompt input.
4. Generate image using diffusion process.
5. Save and display the generated image.

---

## 📊 Model Details

- Model: runwayml/stable-diffusion-v1-5  
- Resolution: 512x512  
- Guidance Scale: 7.5  
- Inference Steps: 40  

---

## 🚀 Future Enhancements

- Web interface using Flask or Streamlit  
- Batch image generation  
- Prompt history storage  
- Fine-tuned custom diffusion model  
- Deployment on cloud (AWS / GCP)  

---

## 👨‍💻 Developer

Divit Chalasani  

---

## 📄 License

This project is developed for academic and educational purposes.

---
