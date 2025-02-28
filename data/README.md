# Dataset Overview
This dataset is drawn from the **China Family Panel Studies (CFPS) 2014** and contains information on **regional, urban/rural distinctions, parental presence, and child health conditions**. The CFPS dataset provides **nationally representative longitudinal data** on family and individual dynamics in China.

## Purpose
The dataset is designed for research in:

- **Social sciences**: Understanding how **urban vs. rural settings** impact child health.
- **Parental impact analysis**: Studying how the **presence or absence of parents** affects a child's well-being.
- **NLP-based interpretability**: Applying **Natural Language Processing (NLP) techniques** to analyze text-based factors related to parental care and child health outcomes.

## Preprocessing Steps
### **Data Cleaning**
- Removed any **missing or inconsistent values**.
- Standardized text formats (e.g., **region names, categorical values**).

### **Encoding**
- Converted categorical variables (e.g., **‘父亲是否缺失’**, **‘母亲是否缺失’**, **‘孩子是否生病’**) into **numerical values** for NLP and visualization.
- Used **Label Encoding** to transform text-based data into a structured numerical format.

### **Data Harmonization**
- Unified **different regional naming conventions** (e.g., **‘Eastern region’** vs. **‘Easternern region’**).
- Mapped **urban/rural distinctions** under a single categorization scheme.
- Ensured **consistent representation** of parental presence and child health conditions.

## Visualization & NLP-Based Interpretability
- **Dimensionality Reduction**: Applied **PCA, t-SNE, and UMAP** to visualize text embeddings.
- **BERT-based NLP Analysis**: Extracted textual relationships and encoded them for **deeper interpretability**.
- **Cluster Analysis**: Used **DBSCAN** to group similar data points and detect **trends in child health outcomes**.

## Expected Outcomes
- Identifying **patterns in parental involvement and child health** based on location.
- Establishing a connection between **urban/rural status and child well-being**.
- Leveraging **NLP for explainable results** and better interpretability.

## Future Improvements
- **Expanding dataset size** for better generalizability.
- **Incorporating additional socio-economic indicators**.
- **Applying advanced NLP models** for improved text representation.

For more details, refer to the **dataset files** and associated **analysis scripts**.
