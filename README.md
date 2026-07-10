# CodeAlpha-Handwritten-Character-Recognition-
# ✍️ Handwritten Character Recognition using Convolutional Neural Networks (CNN)

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Project Overview

This project implements a **Handwritten Character Recognition System** using a **Convolutional Neural Network (CNN)**. The model is trained on the **MNIST handwritten digit dataset** to accurately recognize handwritten digits (0–9).

The project demonstrates the complete deep learning workflow, including:

- Data loading
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Data augmentation
- CNN model development
- Model training
- Performance evaluation
- Visualization
- Model saving
- Prediction on new images
- Deployment readiness

The trained model achieves approximately **98–99% test accuracy**, making it a strong baseline for handwritten image classification.

---

# 📂 Dataset

Dataset Used:

**MNIST Handwritten Digits Dataset**

- Total Images: **70,000**
- Training Images: **60,000**
- Testing Images: **10,000**
- Image Size: **28 × 28**
- Color Mode: Grayscale
- Classes: **10 (Digits 0–9)**

Dataset Source:

https://keras.io/api/datasets/mnist/

---

# 🎯 Objectives

The main objectives of this project are:

- Build a deep learning model for handwritten digit recognition.
- Learn image preprocessing techniques.
- Apply Convolutional Neural Networks (CNNs).
- Evaluate model performance using multiple metrics.
- Visualize learning curves and predictions.
- Save and reuse the trained model.
- Prepare the model for deployment.

---

# 🧠 Model Architecture

The CNN architecture consists of:

- Conv2D Layer (32 filters)
- MaxPooling Layer
- Batch Normalization
- Conv2D Layer (64 filters)
- MaxPooling Layer
- Batch Normalization
- Flatten Layer
- Dense Layer (128 neurons)
- Dropout Layer (0.5)
- Output Layer (Softmax)

---

# 🔄 Workflow

```
Load Dataset
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Preprocessing
      │
      ▼
Data Augmentation
      │
      ▼
CNN Model Building
      │
      ▼
Compile Model
      │
      ▼
Train Model
      │
      ▼
Evaluate Performance
      │
      ▼
Visualizations
      │
      ▼
Save Model
      │
      ▼
Predict New Images
```

---

# 📊 Exploratory Data Analysis (EDA)

The project includes:

- Dataset inspection
- Dataset shape
- Class distribution
- Sample handwritten images
- Image dimensions
- Pixel value normalization

---

# ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Image normalization
- Reshaping images for CNN
- One-hot encoding labels
- Data augmentation

---

# 🛠️ Data Augmentation

The following transformations are applied:

- Rotation
- Zoom
- Width Shift
- Height Shift

This helps improve model generalization.

---

# 🚀 Model Training

Training Parameters:

| Parameter | Value |
|-----------|-------|
| Optimizer | Adam |
| Loss Function | Categorical Crossentropy |
| Epochs | 15 |
| Batch Size | 32 |
| Validation Split | 20% |

---

# 📈 Performance Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

---

# 📊 Visualizations

The notebook generates:

- ✅ Class Distribution
- ✅ Sample Handwritten Images
- ✅ Training Accuracy Curve
- ✅ Validation Accuracy Curve
- ✅ Training Loss Curve
- ✅ Validation Loss Curve
- ✅ Confusion Matrix Heatmaps
- ✅ Prediction Probability Chart

---

# 📁 Project Structure

```
Handwritten-Character-Recognition/
│
├── dataset/
│   ├── MNIST/
│   └── EMNIST/
│
├── notebooks/
│   └── handwritten_character_recognition.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── model.py
│   ├── train.py
│   ├── evaluate.py
│   ├── predict.py
│   └── utils.py
│
├── saved_model/
│   └── handwritten_character_recognition.keras
│
├── results/
│   ├── sample_images.png
│   ├── class_distribution.png
│   ├── accuracy_plot.png
│   ├── loss_plot.png
│   ├── confusion_matrix.png
│   └── prediction_probability.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 💻 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Handwritten-Character-Recognition.git
```

Move into the project

```bash
cd Handwritten-Character-Recognition
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

Launch the notebook

```bash
jupyter notebook
```

or

```bash
python train.py
```

---

# 🔮 Prediction on New Images

Load a custom handwritten image and predict the digit.

Example:

```
Input Image
https://docs.chainer.org/en/stable/_images/mnist_output.png
<img width="1490" height="1480" alt="digit" src="https://github.com/user-attachments/assets/08e2086f-aae1-4744-abea-35df49d2b2fd" />


Prediction

Digit = 7
```

---

# 📊 Sample Results

| Metric | Value |
|---------|--------|
| Training Accuracy | ~99% |
| Validation Accuracy | ~99% |
| Test Accuracy | 98–99% |

---

# 📌 Future Improvements

- EMNIST Letter Recognition
- Alphabet Classification
- Handwritten Word Recognition
- CRNN Models
- Attention Mechanism
- Transfer Learning
- Hyperparameter Optimization
- Streamlit Deployment
- Flask API
- Docker Containerization

---

# 🌐 Deployment

The trained model can be deployed using:

- Streamlit
- Flask
- FastAPI
- Hugging Face Spaces

Users can upload handwritten images and receive real-time predictions.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Mir Murtaza**

Electrical Engineer | Machine Learning Engineer | Deep Learning Enthusiast

