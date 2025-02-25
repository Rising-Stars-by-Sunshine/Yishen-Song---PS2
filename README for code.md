# README - Code Documentation

## 1. Overview
This repository contains code for analyzing the **UCI Adult Income dataset** using machine learning and causal inference techniques. The goal is to explore income prediction, fairness in AI, and the impact of education levels on income.

## 2. Files Included
- `data_preprocessing.py`: Loads and cleans the dataset.
- `nlp_analysis.py`: Implements text-based analysis on categorical attributes.
- `income_prediction.py`: Trains and evaluates supervised models.
- `rd_analysis.py`: Performs Regression Discontinuity (RD) design for causal inference.
- `visualization.py`: Generates plots and insights from the dataset.
- `requirements.txt`: Lists required libraries.

## 3. Prerequisites
### Required Libraries
- Python 3.9+
- pandas, numpy, seaborn, matplotlib
- scikit-learn, statsmodels
- transformers (for NLP models)

### Installation
Run the following command to install dependencies:
```bash
pip install -r requirements.txt
```

## 4. Usage Instructions
### 1. Load and Preprocess Data
```bash
python data_preprocessing.py
```
### 2. Run NLP Analysis
```bash
python nlp_analysis.py
```
### 3. Train and Evaluate Predictive Models
```bash
python income_prediction.py
```
### 4. Perform Causal Inference Analysis
```bash
python rd_analysis.py
```
### 5. Generate Visualizations
```bash
python visualization.py
```

## 5. Expected Outputs
- **Preprocessing:** Cleaned dataset with labeled features.
- **NLP Analysis:** Topic modeling and sentiment scores.
- **Model Training:** Accuracy, precision, and recall metrics.
- **Causal Inference:** RD plots and treatment effect estimates.

## 6. Contributors
- **[Yishen Song]** - Lead developer, ML modeling.


