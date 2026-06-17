# 🩺 PCOS Detection Using Clinical Data and Ultrasound Images

## 📌 Overview

Polycystic Ovary Syndrome (PCOS) is one of the most common hormonal disorders affecting women of reproductive age. Early diagnosis is crucial to prevent complications such as infertility, metabolic disorders, and cardiovascular diseases.

This project explores PCOS detection using two complementary data sources:

### 🔹 Clinical Data (Tabular Dataset)

Patient physiological and clinical measurements were analyzed using Machine Learning and Artificial Neural Networks.

### 🔹 Ultrasound Images

Ovarian ultrasound images were analyzed using Convolutional Neural Networks (CNNs) and Transfer Learning techniques.

The objective is to compare traditional Machine Learning approaches with Deep Learning models and investigate the effectiveness of multimodal AI in healthcare diagnostics.

---

## 🗂 Project Workflow

```text
Clinical Dataset
       │
       ▼
 Data Cleaning
       │
       ▼
 Exploratory Data Analysis
       │
       ▼
 Feature Engineering
       │
       ▼
 ML Models + ANN
       │
       ▼
 Performance Evaluation

──────────────────────────

Ultrasound Images
       │
       ▼
 Image Preprocessing
       │
       ▼
 CNN Model
       │
       ▼
 MobileNetV2
       │
       ▼
 Performance Evaluation
```

---

## 📊 Dataset Information

### Clinical Dataset

Dataset Source:

https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos


* 541 patient records
* 50 clinical features
* Binary Classification:

  * PCOS Present (1)
  * PCOS Absent (0)

---

### Ultrasound Dataset

Dataset Source:

https://www.kaggle.com/datasets/anaghachoudhari/pcos-detection-using-ultrasound-images


The image dataset contains ovarian ultrasound scans categorized as:

* Infected (PCOS)
* Not Infected (Non-PCOS)

Images were resized and normalized before training CNN-based models.

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

✅ Missing Value Detection

✅ Outlier Handling

✅ Feature Correlation Analysis

✅ Class Distribution Analysis

✅ Feature Importance Visualization

✅ Heatmaps & Statistical Insights

---

## 🤖 Models Implemented &  📈 Results Summary

### Clinical Dataset

| Model               | Accuracy  | F1 Score  | ROC-AUC   |
| ------------------- | --------- | --------- | --------- |
| Logistic Regression | 0.890     | 0.838     | 0.951     |
| Random Forest       | 0.917     | 0.862     | 0.954     |
| Tuned Random Forest | 0.927     | 0.882     | **0.958** |
| XGBoost             | **0.936** | **0.896** | 0.948     |
| ANN                 | 0.890     | 0.829     | 0.920     |

### Best Tabular Model

🏆 **XGBoost**

```text
Accuracy : 93.6%
F1 Score : 89.6%
```

### Ultrasound Image Dataset

| Model       | Accuracy   |
| ----------- | ---------- |
| CNN         | 100.0%     |
| MobileNetV2 | **100.0%** |

### Best Image Model

🏆 **MobileNetV2**

```text
Test Accuracy : 100.0%
```

### Observations

* Both CNN and MobileNetV2 achieved excellent classification performance on the ultrasound dataset.
* Transfer learning using MobileNetV2 enabled faster convergence and efficient feature extraction.
* Further validation on external datasets is recommended to assess model generalization.

---

## 🛠 Technologies Used

### Languages

* Python

### Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* TensorFlow
* Keras
* XGBoost
* OpenCV
* Pillow

---

## 💡 Key Learnings

* Healthcare datasets require extensive preprocessing.
* Feature selection significantly impacts performance.
* Ensemble models outperform simple linear models.
* Transfer Learning can effectively extract medical image features.
* Combining tabular and imaging data offers promising potential for AI-assisted diagnosis.

---

## Future Improvements

* Hybrid multimodal architecture combining tabular and ultrasound image features.
* Explainable AI using SHAP for model interpretability.
* K-Fold cross-validation for ultrasound image classification models.
* External dataset validation to assess model generalization.
* Streamlit deployment for real-time PCOS prediction.

---

## 👩‍💻 Author

**Vaishnavi Singla**

---

⭐ If you found this project interesting, consider giving it a star!
