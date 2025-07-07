# aicte_week3
# Garbage Classification Using EfficientNetV2-B2

This project is an image classification system that automatically categorizes garbage images (e.g., cardboard, glass, metal, paper, plastic) using a convolutional neural network built on **EfficientNetV2-B2**. The model has been improved to achieve higher accuracy by increasing image resolution and training epochs.
## Project Overview
The project aims to classify different types of garbage images to aid in automated waste management and recycling systems. The model leverages **deep learning** to learn patterns and features distinguishing each garbage class.

## Learning Objectives
- Understand the principles of image classification using CNNs and transfer learning.
- Learn how to preprocess and augment image datasets.
- Implement, train, and evaluate a deep learning model in TensorFlow/Keras.
- Experiment with model hyperparameters to improve accuracy.

## Tools and Technologies
- **Python**
- **TensorFlow / Keras**
- **EfficientNetV2-B2**
- **Gradio** (for interactive interface)
- **Matplotlib** (for plotting metrics)
- **Jupyter Notebook**

## Methodology
1. **Dataset Preparation:** Images were resized and normalized.
2. **Model Building:** Used EfficientNetV2-B2 as the base feature extractor.
3. **Training:** The model was trained initially with lower resolution and fewer epochs.
4. **Evaluation:** Accuracy and loss were calculated on test data.
5. **Improvisation:** Increased input image size to 224×224 pixels and raised the number of epochs to improve learning.

## Improvements
To enhance model performance:
- **Image size was increased** from 124×124 to 224×224, allowing the network to capture richer details.
- **Epochs were increased**, giving the model more iterations to learn and reduce error.
- As a result, **test accuracy significantly improved**.
