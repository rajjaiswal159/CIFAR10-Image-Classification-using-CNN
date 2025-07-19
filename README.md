# 🧠 CIFAR-10 Image Classification using CNN

This project demonstrates how to build and train a **Convolutional Neural Network (CNN)** from scratch using **TensorFlow/Keras** to classify **RGB images** from the **CIFAR-10** dataset into 10 object categories.

---

## 📊 Dataset: CIFAR-10
- **Size**: 60,000 images (32x32 RGB)
- **Classes**:
  - Airplane ✈️
  - Automobile 🚗
  - Bird 🐦
  - Cat 🐱
  - Deer 🦌
  - Dog 🐶
  - Frog 🐸
  - Horse 🐎
  - Ship 🚢
  - Truck 🚛

---

## 🚀 Project Workflow

1. **Data Loading** using `tensorflow.keras.datasets.cifar10`
2. **Data Preprocessing**: Normalization & typecasting
3. **Model Building**: CNN using `Sequential` API
4. **Training**: Using `model.fit()` with validation
5. **Evaluation**: Accuracy, loss, and performance visualization

---

## 🧠 Model Summary
- **Conv2D**
- **MaxPooling2D**
- **Dropout**
- **Flatten**
- **Dense**

Trained using the Adam optimizer and categorical cross-entropy loss.

---

## 🛠️ Tech Stack
- Python 🐍
- TensorFlow / Keras
- Matplotlib

---

## 📌 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/rajjaiswal159/CIFAR10-Image-Classification-using-CNN.git
cd CIFAR10-Image-Classification-using-CNN
```
2. Install dependencies
```
pip install tensorflow matplotlib
```
3. Open the notebook
Run CIFAR10-image-Classification.ipynb in Jupyter Notebook or Google Colab.

🤝 Connect with Me
If you like this project, feel free to ⭐ the repo and connect with me on LinkedIn
