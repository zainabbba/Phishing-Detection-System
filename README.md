# 🧠 Deep Phishing Detector

A deep learning system that detects and classifies website URLs as **phishing** or **legitimate** using advanced neural network architectures.  
The project leverages **CNN**, **LSTM**, and a **hybrid CNN–LSTM** model to analyze URL structures and patterns for detecting malicious websites with high accuracy.

---

## 🎯 Objective
Phishing websites are a major cybersecurity threat that deceive users into providing sensitive data.  
This project aims to **automate phishing detection** by analyzing website URLs and classifying them using deep learning models trained on labeled datasets.

---

## 🧩 Key Features
- 🔍 Detects phishing URLs automatically using trained AI models  
- 🧠 Supports multiple architectures:
  - CNN (Convolutional Neural Network)
  - LSTM (Long Short-Term Memory)
  - Hybrid CNN–LSTM
- 📊 Evaluates model performance with accuracy, precision, recall, and F1-score  
- 🧾 Provides visualization of training metrics and confusion matrices  

---

## 🧠 Model Architectures
1. **CNN:** Extracts spatial patterns and n-gram features from URLs  
2. **LSTM:** Captures sequential dependencies across characters in URLs  
3. **Hybrid CNN–LSTM:** Combines spatial and temporal learning for optimal results  

---

## 🧰 Tech Stack
- **Language:** Python  
- **Libraries:** TensorFlow / Keras, Pandas, NumPy, Matplotlib, Scikit-learn  
- **Tools:** Jupyter Notebook, Google Colab  
- **Dataset:** Public phishing URL dataset (balanced phishing vs legitimate URLs)

---

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/zainabbba/Phishing-Detection-System.git
   cd Phishing-Detection-System
