# System Fault Classification Using Machine Learning and Deep Learning

This project investigates the application of Machine Learning and Deep Learning techniques for system fault classification. The objective is to automatically identify and categorize faults from system data, improving reliability, maintenance efficiency, and operational stability.

---

## Project Overview

Fault detection and classification are critical tasks in modern software and industrial systems. Undetected anomalies may lead to performance degradation, service interruptions, or system failures. This project evaluates multiple classification approaches and compares their effectiveness on different fault datasets.

---

## Implemented Models

### Machine Learning Algorithms

* Random Forest
* Naive Bayes
* Support Vector Machine (SVM)

### Deep Learning Models

* Artificial Neural Network (ANN)
* Long Short-Term Memory (LSTM)

---

## Data Preprocessing Techniques

### SMOTE

Synthetic Minority Over-sampling Technique (SMOTE) is used to address class imbalance by generating synthetic samples for minority classes.

### PCA

Principal Component Analysis (PCA) is applied to reduce feature dimensionality, remove redundant information, and improve training efficiency.

---

## Datasets

The project utilizes two fault classification datasets:

* **equipment_anomaly_data** – Equipment anomaly detection dataset containing operational measurements and anomaly labels.
* **faults** – Fault classification dataset containing system fault categories for supervised learning experiments.

These datasets are stored in the `dataset/` directory.

---

## Evaluation Metrics

Model performance is evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**

These metrics provide a comprehensive assessment of classification effectiveness and fault detection capability.

---

## Technologies Used

* Python
* Scikit-learn
* TensorFlow / Keras
* Pandas
* NumPy
* Matplotlib
* Imbalanced-learn (SMOTE)

---

## Repository Structure

```text
.
├── dataset/
│   ├── equipment_anomaly_data
│   └── faults
│
├── source/
│   ├── code_1.ipynb
│   └── code_2.ipynb
│
└── README.md
```

---

## Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Class Balancing using SMOTE
4. Dimensionality Reduction using PCA
5. Model Training
6. Model Evaluation
7. Comparative Performance Analysis

---

## Results

Experimental results demonstrate the effectiveness of both traditional Machine Learning and Deep Learning approaches for fault classification. Comparative analysis highlights the strengths and limitations of each model under different dataset characteristics and class distributions.

---

## Future Work

* Hyperparameter tuning
* Ensemble learning methods
* Real-time fault detection systems
* Model deployment for industrial applications
