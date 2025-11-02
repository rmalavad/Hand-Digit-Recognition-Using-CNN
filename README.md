# Handwritten Digit Recognition Using Convolutional Neural Networks (CNN)

This project implements a **Convolutional Neural Network (CNN)** to recognize handwritten digits from the **MNIST dataset**, using **TensorFlow** as the backend.  
A simple graphical interface allows users to upload, draw, or capture an image for real-time prediction.

---

## 🎯 Project Overview

- Built and trained a CNN model to classify handwritten digits (0–9).  
- Used **TensorFlow** and **Keras** for model creation, training, and evaluation.  
- Implemented **OpenCV** for image processing and checkpoint restoration during prediction.  
- Developed a **GUI using PyGTK 3.0** for user interaction.  
- The system allows users to:
  - **Upload** an image for prediction  
  - **Capture** an image using a camera  
  - **Display** a stored image  
  - **Draw** digits via gestures for testing  

---

## 🧩 Project Structure

| File / Folder | Description |
|----------------|-------------|
| `cnn.py` | Defines and trains the CNN model |
| `train.py` | Handles model training and saving checkpoints |
| `process_image.py` | Performs image preprocessing using OpenCV |
| `main.py` | GUI application entry point |
| `images/` | Sample handwritten digit images for training and testing |

---

## ⚙️ Tech Stack

- **Python**
- **TensorFlow** / **Keras**
- **OpenCV**
- **PyGTK 3.0**

---

## 🚀 How It Works

1. The CNN model is trained on the MNIST dataset.
2. When launched, the program loads the saved model weights.  
3. Users can provide input via upload, camera capture, or direct drawing.  
4. The preprocessed image is passed through the CNN to predict the digit.

---

## 🧠 Learning Outcomes

- Implemented deep learning with CNNs for computer vision tasks.  
- Integrated OpenCV for image preprocessing and real-time predictions.  
- Combined backend machine learning with a Python-based GUI for usability.  
- Gained experience managing model checkpoints and multi-script ML pipelines.
