# 🏥 Healthcare Industry Projects

## 🔬 Diabetes Prediction Using Classification Models

### 📌 Overview
Diabetes is one of the most prevalent diseases worldwide, with cases increasing annually. While its exact cause remains unknown, research suggests a combination of genetic and environmental factors play a major role. Early detection can help prevent severe health complications, making it crucial to develop predictive models.

### 🎯 Objective
This project aims to build a classification model that predicts the risk of diabetes in patients using medical attributes.

Key research questions:
- What factors contribute the most to diabetes risk?
- How can machine learning be used to predict diabetes effectively?
- Which classification model provides the best accuracy for diabetes prediction?

### 🛠️ Methodology
- **Algorithms Used:** AdaBoost, Random Forest, Gradient Boosting Machine (GBM)
- **Key Features:** Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Pedigree, Age
- **Performance Metrics:** Model tuning for best accuracy and interpretability

📂 [Project Notebook](https://github.com/MichelleT-Portfolio/Healthcare_Industry/blob/main/DiabetesRisk_Prediction.ipynb)

### 🔎 Key Findings
- **Glucose concentration** is the most important predictor, followed by **Age** and **BMI**.
- The optimized decision tree uses only three key variables to separate patients into risk categories.
- Business rules derived from the decision tree:
  - Women with glucose ≤ 127 and age ≤ 28 have a lower risk of diabetes.
  - Women with glucose > 100 and age > 28 have a higher risk.
  - Women with glucose > 127 and BMI ≤ 28 have a lower risk.

### 🔮 Conclusion
- Identifying diabetes risk early can help control the disease and prevent complications.
- The model can be used by healthcare providers to predict risk factors and take early precautions.
- Older and overweight women are at a higher risk and should monitor glucose levels closely.

---

## 🧬 Genomic Data Clustering – Discovering DNA Sequences

### 📌 Overview
DNA sequencing is fundamental in biological sciences, encoding all information needed for cellular function. One of the biggest scientific challenges is understanding how genomic sequences are organized.

### 🎯 Objective
To identify useful genes versus noise in a genomic sequence using unsupervised learning techniques.

### 🛠️ Methodology
- **Algorithms Used:** Principal Component Analysis (PCA), K-Means Clustering
- **Dataset:** Fragment of the genomic sequence of *Caulobacter Crescentus*
- **Task:** Validate the discovery of three-letter codons, which form amino acids and proteins

📂 [Project Notebook](https://github.com/MichelleT-Portfolio/Healthcare_Industry/blob/main/Genomic_Clustering__PCA_and_K_Means.ipynb)

### 🔎 Key Findings
- DNA sequences are well-organized despite appearing random.
- Unsupervised learning techniques help uncover the hidden structure of genetic codes.
- The three-letter codon structure was verified using clustering and dimensionality reduction techniques.

### 🔮 Conclusion
This project provides further evidence supporting the three-letter codon structure of DNA. The methodology can be extended to analyze genomic sequences for various biological organisms.

---

## 🏥 Brain Tumor Classification Using Deep Learning

### 📌 Overview
Medical imaging is crucial for diagnosing brain tumors. This project focuses on developing an image classification model to differentiate between Pituitary Tumor and No Tumor MRI scans.

### 🎯 Objective
- Develop a deep learning model to classify brain MRI images.
- Improve model accuracy using **transfer learning**.

### 🛠️ Methodology
- **Algorithms Used:** Convolutional Neural Networks (CNN), Transfer Learning (VGG16), Data Augmentation
- **Dataset:** Kaggle Brain Tumor MRI dataset (subset with Pituitary Tumor and No Tumor)
- **Training Data:** 395 MRI scans of No Tumor, 435 MRI scans of Pituitary Tumor
📂 [Project Notebook](https://github.com/MichelleT-Portfolio/Healthcare_Industry/blob/main/BrainTumor_Classifier_ComputerVision.ipynb)

### 🔎 Key Findings
- Custom CNN models struggle with achieving high accuracy.
- Transfer learning significantly improves model performance.
- The model converges faster using VGG16 in just **5 epochs** compared to **10 epochs** in the custom CNN.

### 🔮 Conclusion
- Transfer learning allows for faster convergence and better classification performance.
- The model can be further optimized for medical applications.
- This approach can assist radiologists in detecting brain tumors more efficiently.

---

## 🏗️ Installation & Usage
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook (optional but recommended)
- Required Python Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`, `tensorflow`, `keras`

---
## 📬 Contact
If you have any questions or feedback, feel free to reach out via [LinkedIn](http://www.linkedin.com/in/michelle-tzeng-336a441a6) or email at michelletzengcontact@gmail.com.

---
## 🤝 Contributions & Improvements
Open to feedback and suggestions! If you'd like to enhance the project, feel free to contribute. 🚀

