# Machine Learning Based Obstetric Health Prediction and Care System

## Abstract

This project presents an AI-powered integrated maternal healthcare platform designed to predict pregnancy risks and classify fetal ultrasound images using Machine Learning and Deep Learning techniques. The system combines maternal clinical parameter analysis using Support Vector Machines (SVM) and fetal image classification using DenseNet169. The application is built using Python, Streamlit, and Google Colab for accessible and interactive deployment.

---

## 1. Introduction

Maternal healthcare requires continuous monitoring of physiological parameters and fetal development. Traditional systems rely heavily on manual interpretation, which may introduce variability and delayed diagnosis. This project proposes an integrated AI-driven solution that combines prediction, visualization, monitoring, and conversational assistance in a single platform.

---

## 2. Proposed System

The system integrates:

- Maternal Health Risk Prediction (SVM)
- Fetal Ultrasound Classification (DenseNet169 + SVM)
- Interactive Data Visualization
- AI Chatbot Guidance Module
- User-friendly Streamlit Interface

---

## 3. System Architecture

<p align="center">
  <img src="images/architecture.png" width="750"/>
</p>

---

## 4. Application Screenshots

### 4.1 Introduction Page

<p align="center">
  <img src="images/Intropage.png" width="750"/>
</p>

---

### 4.2 Home Page

<p align="center">
  <img src="images/homepage.png" width="750"/>
</p>

---

### 4.3 Data Visualization

<p align="center">
  <img src="images/dataviz.png" width="750"/>
</p>

---

### 4.4 Pregnancy Risk Prediction

<p align="center">
  <img src="images/Pregnancyrisk.png" width="750"/>
</p>

---

### 4.5 Fetal Health Monitor

<p align="center">
  <img src="images/fetalmonitor.png" width="750"/>
</p>

---

### 4.6 AI Chatbot Support

<p align="center">
  <img src="images/chatbot.png" width="750"/>
</p>

---

## 5. Methodology

### Data Processing
- Handling missing values
- Feature normalization
- SMOTE for class balancing
- Image resizing and noise reduction

### Model Development

**Maternal Risk Prediction**
- Algorithm: Support Vector Machine (SVM)
- Output: Low / Moderate / High Risk

**Fetal Classification**
- Feature Extractor: DenseNet169
- Optimizer: Adam
- Loss Function: Cross-Entropy
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score

---

## 6. Technologies Used

- Python 3.9+
- Google Colab
- Streamlit
- Scikit-learn
- PyTorch
- Pandas
- NumPy
- Matplotlib
- Plotly

