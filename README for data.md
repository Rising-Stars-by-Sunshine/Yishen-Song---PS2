# README - Dataset Information

## 1. Overview
This dataset is sourced from the **UCI Adult Income dataset**, which is commonly used for classification tasks and social science research. The dataset contains demographic and employment-related attributes used to predict whether an individual earns more than $50K per year.

## 2. Source and Purpose
- **Source:** The dataset originates from the 1994 U.S. Census Bureau database, available via the UCI Machine Learning Repository.
- **Purpose:** It is used for **income classification**, social mobility analysis, and machine learning experiments in fairness, bias detection, and causal inference.

## 3. Dataset Files
- `adult.data` - The main training dataset with labeled income values.
- `adult.test` - A separate test dataset.
- `adult.names` - Metadata file explaining the attributes.

## 4. Preprocessing and Harmonization Steps
To prepare the dataset for analysis:
1. **Missing Value Handling:** Entries marked as `?` were removed.
2. **Standardization:** Spaces before categorical values were trimmed.
3. **Feature Engineering:**
   - The `income` variable was converted to binary (`>50K` as 1, `<=50K` as 0).
   - The `education-num` variable was used as a continuous feature to model years of education.
4. **Data Splitting:** The dataset was divided into training and testing subsets to ensure fair model evaluation.

## 5. Usage
This dataset can be used for:
- **Supervised Learning:** Training classification models (Random Forest, Neural Networks, etc.).
- **Causal Inference:** Applying Regression Discontinuity (RD) designs to study the impact of education on income.
- **NLP Analysis:** Extracting insights from text attributes such as occupation and relationship descriptions.

## 6. License & Attribution
- Data provided by the **UCI Machine Learning Repository**.
- No copyright restrictions, but attribution is appreciated.

---

### Contributors
- **[Yishen Song]** - Data preprocessing, harmonization, and documentation.


