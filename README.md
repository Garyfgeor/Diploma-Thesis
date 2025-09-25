# Diploma-Thesis
# Data Generation and Machine Learning-Based Image Restoration in 3D Synthetic Environments

This repository contains the implementation of my diploma thesis, which focuses on the **removal of lens flare artifacts from RGB images** using **Generative Adversarial Networks (GANs)** with spatial attention mechanisms. The work combines **synthetic dataset generation in Unreal Engine** with **deep learning-based image restoration**, providing both training pipelines and a real-time restoration system.


---

## 🚀 Overview
Lens flare is a common optical artifact caused by strong light sources (e.g., the sun), degrading image quality and obscuring critical details. This thesis presents a novel workflow for:

- Generating **synthetic paired datasets** (flare + clean) using **Unreal Engine 5**  
- Training a **SpA-GAN** model (Spatial Attention GAN, adapted from cloud removal tasks) for lens flare removal  
- Evaluating results with both **quantitative metrics (PSNR, SSIM, GRVI)** and qualitative analysis  
- Implementing a **real-time flare removal system** for live inference and visualization  

🎥 Demo video: [Real-Time Flare Removal](https://youtu.be/LVj18BssUfc)

---

## ✨ Contributions
- 📊 Study of lens flare impact on image quality  
- 🔧 Adaptation of **SpA-GAN** for flare removal with modified training strategies  
- 🗂️ Creation of a **synthetic dataset** with controlled environmental conditions (lighting, flare variations, camera paths)  
- 📈 Performance evaluation with PSNR, SSIM, and GRVI metrics  
- ⚡ Real-time image restoration pipeline using **PyTorch** + **OpenCV**  

---

## 🛠 Tools & Libraries
- **Unreal Engine 5** – synthetic dataset generation (lighting, textures, lens flare simulation, AI camera navigation)  
- **PyTorch** – GAN model training & evaluation  
- **OpenCV** – real-time image capture, preprocessing, and visualization  
- **CUDA-enabled GPU (NVIDIA A40)** – model training & inference acceleration  

---

## 📂 Repository Structure

