# Face Emotion Recognition (Project #04)

The fourth project in my **AI/ML Learning Path**. This project marks my transition from classical Computer Vision to **Deep Learning**, specifically focusing on Facial Expression Recognition (FER).

## 📌 Overview
This project implements a Convolutional Neural Network (CNN) to classify human facial expressions in real-time. The model can detect and categorize emotions such as Happy, Sad, Angry, Surprise, Neutral, Fear, and Disgust.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** TensorFlow / Keras, OpenCV, NumPy
* **Architecture:** Convolutional Neural Network (CNN)
* **Dataset:** Trained on the FER2013 dataset (or similar)

## ⚙️ How It Works
1. **Face Detection:** Uses Haar Cascades or MediaPipe to isolate the face from the background.
2. **Preprocessing:** The detected face is cropped, converted to grayscale, and resized to match the input shape of the neural network (e.g., 48x48 pixels).
3. **Feature Extraction:** Multiple Convolutional layers detect patterns like edge orientations, shapes, and complex facial features.
4. **Classification:** Dense layers and a Softmax activation function output the probability for each emotion category.

## 🚀 Quick Start
1. **Install Dependencies:**
   ```bash
   pip install tensorflow opencv-python numpy

*Progress: First Deep Learning project completed! Moving from pixel-math to neural-mapping*
