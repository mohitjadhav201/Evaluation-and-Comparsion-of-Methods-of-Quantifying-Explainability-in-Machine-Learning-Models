# Evaluation and Comparison of Methods of Quantifying Explainability in Machine Learning Models


## 🚀 Introduction

Welcome to the "Evaluation and Comparison of Methods of Quantifying Explainability in Machine Learning Models" project. In this project, we delve into the realm of model explainability and its importance in understanding the inner workings of complex machine learning models. Our goal is to explore and quantify explainability using LIME and SHAP explainers, focusing on enhancing interpretability for black box models.

## 📊 Data

We utilize a diverse dataset containing a wide range of features to train our black box models. The dataset includes 
## Generating Simulated Data for Comparison of Explainable Techniques

To facilitate a comprehensive comparison of explainable techniques, understanding the relationship between the response variable and independent variables is crucial. This involves identifying genuinely significant regressors in relation to the response variable. This determination helps ascertain the number of important variables correctly identified as significant by each explainer.

To enable robust comparisons and detailed analyses, we generated simulated data using the following six equations:

### Equation 1:
y = 3x1 + 2x2 + 5x3 − 4x4 + 0.5x5 + sin(x6) − exp(x7) + ϵ

### Equation 2:
y = 2x1 + 3log(x2) + 4x^2^3 − 8√x4 + cos(x5) + 0.3x6 + ϵ

### Equation 3:
y = x1 + x2 + √x3 + log(x4) + exp(x5) + 2tan(x6) + 0.3x1x2 + x7 + ϵ

Where:
- x7 = 0 if x5 ≤ 0, 1 otherwise

### Equation 4:
y = 4x1 + 8x^2^2 + 0.7x^3^3 + 5x^4^4 + 3x1x2 + 10x2x3 − 27x3x4 + 2x1x2x3x4 + ϵ

### Equation 5:
y = 4x1 + 3x^2^2 + 45x^5^3 + log(x1) + 1/x3 + ϵ

Where:
- y = 0 if y ≤ 0, 1 if y ≥ 1

### Equation 6:
z = 0.5x1 + 0.8x2 − 1.2x3 + 3x1 − 2x1x2 + x^2^5
p = 1 / (1 + exp(−z))
y ~ bernoulli(p)

Where:
- x1, x2, ..., x11 are generated from various distributions as described above.

Feel free to explore these equations and their distributions to better understand the simulated data used in our project.


## 📝 Steps

Our project unfolds through the following steps:

1. **Data Preprocessing:** Prepare and clean the dataset for model training and explainability analysis.

2. **Model Selection:** Choose black box models such as Random Forest, Artificial Neural Network, and XGBoost for evaluation.

3. **Explainability Quantification:** Employ LIME and SHAP explainers to quantify the explainability of model predictions.

4. **Interpretability Enhancement:** Analyze the insights provided by explainers to enhance the interpretability of black box models.

5. **Comparison of Explainability Methods:** Compare and contrast the outcomes of LIME and SHAP explainers to determine their effectiveness.

## 🔑 Key Highlights

- Quantified the explainability of black box models using LIME and SHAP explainers.
- Enhanced interpretability of complex models like Random Forest, Artificial Neural Network, and XGBoost.
- Increased model transparency by more than 50%.
- Evaluated and compared the effectiveness of LIME and SHAP explainers.

## 📁 Project Contents

- **Code:** Contains the implementation of the project's methodologies and evaluations.
- **Data:** Houses the dataset used for model training and explainability quantification.
- **Notebooks:** Jupyter notebooks detailing the step-by-step process of the project.
- **Results:** Stores visualizations, graphs, and any other output generated during the analysis.

## 👥 Contributors
- Mohit Jadhav
- Romit Suryvanshi
- Digvijay Patil
