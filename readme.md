
# 🐄 Cattle Biometrics Deep Learning Model

## Overview

This project implements a **biometric identification system for cows using nose images**. Leveraging the unique patterns found in bovine nasal prints, we use deep learning to enable high-accuracy, rapid identification of individual cattle. This enhances traceability across the supply chain and boosts consumer confidence in the authenticity of animal-based products.

## 🔍 Motivation

- **Traceability**: Enables efficient and transparent tracking of cattle in the supply chain.
- **Speed**: Achieves a **60% faster identification** compared to traditional methods.
- **Accuracy**: Utilizes deep learning to achieve **98.6% accuracy** with a **processing time of just 9.7 ms/image**.
- **Trust**: Builds consumer trust in dairy/meat product sourcing by ensuring reliable animal identification.

## 🚀 Model Performance

- **Framework**: PyTorch  
- **Architecture**: Convolutional Neural Network (CNN)  
- **Accuracy**: 98.6%  
- **Inference Time**: 9.7 ms/image  

## 🧠 How It Works

1. **Preprocessing**: Resize and normalize nose print images.
2. **Model Architecture**: A CNN model designed for extracting features from nasal patterns.
3. **Training & Validation**: Trained using labeled images of individual cows.
4. **Evaluation**: Evaluated on accuracy, precision, recall, and inference speed.

## 📊 Results

| Metric           | Value         |
|------------------|---------------|
| Accuracy         | 98.6%         |
| Processing Time  | 9.7 ms/image  |
| Model Type       | CNN (Custom)  |

## 📈 Use Cases

- Livestock management systems
- Supply chain and origin traceability
- Livestock insurance claim verification
- Cattle theft detection
