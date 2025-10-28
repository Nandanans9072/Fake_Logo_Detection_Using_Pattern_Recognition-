🧠 Fake Logo Detection Using Pattern Recognition
📄 Overview

This project detects fake or manipulated brand logos using pattern recognition techniques implemented with a Convolutional Neural Network (CNN).
The model classifies logos as Real or Fake based on learned visual patterns.


🧩 Dataset

The dataset is taken from Kaggle, containing real and fake brand logos such as Google, YouTube, Fila, LG, and Levi’s.
It includes two folders:

/train/real     → Real brand logos  
/train/fake     → Fake or generated logos


🧠 Model

A CNN is trained to extract and recognize patterns that differentiate authentic logos from fake ones.
Key layers: Conv2D, MaxPooling, Flatten, Dense, and Dropout.


⚙️ Tools Used

Python, TensorFlow (Keras)

Google Colab

NumPy, Matplotlib, Scikit-learn


📊 Results

Training Accuracy: ~95%

Validation Accuracy: ~90%
The model successfully distinguishes fake logos from real ones with high accuracy.
