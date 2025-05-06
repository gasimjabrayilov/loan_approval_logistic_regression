# loan_approval_logistic_regression
1. Create environment - python3 -m venv venv
2. Activate envirenment - source myenv/bin/activate
3. Downlaod needed libraries - pip install -r requirements.txt

4. You are ready to run codes





| Metric                  | Logistic Regression | Decision Tree | Random Forest |
| ----------------------- | ------------------- | ------------- | ------------- |
| **Accuracy**            | 0.85                | 0.90          | **0.93**      |
| **Precision (class 1)** | 0.73                | 0.76          | **0.89**      |
| **Recall (class 1)**    | 0.50                | 0.78          | **0.78**      |
| **F1-score (class 1)**  | 0.59                | 0.77          | **0.83**      |
| **Macro avg F1**        | 0.75                | 0.85          | **0.89**      |


Random Forest is the top performer overall: high precision, recall, and F1-score, making it the best choice for this binary classification problem.

Decision Tree performs well too but slightly less accurate.

Logistic Regression struggles especially with recall for class 1 (loan approved), indicating many false negatives.