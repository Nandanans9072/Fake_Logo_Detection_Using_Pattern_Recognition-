# 🧠 Fake Logo Detection Using Pattern Recognition

---

## 📄 Overview
This project aims to detect **fake or manipulated brand logos** using **pattern recognition techniques** implemented through a **Convolutional Neural Network (CNN)**.  
The model is designed to classify input logos as **Real** or **Fake** by learning distinctive visual patterns that separate authentic logos from counterfeit ones.

---

## 🧩 Dataset
The dataset is **sourced from Kaggle**, containing a wide range of **real and fake** brand logos such as **Google**, **YouTube**, **Fila**, **LG**, and **Levi’s**.  

**Dataset Structure:**
/train/real     → Real brand logos  
/train/fake     → Fake or generated logos


Each image is resized and normalized before being fed into the CNN model for training and testing.

---

## 🧠 Model Architecture
A **Convolutional Neural Network (CNN)** is trained to extract and recognize spatial features from logo images.  
The network automatically learns visual differences between authentic and fake logos through deep pattern recognition.

**Key Layers:**
- `Conv2D` – for feature extraction  
- `MaxPooling2D` – for dimensionality reduction  
- `Flatten` – to convert feature maps into a vector  
- `Dense` – for classification  
- `Dropout` – to prevent overfitting  

**Activation Functions:**
- ReLU for hidden layers  
- Sigmoid or Softmax for output layer  

---

## ⚙️ Tools & Technologies
- 🐍 **Python**
- 🧩 **TensorFlow / Keras**
- 💻 **Google Colab**
- 📊 **NumPy**, **Matplotlib**, **Scikit-learn**
- 🗂 **Kaggle Dataset**

---

## 📊 Results
| Metric | Accuracy |
|:--|:--:|
| Training Accuracy | ~95% |
| Validation Accuracy | ~90% |

The model achieves strong classification accuracy, effectively distinguishing between **real** and **fake** logos based on visual features.

---



