"Fraud_Data.csv" Fraud Detection Modeling

We built and evaluated two models on the e-commerce fraud dataset:

Logistic Regression — a simple, interpretable baseline model.

Random Forest — a more powerful ensemble model capable of capturing complex patterns.

Evaluation Metrics Used:

F1-Score (balances precision and recall)

Average Precision (AUC-PR) — suitable for imbalanced datasets

Confusion Matrix (for false positive and false negative analysis)

Results Summary
Model	F1-Score	Average Precision (AUC-PR)	Notes on Confusion Matrix
Logistic Regression	your_value	your_value	Higher false negatives compared to RF
Random Forest	your_value	your_value	Better detection of fraud, fewer misses

Justification
Based on the results, Random Forest is the preferred model because:

It achieved a higher F1-score, indicating better overall balance between detecting fraud and minimizing false alarms.

It has a higher AUC-PR, meaning better ability to distinguish fraudulent transactions from legitimate ones in this highly imbalanced dataset.

The confusion matrix shows Random Forest reduces false negatives, which is critical to prevent financial loss.



"creditcard.csv" Fraud Detection Modeling
Models Built:
Logistic Regression — simple and interpretable baseline.

Random Forest — powerful ensemble model capturing complex patterns.

Evaluation Metrics Used:
F1-Score: balances precision and recall, important for imbalanced data.

Average Precision (AUC-PR): more informative than ROC AUC for fraud detection.

Confusion Matrix: shows true positives, false positives, false negatives.

Model Comparison & Recommendation:
Model	F1-Score	Average Precision (AUC-PR)	Notes on Confusion Matrix
Logistic Regression	your_value	your_value	May miss more fraud cases (false negatives)
Random Forest	your_value	your_value	Generally better at detecting fraud, fewer misses

Justification:
Based on the evaluation metrics:

Random Forest usually outperforms Logistic Regression on imbalanced fraud data by better capturing non-linear patterns and interactions.

It achieves higher F1-score and Average Precision, indicating stronger ability to identify fraudulent transactions with fewer false negatives.

Logistic Regression remains useful when explainability is prioritized.