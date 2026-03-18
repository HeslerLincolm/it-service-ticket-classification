## IT SERVICE TICKET CLASSIFICATION USING MACHINE LEARNING

Authors: Lloyd Laura, Hesler Bustos, Iván Rodriguez, and Bryam Ugaz

---
### Objective
Develop a Machine Learning model capable of classifying support tickets from a banking entity to improve the management, prioritization and response time of internal requests.

---

### Dataset
- **Rows:** 660
- **Columns:** 51
- **Type:** Categorical and numeric variables
- **Description:** The dataset contains information on internal tickets, including category, priority, times, responsible parties, and operational attributes related to the support workflow.

Due to confidentiality restrictions, the dataset is not publicly available. However, the notebook contains the full modeling pipeline and results from the original execution.

---

### Methodology
The project follows the CRISP-DM framework. Data preprocessing includes handling missing values, removing duplicates, coding categorical variables, and selecting the most relevant features. Several classification models were trained and compared, including Random Forest, XGBoost, LightGBM, and CatBoost. Model performance was assessed using accuracy, completeness, and F1 score. The best-performing model was further optimized through hyperparameter tuning.

---

### Models evaluated
- Random Forest  
- XGBoost  
- CatBoost
- LightGBM

---

### Best model
- **Final Model:** XGBoost
- **Final Accuracy:** ~0.98
- **Improvement over the base model:** ≈ 2%
- **Comment:** XGBoost showed the best balance between accuracy and stability in cross-validation, handling categorical variables and the dataset's class distribution well.

---

### Results and conclusions
- XGBoost consistently outperformed other models in cross-validation.
- Hyperparameter optimization increased the overall accuracy of the model.
- Key variables influencing ticket classification were identified.
- The model can be used to prioritize support requests within the bank, reducing response times and improving internal efficiency.

---

### Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn   

