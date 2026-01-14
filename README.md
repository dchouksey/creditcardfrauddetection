# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using supervised machine learning on a highly imbalanced real-world dataset. The notebook covers data preprocessing, exploratory data analysis, feature scaling, model training, and evaluation using metrics suitable for imbalanced classification problems.

### Algorithms Implemented
The following models were trained and evaluated:

- **Logistic Regression** – used as a baseline linear classifier.
- **Random Forest Classifier** – ensemble-based model to capture non-linear relationships.
- **XGBoost Classifier** – gradient boosting model optimized for imbalanced data and high predictive performance.

### Model Evaluation
Models were evaluated using fraud-focused metrics including **Recall**, **F1-score**, **ROC-AUC**, and **PR-AUC**, which are more reliable than accuracy for imbalanced datasets.

- Logistic Regression provided a strong baseline but showed limitations in recall.
- Random Forest improved non-linear decision boundaries and overall performance.
- **XGBoost achieved the best overall results**, delivering the highest ROC-AUC and PR-AUC scores, making it the final selected model for fraud detection.

**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn  
**Format:** Jupyter Notebook
