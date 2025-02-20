# Insurance Purchase Prediction with MARS and GAM  

## Description  
This project predicts customer purchases of a variable annuity insurance product using **MARS** (Multivariate Adaptive Regression Splines) and **GAMs** (Generalized Additive Models). The solution demonstrates expertise in handling missing data, advanced regression techniques, and model evaluation for a commercial banking use case.  

**Tools Used**  
- **R**: `earth`, `mgcv`, `caret`, `pROC`, `dplyr`  
- **Visualization**: `ggplot2`, `ROCit`  
- **Workflow**: RMarkdown for reproducible reporting  

## Key Features  
- Imputed missing values using **median** for continuous variables and **new category (2)** for missing binary/categorical data.  
- Built a **MARS model** with binomial logistic regression (`glm.list(family="binomial")`).  
- Developed a **GAM** with splines for continuous variables and automated feature selection (`select = TRUE`).  
- Evaluated models using **AUC-ROC curves** and interpreted variable importance.  

## Results  
- MARS achieved **AUC-ROC of 0.85**, identifying **account age (ACCTAGE)** as a key predictor.  
- GAM revealed nonlinear relationships with **home value (HMVAL)** and **credit score (CRSCORE)** driving purchase decisions.  
- Delivered actionable insights through visualizations and business-ready documentation.
