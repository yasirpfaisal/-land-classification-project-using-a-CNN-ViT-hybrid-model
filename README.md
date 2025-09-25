# 🌍 Hybrid CNN-ViT for Satellite Land Classification  
![Python](https://img.shields.io/badge/python-3.11-blue.svg) ![PyTorch](https://img.shields.io/badge/PyTorch-Framework-red.svg) ![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange.svg)  

> A **hybrid Convolutional Neural Network (CNN) + Vision Transformer (ViT)** model for satellite image classification, distinguishing **agricultural vs. non-agricultural** land. Implemented in both **PyTorch** and **Keras/TensorFlow**.  

---

## 📌 Overview  
This project demonstrates how to build and evaluate a **hybrid CNN-ViT model** for remote sensing land classification.  
Both **PyTorch** and **Keras** implementations are included, achieving **near-perfect accuracy and ROC-AUC scores**.  

---

## ⚙️ Key Features  
- 🛰️ **Dataset**: 6,000 satellite images (64×64 pixels)  
- 🧩 **Hybrid Model**: CNN feature extractor + ViT with multi-head self-attention  
- 🔧 **Frameworks**: PyTorch & Keras/TensorFlow implementations  
- 📊 **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix, Classification Report  

---

## 🏗️ Model Architecture  
- **CNN**: 6 convolutional layers extract low- and mid-level features  
- **ViT**: Transformer encoder layers with positional embeddings & multi-head self-attention  
- **Hybrid Classifier**: Combines CNN + ViT representations for final prediction  

---

## 📊 Results  

| Model          | Accuracy | ROC-AUC |
|----------------|----------|---------|
| **Keras Hybrid**   | 99.58%   | 99.98%  |
| **PyTorch Hybrid** | 99.90%   | 100%    |

✅ Both frameworks deliver **state-of-the-art performance** on the satellite dataset.  


