# Anemia Detection and Screening - Machine Learning Project

This repository contains a project on the application of machine learning techniques for the automated screening and detection of anemia using routine hematological data. The project was completed as a final year Bachelor of Science (Computer Science) project report for Savitribai Phule Pune University for the academic year 2024-2025 by Shalom Salve and Jerin Abraham.

---

### 🎯 Objective

The primary objective of this project is to develop a robust and accurate machine learning model that can effectively identify individuals at risk of anemia. By automating this process, the project aims to contribute to earlier detection, which could lead to improved patient outcomes and reduced healthcare costs.

---

### 📊 Dataset

The dataset used in this project is the first of its kind for various hematology patients in Iraq and was collected in 2022 from the Medial City / Hematology Center. The dataset contains 300 rows and 28 columns, providing a range of Cell Blood Count (CBC) test features.

**Key features in the dataset include:**
* **Gender**: Patient sex (0 for Female and 1 for Male)
* **WBC**: White Blood Cell count
* **HGB**: Hemoglobin
* **RBC**: Red Blood Cell count
* **MCV**: Mean Corpuscular Volume
* **MCH**: Mean Corpuscular Hemoglobin

---

### 🛠️ Methodology & Tools

The project follows a supervised learning approach, formulating the anemia detection task as a binary classification problem to categorize patients as 'Anemic' or 'Non-Anemic'.

**Key Tools & Libraries:**
* **Python**: The primary programming language for its versatility and extensive libraries.
* **Google Colab**: A cloud-based interactive environment for executing Python code.
* **Pandas & NumPy**: Used for data manipulation, cleaning, and numerical computations on the hematological data.
* **Matplotlib & Seaborn**: Employed for data visualization to explore distributions and relationships between variables, such as correlation heatmaps and pie charts.
* **Scikit-learn**: A machine learning library for data preprocessing, model selection, and evaluation.
* **XGBoost**: An optimized gradient boosting library used for its high performance and scalability.

**Models Employed:**
* Logistic Regression
* Support Vector Machines (SVM)
* Decision Tree
* K-Nearest Neighbors (KNN)
* Gaussian Naive Bayes
* Random Forests
* Ensemble Methods (Voting Classifier, AdaBoost, Gradient Boosting, XGBoost)

---

### 📈 Findings & Performance

The project demonstrated the strong potential of machine learning, especially boosting algorithms, for automated anemia detection.

The evaluation was conducted using 10-fold cross-validation with accuracy as the primary performance metric. The results showed that:
* **Gradient Boosting** achieved the highest cross-validated accuracy of approximately **99.13%**.
* **AdaBoost** and **XGBoost** followed closely with an accuracy of around **98.70%**.

These findings highlight the feasibility of leveraging machine learning models as valuable tools for the early identification of anemia, which could improve healthcare access and patient outcomes.

---

### 🔗 Project Notebook

You can view the full implementation and code in the Google Colab notebook: 

[Anemia Detection and Screening - Machine Learning Project](https://colab.research.google.com/drive/1OTUEdZylDhxiAHuwBgfkc7b9TjI4Yrsf#scrollTo=sU-WjqRmdEXp)
