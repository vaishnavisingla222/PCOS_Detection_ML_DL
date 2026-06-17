# 🩺 PCOS Detection Using Clinical Data and Ultrasound Images

## 📌 Overview

Polycystic Ovary Syndrome (PCOS) is a common endocrine disorder affecting women of reproductive age. Early diagnosis can help prevent long-term complications and improve patient outcomes.

This project investigates PCOS detection using two complementary data sources:

📊 **Clinical and Physiological Patient Data (Tabular Dataset)**

🖼️ **Ovarian Ultrasound Images (Medical Imaging Dataset)**

Machine Learning models were applied to structured clinical data, while Deep Learning models were trained on ultrasound images to evaluate their effectiveness in PCOS prediction.

---

## 📂 Datasets

### 📊 Clinical Dataset

Dataset Source:

https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos

**Dataset Summary**

* 541 patient records
* Approximately 50 clinical features
* Demographic information
* Hormonal measurements
* Metabolic indicators
* Reproductive health parameters

---

### 🖼️ Ultrasound Dataset

Dataset Source:

https://www.kaggle.com/datasets/anaghachoudhari/pcos-detection-using-ultrasound-images

**Dataset Summary**

* Ovarian ultrasound images
* Binary classification task:

  * Infected (PCOS)
  * Non-Infected (Normal)

---

## 🔄 Project Workflow

```text
Clinical Data
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Performance Evaluation

--------------------------------

Ultrasound Images
      ↓
Image Preprocessing
      ↓
Data Augmentation
      ↓
CNN / MobileNetV2
      ↓
Performance Evaluation
```

---

## 🤖 Models Implemented

### Machine Learning Models

* Logistic Regression
* Random Forest
* XGBoost
* Artificial Neural Network (ANN)

### Deep Learning Models

* Convolutional Neural Network (CNN)
* MobileNetV2 (Transfer Learning)

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Cross Validation

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* Scikit-Learn
* XGBoost
* NumPy
* Pandas
* Matplotlib
* Kaggle Notebook Environment

---

## 🚀 Future Improvements

* Hybrid model combining clinical and imaging features
* Explainable AI using Grad-CAM
* Streamlit-based deployment
* Validation on larger datasets
* Real-world clinical integration

---

## 👩‍💻 Author

**Vaishnavi Singla**

B.E. Computer Science & Engineering

Thapar Institute of Engineering & Technology

GitHub: https://github.com/vaishnavisingla222

---

⭐ If you found this project interesting, feel free to star the repository.
