# 🧠 CNN Fingerprint Reconstruction Model

A deep learning project using **Convolutional Neural Networks (CNN)** to reconstruct and enhance degraded fingerprint images. The model restores ridge clarity from noisy, blurred, and low-quality inputs, improving biometric recognition accuracy for security and forensic applications.

---

## 📌 Project Overview

Fingerprint images captured in real-world conditions often suffer from noise, blur, partial impressions, and poor contrast. These issues reduce the performance of biometric systems.

This project proposes a **CNN-based reconstruction pipeline** that learns to transform degraded fingerprint images into high-quality reconstructed outputs by learning ridge patterns and structural details.

---

## 🚀 Features

- Enhances blurred and noisy fingerprints  
- Restores missing ridge patterns  
- Improves fingerprint clarity and contrast  
- End-to-end deep learning pipeline  
- High-quality reconstructed output  

---

## 🏗️ Model Architecture

- CNN Encoder–Decoder Network  
- Convolution + Batch Normalization + ReLU  
- Loss Functions: MSE / MAE + SSIM  
- Post-processing for ridge enhancement  

---

## 🔧 Tech Stack

- Python  
- TensorFlow / PyTorch  
- OpenCV  
- NumPy  
- Google Colab  

---

## 📂 Dataset

- Public fingerprint datasets (e.g., FVC, NIST SD4)  
- Artificially degraded fingerprint images generated for training  

---

## ⚙️ Pipeline

1. Input fingerprint image  
2. Preprocessing & normalization  
3. Artificial degradation (training only)  
4. CNN-based reconstruction  
5. Output enhanced fingerprint  

---

## 📊 Results

The model successfully reconstructs degraded fingerprints and improves ridge clarity, leading to better matching accuracy compared to traditional enhancement methods.

---
