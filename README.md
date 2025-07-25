# Facial Expression Recognition using CNN (FER2013 Dataset)

This project is a deep learning-based system to recognize human facial expressions from grayscale images using Convolutional Neural Networks (CNNs). The model is trained and evaluated on the **FER-2013** dataset.

---

## 📌 Overview

Facial expression recognition is an important application in emotion AI, HCI, and surveillance systems. This project performs classification of 48x48 pixel face images into one of the following 7 emotions:

- 😠 Angry
- 😢 Disgust
- 😨 Fear
- 😄 Happy
- 😐 Neutral
- 😕 Sad
- 😲 Surprise

---

## 🧠 Model Architecture

The model uses a **CNN (Convolutional Neural Network)** architecture composed of:

- Multiple `Conv2D` + `ReLU` + `MaxPooling` layers
- `Dropout` layers to prevent overfitting
- Fully connected `Dense` layers
- Final `Softmax` layer for 7-class classification

---

## 🗂️ Dataset: FER-2013

- Source: [Kaggle FER-2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013)
- Format: CSV containing 48x48 grayscale pixel values and emotion labels
- Total Images: ~35,000
- Classes: 7 (see above)

---

## 🛠️ Installation & Setup

Run the project on [Google Colab](https://colab.research.google.com/) or locally using Python 3.10+ with the following libraries:

