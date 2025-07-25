# Handwritten Digit Recognizer

A simple, high-accuracy CNN-based handwritten digit recognizer built with TensorFlow and Keras, trained on the MNIST dataset.

---

## 🔍 Features

- Convolutional Neural Network (CNN) for image recognition
- Classifies digits from 0 to 9
- Achieves approximately 98% accuracy on test data
- Designed to run in **Google Colab**

---

## 🧠 Model Architecture

1. **Conv2D** layer with ReLU activation
2. **MaxPooling** layer
3. **Flatten** layer
4. **Dense** layer with ReLU activation
5. **Output Dense** layer with Softmax activation

---

## 📊 Dataset

- Uses the **MNIST** dataset of handwritten digits
- Loaded via `tensorflow.keras.datasets`

---

## 🚀 How to Run

1. Open `Handwritten_Digit_Recognizer.ipynb` in Google Colab.
2. Run all cells to train and evaluate the model.
3. To test different digit predictions, modify the `image_index` variable as needed.

---

## 📦 Requirements

Dependencies are listed in `requirements.txt`.

---
