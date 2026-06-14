# Dual-Modal-Clinical-Diagnostic-System-breast-cancer-detector-
# 🧬 Dual-Modal Clinical Diagnostic System  
### Breast Cancer Detection using Machine Learning & Deep Learning

---

## 📌 Overview

The Dual-Modal Clinical Diagnostic System is an AI-powered medical decision-support system designed to assist in the early detection of breast cancer using both **clinical tabular data** and **medical imaging data**.

The system integrates two complementary AI models:
- A machine learning model for structured clinical patient data
- A deep learning model for histopathology image analysis

By combining both modalities, the system demonstrates a more robust and reliable diagnostic approach compared to single-source prediction systems.

This project focuses on applying AI in healthcare for early-stage cancer detection support and decision assistance.

---

## 🧠 Key Features

- 🧾 Clinical data-based cancer prediction using structured patient attributes  
- 🖼️ Medical image classification using deep learning (histopathology scans)  
- 🔬 Hybrid diagnostic system combining both clinical + imaging insights  
- 📊 Advanced model evaluation (Accuracy, Precision, Recall, F1-score, ROC-AUC)  
- 📉 Confusion matrix and performance visualization  
- 🧪 Interactive diagnostic system for real-time predictions  
- 📁 Supports both manual input and dataset-based evaluation  

---

## 🏗️ System Architecture

The system is built using a **dual-pipeline architecture**:

### 1️⃣ Clinical Data Pipeline
- Input: Patient numerical medical attributes  
- Preprocessing: StandardScaler, Label Encoding  
- Model: **XGBoost Classifier**  
- Output: Cancer risk probability (Benign / Malignant)

### 2️⃣ Imaging Pipeline
- Input: Histopathology breast scan images  
- Preprocessing: Image resizing, normalization, augmentation  
- Model: **MobileNetV2 (Transfer Learning)**  
- Output: Image-based cancer classification

### 🔗 Hybrid System
- Combines both outputs for comprehensive diagnosis
- Provides final prediction + severity score

---

## 🧠 Models Used

### 📊 Clinical Model
- XGBoost Classifier
- Trained on structured breast cancer dataset

### 🖼️ Imaging Model
- MobileNetV2 (Transfer Learning)
- Fully connected classification head added
- Binary classification (Benign vs Malignant)

---

## 📂 Dataset Information

### Clinical Dataset:
- Breast Cancer Wisconsin Dataset (CSV format)

### Imaging Dataset:
- Breast Histopathology Images Dataset  
- Source: Kaggle (`paultimothymooney/breast-histopathology-images`)

---

## ⚙️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- TensorFlow / Keras  
- OpenCV  
- Matplotlib, Seaborn  
- Google Colab (development environment)

---

## 📊 Evaluation Metrics

The system evaluates performance using:

- Accuracy  
- Precision  
- Recall (Sensitivity)  
- Specificity  
- F1-Score  
- ROC Curve & AUC  
- Confusion Matrix  

Both clinical and imaging models are independently evaluated.

---

## 🧪 System Capabilities

### 🧾 Clinical Analysis
- Accepts patient medical attributes
- Predicts cancer risk probability
- Outputs diagnosis: Benign or Malignant

### 🖼️ Imaging Analysis
- Upload histopathology scan images
- Predicts tumor classification
- Displays annotated result with severity score

### 🔄 Interactive Mode
- CLI-based diagnostic system
- Supports:
  - Clinical-only analysis
  - Imaging-only analysis
  - Full hybrid diagnostic workflow

---

## 🧠 Key Learning Outcomes

- Multi-modal AI system design  
- Medical image classification using CNNs  
- Gradient boosting for structured medical data  
- Model evaluation and interpretability  
- Integration of ML + DL pipelines  
- End-to-end AI system simulation  

---

## ⚠️ Disclaimer

This project is for **educational and research purposes only**.  
It is not intended for real-world medical diagnosis or clinical use.

---

## 🚀 Future Improvements

- Deploy as a web application (Streamlit / Flask)  
- Improve fusion strategy (weighted ensemble model)  
- Add explainable AI (Grad-CAM for images, SHAP for clinical data)  
- Optimize model performance with hyperparameter tuning  
- Convert into real-time clinical decision support tool  

---

## 👨‍💻 Author

**Vishwa Rajarathne**  
BSc Undergraduate – Electronic & Computer Science  
University of Kelaniya  
Focus: Cybersecurity | AI/ML Systems

---

## ⭐ If you like this project

Feel free to star the repository and explore other projects.
