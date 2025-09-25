**Hybrid CNN-ViT for Satellite Image Classification**
📌 Overview

This project implements and evaluates a hybrid Convolutional Neural Network (CNN) + Vision Transformer (ViT) model for satellite land classification, distinguishing agricultural vs. non-agricultural regions. Both PyTorch and Keras versions are provided.

⚙️ Key Features

Dataset: 6,000 satellite images (64×64 pixels)

Hybrid Model: CNN feature extractor + ViT with multi-head self-attention

Frameworks: Implemented in PyTorch and Keras/TensorFlow

Evaluation Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix, Classification Report

🏗️ Model Architecture

CNN: 6 convolutional layers for feature extraction

ViT: Transformer encoder layers with position embeddings

Hybrid: CNN features fused with ViT representations for classification

📊 Results

Keras Model: 99.58% accuracy, 99.98% ROC-AUC

PyTorch Model: 99.90% accuracy, 100% ROC-AUC

Both implementations achieve near-perfect performance, showcasing the effectiveness of hybrid CNN-ViT models for remote sensing classification tasks.
