
# 🛒 MNIST Digit Classification using CNN



## 📌 Overview
This project demonstrates the application of Convolutional Neural Networks (CNNs) for handwritten digit recognition using the MNIST dataset. It covers the complete deep learning workflow: preprocessing, model building, training, evaluation, and prediction on custom images.
## ❓ Problem Statement
Handwritten digit recognition is a classic computer vision problem. The challenge is to correctly classify digits (0–9) from grayscale images. This project aims to build a CNN model that achieves high accuracy and can generalize to unseen handwritten digits.
## 📂 Dataset
Source: MNIST dataset (available in TensorFlow/Keras)

Size: 70,000 images (60,000 training, 10,000 testing)

Image Specs: Grayscale, 28×28 pixels

Classes: Digits from 0 to 9
## 🛠️ Tools & Technologies
Programming Language: Python 

Libraries: TensorFlow/Keras, NumPy, Matplotlib

Environment: Google Colab
## 🔄 Workflow
Data Loading & Visualization – Load MNIST dataset and visualize sample digits.

Preprocessing – Normalize pixel values (0–255 → 0–1), reshape to (28,28,1).

Model Building – CNN architecture with Conv2D, MaxPooling, Dense layers.

Compilation – Optimizer: Adam, Loss: Sparse Categorical Crossentropy, Metric: Accuracy.

Training – Train for 5 epochs with validation on test data.

Evaluation – Achieved ~99% accuracy on test set.

Custom Predictions – Load external digit images, preprocess, and predict using trained model.
## 🔑 Key Insights
Normalization significantly improves training stability.

CNNs automatically learn spatial features (edges, curves) crucial for digit recognition.

The model generalizes well to unseen handwritten digits, even from external sources.

Achieved Test Accuracy: 99.01%, proving CNNs are highly effective for image classification tasks.
## 📊 Results
Training Accuracy: ~99%

Validation Accuracy: ~99%

Successfully predicted custom images (imgof3.png, imgof6.png) with correct labels.
## Conclusion
This project highlights the effectiveness of CNNs in solving computer vision problems like handwritten digit recognition. With minimal preprocessing and a simple architecture, the model achieves near‑state‑of‑the‑art accuracy. It also demonstrates how to extend the model to real‑world handwritten inputs.
## Contributing
Contributions to this project are welcome! If you have ideas for improvements or additional insights, please open an issue or a pull request. Your contributions will be greatly appreciated.
## 📬 Contact Information
LinkedIn: kaushik-raghani

Email: kaushikraghani23@gmail.com