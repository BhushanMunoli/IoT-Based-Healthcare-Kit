# 🏥 IoT-Based Healthcare Kit for Cardiac Diagnosis
> **Published in IEEE Xplore** | Developed at PES University

[![IEEE Xplore](https://img.shields.io/badge/Publication-IEEE%20Xplore-maroon.svg)](https://ieeexplore.ieee.org/)
[![Tech Stack](https://img.shields.io/badge/Stack-IoT%20%7C%20ML%20%7C%20Embedded-blue.svg)](#)
[![Accuracy](https://img.shields.io/badge/Best%20Accuracy-78.67%25-orange.svg)](#)

## 🔍 Project Overview
Cardiovascular diseases and Cardiac Arrhythmia are the most familiar reasons for death throughout the world over the last few decades across the world. However, it is difficult to examine patients in all cases accurately, and
consultation with a patient for 24 hours by a doctor is not possible as it needs extra patience, expertise, and time. Thus, with ECG sensors, Arduino, and Raspberry Pi, we implemented machine learning models based on K-Nearest Neighbour, Logistic Regression, Support Vector Machine, and Random Forest for heart disease prediction based on the parameters and attributes related to cardiovascular disease. The datasets in this research are available publicly on the UCI website. The early diagnosis of cardiovascular diseases assists in making decisions on lifestyle changes in patients prone to high risk of heart diseases and minimizing the complications. The result of this research canbe a milestone in medicine.

## 🏗 Results
The main operation is carried out with an ECG sensor to measure electrical activity and record the electricalsignals in the form of graphs. The main discussion of the above project is to Classify the two types of heart disease (CVD and Cardiac Arrhythmia). The secondary operation is to detect the risk of disease by creating an application interface. The output value is obtained in binary format in which 0 indicates no disease and 1 indicates the person has a chance ofhaving CVD. Among multiple machine learning algorithms, the Support Vector Classifier shows the highest accuracy of 78.67%. For cardiac Arrhythmia, the output includes 16 classes based on the value of attributes. Initially, PCA is applied for feature extraction, followed by SVM with various kernel functions. The results of the random forest classifier show that the SVM with Linear Kernel and regularization parameter of 0.01 is 74% accurate amongst the other kernels used for predicting CardiacArrhythmia (Tables I and II).

| Rank | Model | Accuracy |
| :--- | :--- | :--- |
| **01** | **Linear Support Vector Machine (SVM)** | **78.67%** |
| 02 | Random Forest Classifier | 77.33% |
| 03 | Logistic Regression | 76.00% |
| 04 | K-Nearest Neighbors (KNN) | 74.67% |
| 05 | Decision Tree | 70.67% |

### 2. Cardiac Arrhythmia Prediction
*Multi-class Classification: 16 distinct cardiac categories.*

| Algorithm | Configuration | Accuracy |
| :--- | :--- | :--- |
| **Linear SVM** | **Regularization (C=0.01)** | **74.00%** |
| Random Forest | Combined with SVM | 73.00% |
| Polynomial SVM | Degree Kernel | 68.00% |
| RBF SVM | Radial Basis Function | 66.00% |

## 📈 Key Conclusions
* **Optimal Algorithm:** The **Support Vector Machine (SVM)** consistently outperformed other models, proving most effective at handling the high-dimensional attributes of ECG data.
* **Rural Impact:** The framework is designed for high-efficiency monitoring in rural areas where access to specialized cardiologists is limited.
* **Internet of Things:** Integration with IoT improves administrative efficiency and operational patient care.

## 🔮 Future Enhancements
* Implementation of **Deep Learning (CNN/LSTM)** for automated ECG pattern recognition.
* Data augmentation to expand the training set for rarer arrhythmia classes.
* Development of a mobile-first dashboard for real-time patient-doctor alerts.

---

### 🎓 Academic Citation
Authorized licensed use limited to: **Texas A&M University**. 
*Originally presented at the 2022 IEEE 4th Eurasia Conference on Biomedical Engineering, Healthcare and Sustainability (ECBIOS).*
