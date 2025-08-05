# 🖼️ Image Captioning using ViT-GPT2

This project uses a pre-trained transformer model to automatically generate descriptive captions for input images. It combines computer vision (ViT) and natural language generation (GPT2) to understand and describe visual content.

---

## 🚀 Project Overview

- Converts input images into natural language captions.
- Uses `nlpconnect/vit-gpt2-image-captioning`, a model based on Vision Transformer (ViT) + GPT-2.
- Ideal for tasks like visual storytelling, accessibility tools, and content indexing.

---

## 🧠 Model Architecture

- **ViT (Vision Transformer)** – Encodes the image.
- **GPT-2 (Generative Pre-trained Transformer)** – Decodes and generates a text caption.
- **HuggingFace Transformers** – Pretrained pipeline used directly.

---

## 📦 Dependencies

Make sure to install the following:

```bash
pip install transformers torch pillow
