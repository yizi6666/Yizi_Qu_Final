# **Parental Absence and Child Development in China: A Machine Learning Perspective**

## **Authors**
- **Yizi Qu** – Research Design, Data Analysis, Machine Learning, Literature Review, Policy Analysis, Visualization  

## **Disclaimer**
Submitted for **STATS201: Machine Learning for Social Science**, instructed by **Prof. Luyao Zhang**, **Duke Kunshan University, Autumn 2025**.  

## **Acknowledgments**
Thanks to **Prof. Luyao Zhang**, classmates for feedback, and **open-source tools**. Special recognition to **ChatGPT, Bard, and Hugging Face** for AI-assisted research.  

---

## **Statement of Intellectual and Professional Growth**
This project strengthened our skills in **machine learning for social science**, covering **data preprocessing, Random Forest modeling, SMOTE for class balancing, and SHAP-based explainability**. It enhanced our ability to **analyze imbalanced social data and apply AI in policy contexts**.

---

## **Embedded Media**
[View Research Poster](./poster.pdf)  

---

## **Table of Contents**
1. [Introduction](#introduction)  
2. [Dataset Overview](#dataset-overview)  
3. [Methodology](#methodology)  
4. [Results & Discussion](#results--discussion)  
5. [Policy & Ethical Considerations](#policy--ethical-considerations)  
6. [Future Directions](#future-directions)  
7. [Navigation Instructions](#navigation-instructions)  

---

## **Introduction**
This study examines how **maternal vs. paternal absence** affects **child health and well-being** in China, using **CFPS (2010-2014) data** and **machine learning models** to identify key risk factors.

---

## **Dataset Overview**
- **Source**: CFPS 2014  
- **Key Variables**:  
  - **Dependent**: Child health, well-being scores  
  - **Independent**: Parental presence, urban/rural status, income  
- **Preprocessing**: Categorical encoding, missing data handling, SMOTE  

[See Data Dictionary](./data_dictionary.md).  

---

## **Methodology**
- **Regression Models**: Fixed-effects for causal inference  
- **Machine Learning**:  
  - **Random Forest** for child health classification  
  - **SMOTE** for class balancing  
  - **NLP (BERT, sentiment analysis)** for interpretability  

---

## **Results & Discussion**
- **Maternal absence has a stronger negative impact than paternal absence**  
- **SMOTE improves minority class recall but introduces noise**  
- **SHAP analysis identifies parental presence as the strongest predictor**  

---

## **Policy & Ethical Considerations**
- **Hukou Reform**: Ensuring **migrant children’s access to healthcare & education**  
- **AI Fairness**: Preventing bias in **social welfare decision-making**  
- **SDGs**: Aligns with **SDG 3 (Health) and SDG 10 (Reduced Inequalities)**  

---

## **Future Directions**
- **Longitudinal AI models** for multi-year predictions  
- **Advanced NLP** for policy text analysis  
- **AI & Policy**: Using predictive models for **child welfare interventions**  

---

## **Navigation Instructions**
- **Code**: `./code/` – Machine learning models, simulations  
- **Datasets**: `./data/` – CFPS raw and processed data  
- **Docs**: `./docs/` – Methodology, preprocessing  
- **Dependencies**: `requirements.txt`  

For full details, visit the **[GitHub Repository](https://github.com/YOUR_REPO_LINK)**.
