## Overview
This project involves building predictive models to determine which customers are likely to purchase a variable rate annuity product offered by a bank. The analysis is divided into three phases, each focusing on different modeling approaches and objectives:

1. **Phase 1**: Use of MARS (Multivariate Adaptive Regression Splines) and GAM (Generalized Additive Models) to explore predictive power.
2. **Phase 2**: Implementation of tree-based models, specifically Random Forest and XGBoost, to enhance predictive accuracy.
3. **Phase 3**: Model interpretation, including global and local insights, to understand the factors influencing customer decisions.

The goal is to provide actionable insights and high-performing models that align with the bank's objectives.

---

## Project Structure
1. **Data Preparation**:
   - Two datasets are provided: `insurance_t` (training) and `insurance_v` (validation).
   - Missing values are handled using median and mode imputation for continuous and categorical variables, respectively, unless alternative methods are justified.
   - The target variable `INS` indicates whether a customer purchased the product (1 = Yes, 0 = No).

2. **Modeling Phases**:
   - **Phase 1**:
     - Build MARS and GAM models.
     - Evaluate model performance using metrics like AUC and ROC curves.
     - Report variable importance for each model.
   - **Phase 2**:
     - Develop Random Forest and XGBoost models.
     - Tune hyperparameters to optimize performance.
     - Rank variable importance and evaluate using AUC and ROC curves.
   - **Phase 3**:
     - Create an additional machine learning model not used in earlier phases.
     - Provide global interpretations for key variables (e.g., account age) using techniques like PDP or ALE.
     - Offer local interpretations for specific observations using methods like LIME or SHAP.

3. **Deliverables**:
   - A comprehensive business report summarizing findings, justifications for model choices, and interpretations of results.
   - Commented code used to produce results, ensuring reproducibility.

---

## Key Objectives
- Develop robust predictive models with high accuracy and interpretability.
- Provide insights into the factors driving customer decisions to purchase the annuity product.
- Deliver actionable recommendations based on data-driven analysis.
