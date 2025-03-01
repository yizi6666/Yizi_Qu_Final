# **Parental Absence and Child Development in China: A Machine Learning Perspective**

## **Authors**
- **Yizi Qu** – Research Design, Data Analysis, Machine Learning, Literature Review, Policy Analysis, Visualization  

## **Disclaimer**
Submitted for **STATS201: Machine Learning for Social Science**, instructed by **Prof. Luyao Zhang**, **Duke Kunshan University, Autumn 2025**.  

## **Acknowledgments**
Thanks to **Prof. Luyao Zhang**, classmates for feedback, and **open-source tools**. Special recognition to **ChatGPT, Bard, and Hugging Face** for AI-assisted research.  

---

## **Statement of Intellectual and Professional Growth**
This project enhanced our skills in **machine learning for social science**, specifically in **Random Forest modeling, class imbalance handling with SMOTE, and SHAP-based interpretability**. It deepened our understanding of **social science applications of AI** and policy-driven data analysis.

---

## **Embedded Media** 
[View Research Poster](./Research Poster.pdf)

---

## **Table of Contents**
1. [Background and Motivation](#background-and-motivation)  
2. [Research Questions](#research-questions)  
3. [Application Scenarios](#application-scenarios)  
4. [Methodologies](#methodologies)  
5. [Results: Random Forest & SMOTE Analysis](#results-random-forest--smote-analysis)  
6. [Intellectual Merits](#intellectual-merits)  
7. [Practical Impacts](#practical-impacts)  
8. [Navigation Instructions](#navigation-instructions)  

---

## **Background and Motivation**
This study explores how **parental absence due to labor migration** affects **child well-being** in China. With increasing internal migration, children left behind face **health, emotional, and educational challenges**. Understanding these effects using **machine learning** can inform **targeted policy interventions**.

---

## **Research Questions**
- **How does parental absence affect child health and well-being?**  
- **Is maternal absence more significant than paternal absence?**  
- **Can machine learning improve prediction accuracy in child welfare studies?**  

---

## **Application Scenarios**
- **Public Policy**: Identifying at-risk children for targeted welfare programs.  
- **Healthcare & Education**: Predicting health risks based on parental presence.  
- **NGOs & CSR**: Supporting child development initiatives using AI-driven insights.  

---

## **Methodologies**
- **Random Forest**: Classifying child health outcomes.  
- **SMOTE**: Balancing class distribution to improve minority class predictions.  
- **SHAP Analysis**: Identifying key predictors of child well-being.  
- **NLP**: Extracting interpretability insights from social narratives.  

---

## **Results: Random Forest & SMOTE Analysis**
- **Maternal absence has a stronger negative impact than paternal absence**.  
- **SMOTE improves classification for underrepresented groups but introduces noise**.  
- **SHAP analysis reveals parental presence as the dominant predictor of child health**.  

---

## **Intellectual Merits**
This study advances **machine learning applications in social science**, demonstrating how **AI-driven classification** improves child welfare research. It bridges the gap between **traditional econometric approaches** and **data-driven policy insights**, inspiring future studies in **explainable AI and longitudinal child development models**.

---

## **Practical Impacts**
- **Policy**: Supports evidence-based decisions for migrant child welfare.  
- **Industry**: AI-powered child health prediction tools for NGOs and government agencies.  
- **Ethics & AI Governance**: Ensures **fair, transparent, and privacy-conscious** machine learning applications in social policy.  

---

## **Navigation Instructions**

## **Navigation Instructions**
This repository contains all necessary resources for replicating our analysis on **Parental Absence and Child Development Using CFPS Data**.

### **📂 Code for Simulations and Visualizations** (`./code/`)
All machine learning scripts, data preprocessing, and visualization codes are stored in this directory.
- [`random_forest.py`](./code/prediction) – Implements **Random Forest classification, Handles **data imbalance using SMOTE**.

### **📂 Datasets and Preprocessing Steps** (`./data/`)
This directory contains **raw and processed datasets** used in the analysis.
- [`CFPS_2014_part.xlsx`](./data/CFPS_2014_part.xlsx) – **Original CFPS dataset**.

### **📂 Visualization** (`./docs/`)
This folder contains **detailed documentation** about the dataset and methodology.
- [`data_dictionary.md`](./visualization) – **Detailed variable definitions and descriptions**.

pip install -r requirements.txt

For full details, visit the **[GitHub Repository](https://github.com/yizi6666/Yizi_Qu_Final/tree/main)**.
