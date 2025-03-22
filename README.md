# Equitable AI in Dermatology - AJL Kaggle Competition Team 9

Welcome to our project repository for the **Algorithmic Justice League 2025 Kaggle Competition**, the goal for our team was to use dermatological image classification with a focus on fairness and equity across diverse skin tones.

## 📌 Overview

This project aims to build an image classification model that accurately detects and classifies dermatological conditions across a wide range of skin tones. We are participating in the AJL-sponsored Kaggle competition to address biases in current dermatology AI tools, especially for underrepresented groups.

Our notebook walks through a complete ML pipeline using Convolutional Neural Networks, covering:
- Data loading and exploration
- Image preprocessing and augmentation
- Model building (CNN with Keras)
- Training and evaluation
- Predictions for Kaggle submission

## 📊 Dataset

We used the official dataset provided on Kaggle for the `bttai-ajl-2025` competition, which includes:
- `train.csv` - Metadata and labels for training images
- `test.csv` - Metadata for test images
- `sample_submission.csv` - Format for predictions
- Folders with dermatology images organized by condition

## 🧪 Methods Used

- **Libraries**: TensorFlow/Keras, NumPy, Pandas, Matplotlib
- **Model**: CNN-based classifier
- **Data Augmentation**: To combat class imbalance and skin tone variation
- **Performance Metric**: Accuracy

## 🚀 Getting Started

To run the notebook:
1. Make sure you’re in a Kaggle Notebook environment or have access to the dataset.
2. Install any missing libraries:
   ```bash
   pip install keras tensorflow numpy pandas
