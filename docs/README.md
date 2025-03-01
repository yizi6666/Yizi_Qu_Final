# **Parental Absence and Child Development in China: A Machine Learning Perspective**

## **Project Overview**
This study analyzes the effects of **maternal and paternal absence** on **child health and well-being** using **CFPS (2010-2014) data**. Machine learning techniques such as **Random Forest and SMOTE** are employed to improve classification accuracy and understand key predictors.

---

## **Table of Contents**
1. [Code Execution in Google Colab](#code-execution-in-google-colab)  
2. [Dependencies](#dependencies)  
3. [Example Usage](#example-usage)  
4. [Navigation Instructions](#navigation-instructions)  

---

## **Code Execution in Google Colab**
To run this project in **Google Colab**, simply click the link below and **run all cells**:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_REPO_LINK/blob/main/notebooks/data_analysis.ipynb)

### **Steps to Run:**
1. Open the Colab link above.
2. Click **"Runtime" > "Run all"** to execute the code.
3. Follow any prompts if needed (e.g., mounting Google Drive for dataset access).

---

## **Dependencies**
All required libraries are listed in `requirements.txt`. If running in **Google Colab**, install dependencies using:

```python
!pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn pyreadstat
```

## **Example Usage**
This project provides **multiple ways to run the analysis**, including **Google Colab, command-line execution, and Jupyter Notebook**.

### **1️⃣ Running in Google Colab**
Simply open the provided **Google Colab notebook**, execute all cells, and follow on-screen instructions to process data, train the model, and visualize results.

### **2️⃣ Running from the Command Line**
Users can execute individual Python scripts for **data preprocessing, model training, and visualization**. Running the preprocessing script prepares the dataset, which is then used by the machine learning model to make predictions.

### **3️⃣ Running in Jupyter Notebook**
The Jupyter Notebook allows users to **step through the analysis interactively**, including **data exploration, feature importance analysis, and result interpretation**.

### **Expected Output**
- **Preprocessed dataset** ready for modeling.
- **Trained Random Forest model** with performance metrics.
- **Visualizations** of class distributions, model predictions, and feature importance.

For more details, check the **project documentation** or navigate to the relevant scripts in the repository.
