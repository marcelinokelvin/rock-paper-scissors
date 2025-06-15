# Rock Paper Scissors Image Classifier ✊✋✌️
This project is a deep learning-based image classifier that identifies hand gestures for **Rock**, **Paper**, or **Scissors**. Built using TensorFlow and Keras, this model was developed to fulfill the final project requirement for the *Dicoding "Belajar Machine Learning untuk Pemula"* course.

## 📌 Project Overview
The model is trained on image data of hand gestures and performs classification using a Convolutional Neural Network (CNN). The dataset was provided by Dicoding via GitHub.

## 🧰 Tools & Libraries
* Python 3
* TensorFlow / Keras
* NumPy
* Matplotlib
* OpenCV (for image handling)
* Google Colab (training platform)

## 🗂️ Dataset
* Downloaded from:
  ```
  https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip
  ```
* Preprocessed and split using `ImageDataGenerator` with a 60/40 training/validation split.

## 🧠 Model Architecture
* 4 Convolutional layers (with MaxPooling)
* 1 Flatten + Dense layer
* Output layer with 3 neurons (softmax for classification)
* Uses `categorical_crossentropy` loss and `Adam` optimizer

## 🎯 Features
* Classifies images as either **Rock**, **Paper**, or **Scissors**
* Trained with image augmentation for better generalization
* Early stopping when validation accuracy > 97%
* Can perform prediction on uploaded image files

## 🧪 How to Use
1. Train the model using the Jupyter Notebook (`rock_paper_scissors.ipynb`)
2. Upload an image file via the Colab interface
3. The model will classify the image and display the result

## 📁 File List
* `rock_paper_scissors.ipynb` – Full training and prediction notebook
* `rockpaperscissors.zip` – Dataset archive (downloaded in notebook)
