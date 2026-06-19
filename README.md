# Data-science-projects
# Student Performance Analysis Using Machine Learning

## Project Title

**Student Performance Analysis and Prediction Using Machine Learning**

---

# 1. Introduction

Student academic performance is influenced by several factors such as study habits, family background, school support, internet access, and extracurricular activities. This project analyzes student data to identify these factors and build machine learning models capable of predicting student performance accurately.

---

# 2. Aim of the Project

To analyze student performance data, identify the major factors affecting academic success, and develop machine learning models that can accurately predict students' performance.

---

# 3. Objectives

* Import and explore the student dataset.
* Clean and preprocess the data.
* Handle missing values and remove duplicate records.
* Perform exploratory data analysis (EDA).
* Train multiple machine learning models.
* Compare the performance of the models.
* Identify the best-performing algorithm.

---

# 4. Tools and Technologies Used

* **Programming Language:** Python
* **Development Environment:** Jupyter Notebook (VS Code)
* **Libraries:**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Scikit-learn

---

# 5. Dataset Description

The dataset contains information about students, including:

* Age
* Gender
* School
* Parents' education
* Study time
* Number of past failures
* Internet access
* Family support
* Extra classes
* Social activities
* Final academic performance

---

# 6. Methodology

### Data Collection

The student dataset was imported from an Excel file into Python.

### Data Preprocessing

The dataset was cleaned by:

* Handling missing values.
* Filling missing categorical values with the mode.
* Removing duplicate records.
* Checking data types and dataset information.

### Exploratory Data Analysis (EDA)

EDA was carried out to:

* Understand the structure of the dataset.
* Examine distributions of variables.
* Identify relationships between different student characteristics and academic performance.

### Machine Learning Models

Three classification algorithms were trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest

---

# 7. Results

The performance of the models is summarized below:

| Model               | Accuracy   |
| ------------------- | ---------- |
| Logistic Regression | **98.32%** |
| Decision Tree       | **100%**   |
| Random Forest       | **100%**   |

Additional evaluation metrics such as Precision, Recall, F1-Score, and training time were also used to compare model performance.

---

# 8. Key Findings

* Student data can be used to predict academic performance with very high accuracy.
* Both the **Decision Tree** and **Random Forest** models achieved perfect classification accuracy on the evaluation dataset.
* Logistic Regression also performed exceptionally well with an accuracy of approximately **98.3%**.
* Proper data cleaning and preprocessing significantly improved model performance.

---

# 9. Conclusion

This project demonstrates that machine learning techniques can effectively predict student academic performance. Among the models tested, **Decision Tree** and **Random Forest** produced the best results with **100% accuracy**, making them suitable models for educational performance prediction. Such predictive systems can assist schools in identifying students who may require additional academic support.

---

# 10. Future Improvements

* Train the models using larger and more diverse datasets.
* Apply cross-validation to improve model reliability.
* Develop a web application where users can input student information and receive performance predictions.
* Explore advanced algorithms such as **XGBoost**, **Support Vector Machine (SVM)**, and **Neural Networks** for further performance comparison.
