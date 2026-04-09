# Prompt Meets Style 🎨
### A Unified Framework for Text-Guided Artistic Style Transfer

A generative AI pipeline that takes a natural language text prompt and produces a high-quality image using **Stable Diffusion XL**, then converts it into a **pencil sketch** using OpenCV-based image processing — no artistic skills required.

---

## 📌 Problem Statement
Traditional image creation requires manual effort or artistic skills, making it hard for non-designers to visualize concepts from text alone. This project solves that by generating clean, high-resolution images from text prompts and converting them into visually interpretable pencil sketches.

---

## ✨ Features
- 📝 **Text-to-Image Generation** — Accepts any natural language prompt and generates a high-quality image using SDXL
- ✏️ **Pencil Sketch Conversion** — Converts generated images into pencil sketches using OpenCV
- 🔌 **Modular Pipeline** — Apply different artistic styles without regenerating the original image
- 🌍 **Versatile** — Works for historical, futuristic, and artistic scene visualization

---

## 🧠 Model & Tech
- **Stable Diffusion XL (SDXL)** — Pre-trained diffusion model for text-to-image generation
- **OpenCV** — Image processing for pencil sketch conversion

---

## 📊 Results
- SSIM score of **~0.6–0.9** between generated images and their sketches, confirming effective preservation of structural details like edges and layout

---

## 🛠️ Tech Stack
- **Model:** Stable Diffusion XL (via Hugging Face Diffusers)
- **Image Processing:** OpenCV
- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebook

---






