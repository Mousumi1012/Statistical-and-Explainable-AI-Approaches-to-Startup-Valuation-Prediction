# Startup Valuation Prediction

This project predicts startup valuations using regression modeling with a focus on statistical rigor and model interpretability.

## Key Steps
- **Data Preprocessing**: Handled missing values using **KNN imputation** and removed outliers.  
- **Heteroscedasticity Handling**: Tested **Weighted Least Squares (WLS)** and data segmentation; a **log-transform of the target** provided the best fit.  
- **Modeling**: Trained and evaluated **regularized linear regression models (Ridge/Lasso)**, interpreting coefficients and **confidence intervals** to assess feature impact.  
- **Explainability**: Applied **LIME** and **SHAP** to interpret predictions and identify key drivers of valuation.  

## Highlights
- Improved model assumptions and performance through transformations and regularization.  
- Combined statistical inference (confidence intervals) with modern explainability techniques.  

---
