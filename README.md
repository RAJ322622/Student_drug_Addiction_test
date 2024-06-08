**Models Used**

Logistic Regression
Decision Tree
Random Forest
Bagging Classifier
XGBoost
Metrics Evaluated:

F1 Score
Recall Score
Evaluation:

Each model was trained and evaluated on the dataset, with performance measured in terms of F1 and recall scores.
The F1 score is a balance between precision and recall, providing a single metric that accounts for both false positives and false negatives.
Recall focuses on the ability of the model to correctly identify all positive instances (i.e., students who are addicted).
Key Observations:
Logistic Regression:

As a baseline model, Logistic Regression performed adequately, offering a balance of simplicity and interpretability.
It is useful for understanding the relationships between features and the target variable but may not capture complex patterns.
Decision Tree:

Decision Tree provided a clear and interpretable model, highlighting the most important features.
However, it may suffer from overfitting, especially with noisy or small datasets.
Random Forest:

Random Forest showed strong performance, benefiting from ensembling multiple decision trees to improve robustness and accuracy.
It effectively handled the imbalance in the dataset, providing higher recall and F1 scores.
Bagging Classifier:

Similar to Random Forest, Bagging Classifier also improved stability and accuracy by aggregating multiple models.
It demonstrated good performance in terms of both F1 and recall scores.
XGBoost:

XGBoost, known for its efficiency and performance, provided the best results among the evaluated models.
It achieved the highest F1 and recall scores, making it highly effective for predicting student drug addiction.
Conclusion:
Best Performing Model:

XGBoost emerged as the most effective model for predicting student drug addiction, achieving the highest F1 and recall scores. This indicates its superior ability to identify students who are addicted while minimizing false positives and negatives.
Overall Performance:

Ensemble methods like Random Forest and Bagging Classifier also performed well, indicating that these approaches are suitable for handling imbalanced datasets and providing robust predictions.
Interpretability vs. Performance:

While models like Logistic Regression and Decision Tree offer greater interpretability, they may not perform as well as ensemble methods or XGBoost, especially in complex or imbalanced scenarios.
Recommendations:
Further Validation:

It is recommended to perform cross-validation and possibly explore additional tuning of hyperparameters to further validate and optimize the models.
Feature Importance:

Analyzing feature importance from models like Random Forest and XGBoost can provide valuable insights into the factors contributing to student drug addiction, aiding in targeted interventions.
Combining Models:

Consider combining the strengths of different models through stacking or blending to leverage the advantages of multiple approaches.

By understanding these findings, stakeholders can make informed decisions about deploying predictive models to identify and address student drug addiction effectively.

![download](https://github.com/RAJ322622/Student_drug_Addiction_test/assets/146355426/a3bc97f7-628e-43c4-853d-847a4c458dca)
