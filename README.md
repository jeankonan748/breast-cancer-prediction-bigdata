<div align="center">

# 🧠 Breast Cancer Prediction  
### Machine Learning & Deep Learning for Medical Diagnosis  

<br>

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" width="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scikitlearn/scikitlearn-original.svg" width="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" width="50"/>
<img src="https://www.tensorflow.org/images/colab_logo_32px.png" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original.svg" width="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" width="50"/>

<br><br>

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange.svg)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-red.svg)](https://www.tensorflow.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-GradientBoosting-purple.svg)](https://xgboost.readthedocs.io/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)]()

</div>

---

## 📖 Overview

This project develops an intelligent classification system to predict whether a breast tumor is **Benign (B)** or **Malignant (M)** using Machine Learning and Deep Learning models.

The main objective is to compare classical ML approaches with Artificial Neural Networks to determine performance differences on structured medical data.

---

## 🏥 Medical Context

<div align="center">
  <img src="https://images.unsplash.com/photo-1581594693702-fbdc51b2763b?q=80&w=800" width="450"/>

</div>

Breast cancer remains one of the leading causes of cancer-related deaths worldwide.  
Early detection significantly improves survival rates.  
Artificial Intelligence can assist medical professionals in decision-making processes.

---

## 📊 Dataset Description

The dataset includes numerical features computed from digitized images of breast mass cell nuclei.

### Feature Categories:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

Each feature is provided as:
- Mean
- Standard Error
- Worst Value

### Target Variable:
- `M` → Malignant  
- `B` → Benign  

Binary Supervised Classification.

---

## 🔄 Project Pipeline

```mermaid
flowchart TD
    A[Dataset] --> B[Data Cleaning]
    B --> C[Feature Scaling]
    C --> D[ML Models]
    C --> E[Deep Learning Model]
    D --> F[Evaluation]
    E --> F
    F --> G[Model Comparison]

```

## 🤖 Models Implemented

- Machine Learning

- Logistic Regression

- Support Vector Machine

- Random Forest

## 📈 Evaluation Metrics

- Accuracy

- Precision

- Recall

- F1-Score

- ROC-AUC

- Confusion Matrix

- Stratified Cross-Validation

## 🛠 Tech Stack

- Python

- Pandas

- NumPy

- Scikit-learn

- TensorFlow / Keras

- XGBoost

- Matplotlib

- Seaborn

- Jupyter Notebook

## 🚀 Installation


or ``conda``::

    git clone https://github.com/your-username/breast-cancer-prediction.git
    cd breast-cancer-prediction
    pip install -r requirements.txt
    jupyter notebook

    
## 🎓 Research Contribution

Comparative study between ML and DL

Robust evaluation via cross-validation

Feature importance analysis

Reproducible AI pipeline

## 📄 License

MIT License

<div align="center">
👨‍💻 Developed by Jean KONAN

Master 2 – Big Data & Artificial Intelligence

</div>
