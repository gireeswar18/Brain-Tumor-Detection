# Brain Tumor Classification using Deep Learning

## 📌 Project Overview

This project uses **Deep Learning** to classify **brain MRI images into different tumor types**.

The model analyzes MRI scans and classifies them into the following categories:

- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

The model was built and trained using **TensorFlow/Keras in Jupyter Lab**.

## 🧠 Problem Type

Multi-Class Image Classification

Number of Classes: 4

Classes:

- Glioma
- Meningioma
- Pituitary
- No Tumor


## 🧠 Model Used

- MobileNet Transfer Learning
- Convolutional Neural Network (CNN)

Frameworks:

- TensorFlow
- Keras
- Python


## 📊 Results

Model Accuracy:

**~83% Validation Accuracy**

MobileNet transfer learning improved the performance compared to the basic CNN model.


## 📁 Project Structure

```
brain-tumor-classification/
│
├── brain_tumor.ipynb
├── README.md
├── requirements.txt
└── dataset/ (not included)
```

Dataset folder structure:

```
dataset/
│
├── glioma/
├── meningioma/
├── pituitary/
└── notumor/
```



## 📦 Dataset

The dataset contains MRI images of brain tumors.

Classes included:

- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

Dataset Source:

Kaggle Brain Tumor MRI Dataset

The dataset is not included in this repository because of large file size.

## ⚙️ Installation

Clone repository:


git clone https://github.com/yourusername/brain-tumor-classification.git


Install dependencies:


pip install -r requirements.txt


Run Jupyter Lab:


jupyter lab


Open notebook:


brain_tumor.ipynb


## 🔬 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Lab

## 🧪 Training Details

- Image Size: 224 × 224
- Batch Size: 32
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Epochs: 30
- Transfer Learning: MobileNet

## 📈 Future Improvements

- Increase dataset size
- Improve accuracy
- Try EfficientNet
- Build web application
- Deploy model

## 👨‍💻 Author

Gireeswar C P