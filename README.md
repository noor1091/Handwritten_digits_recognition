# MNIST Digit Classifier Using CNN

This project is a deep learning model that classifies handwritten digits from the MNIST dataset using a Convolutional Neural Network (CNN). Implemented in Python using TensorFlow/Keras.

## 🧠 Model Summary

- Input shape: (28, 28, 1)
- Conv2D → ReLU → MaxPooling → Conv2D → ReLU → MaxPooling
- Flatten → Dense → Output Softmax (10 classes)

## 📈 Performance

- Trained with 5 epochs
- Achieved high validation accuracy
- Classification report and confusion matrix included

## 📦 Libraries Used

- `tensorflow`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## 🚀 How to Run

```bash
pip install -r requirements.txt
python Handwritten_digits_recognition.py
