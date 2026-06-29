# 🧠 Brain Tumor MRI Classification using CNN

## 📌 Project Overview

This project uses a Convolutional Neural Network (CNN) to classify Brain MRI images into four categories:

- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

The objective is to assist in automated brain tumor detection using Deep Learning and Computer Vision techniques.

---

## 📂 Dataset

Dataset: Brain Tumor MRI Dataset

- Total Images: 7200
- Training Images: 5600
- Testing Images: 1600
- Classes:
  - Glioma
  - Meningioma
  - Pituitary
  - No Tumor

Source:
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- CNN (Convolutional Neural Network)
- NumPy
- Matplotlib
- Scikit-learn

---

## 📁 Project Structure

```
Brain-Tumor-CNN/
│
├── dataset/
│   ├── Training/
│   └── Testing/
│
├── Brain_Tumor_CNN.ipynb
├── brain_tumor_cnn_model.keras
├── README.md
└── requirements.txt
```

---

## ⚙️ Model Architecture

The CNN consists of:

- Conv2D (16 Filters)
- MaxPooling2D
- Conv2D (32 Filters)
- MaxPooling2D
- Conv2D (64 Filters)
- MaxPooling2D
- Flatten Layer
- Dense Layer (64 Units)
- Dropout (0.5)
- Output Layer (4 Classes, Softmax)

---

## 📊 Training Details

- Image Size: 128 × 128
- Batch Size: 32
- Epochs: 5
- Optimizer: Adam
- Loss Function: Categorical Crossentropy

---

## 📈 Results

Training Accuracy:
- 82.32%

Test Accuracy:
- 77%

Classification Report Generated:
- Precision
- Recall
- F1-Score

Confusion Matrix Generated

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Brain-Tumor-CNN.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Open Notebook

```bash
jupyter notebook
```

or

```bash
Brain_Tumor_CNN.ipynb
```

Run all cells.

---

## 📷 Sample Prediction

The trained model predicts whether the MRI belongs to:

- Glioma
- Meningioma
- Pituitary
- No Tumor

---

## 🎯 Future Improvements

- Transfer Learning using MobileNetV2
- ResNet50
- EfficientNet
- Streamlit Web Application
- Model Deployment on Hugging Face Spaces
- Docker Deployment

---

## 👨‍💻 Author

Malothu Naveen

B.Tech – Computer Science and Engineering (Cyber Security)

Interested in:
- Artificial Intelligence
- Machine Learning
- Deep Learning
- Computer Vision

GitHub:
https://github.com/Naveen-ram01

LinkedIn:
(Add your LinkedIn profile)

---

## ⭐ If you found this project useful, please give it a Star.
