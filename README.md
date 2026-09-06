# NeuroVisionAI
# 🧠 NeuroVision AI
## Deep Learning-Based Brain Tumor MRI Classification System

![Python](https://img.shields.io/badge/Python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red)
![VGG16](https://img.shields.io/badge/Model-VGG16-purple)
![License](https://img.shields.io/badge/Project-Educational-green)

---

# 🧠 Overview

**NeuroVision AI** is a deep learning-based web application designed to analyze **Brain MRI images** and classify them into different brain tumor categories.

The project uses **Convolutional Neural Networks (CNNs)** and **VGG16 Transfer Learning** to perform MRI image classification.

The application provides a modern **black-themed Streamlit interface** where users can upload a Brain MRI image and receive an AI-generated prediction along with confidence scores and visual performance analysis.

---

# 🚀 Features

✨ Premium Black Futuristic UI  
🧠 Brain MRI Image Classification  
🤖 VGG16 Transfer Learning Model  
🔬 Custom CNN Model Comparison  
📊 Prediction Confidence Visualization  
📈 Interactive Model Performance Dashboard  
🧠 Brain Tumor Educational Guide  
🤖 Deep Learning Pipeline Explanation  
📁 MRI Image Upload Support  
⚡ Fast AI Prediction  
🌐 Streamlit Web Application  

---

# 🎯 Brain Tumor Classification Categories

The AI model classifies Brain MRI images into the following categories:

| Class | Description |
|------|-------------|
| 🔴 Glioma | Tumor associated with glial cells |
| 🟠 Meningioma | Tumor associated with the meninges |
| 🟣 Pituitary Tumor | Tumor located in the pituitary region |
| 🟢 No Tumor | Dataset category representing MRI images without a tumor |

---

# 🧠 System Architecture

```text
                Brain MRI Image
                       │
                       ▼
              Image Preprocessing
                       │
                       ▼
               Resize (224 × 224)
                       │
                       ▼
             Data Augmentation
                       │
                       ▼
            VGG16 Feature Extractor
                       │
                       ▼
         Global Average Pooling Layer
                       │
                       ▼
                Dense Layers
                       │
                       ▼
              Softmax Classifier
                       │
                       ▼
             Brain MRI Prediction
