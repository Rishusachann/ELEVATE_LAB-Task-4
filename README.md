# ELEVATE_LAB-Task-4

 Here's a **short and clear step-by-step summary** of what we did in the Logistic Regression task:


1. **Import Libraries**
   → We imported libraries like `pandas`, `sklearn`, `matplotlib` for data handling, modeling, and plotting.

2. **Load Dataset**
   → Loaded the `data.csv` file using `pandas.read_csv()`.

3. **Split Features and Target**
   → Selected `X = [age, salary]` as features and `y = purchased` as the target (binary: 0 or 1).

4. **Train-Test Split**
   → Divided data into 80% training and 20% testing using `train_test_split()`.

5. **Standardization**
   → Scaled the features using `StandardScaler()` so they have mean = 0 and std = 1.

6. **Train Logistic Regression Model**
   → Fitted the model on training data using `LogisticRegression().fit()`.

7. **Make Predictions**
   → Predicted probabilities (`predict_proba`) and class labels (`predict`) on test data.

8. **Model Evaluation**
   → Evaluated using:

   * **Confusion Matrix**
   * **Precision**
   * **Recall**
   * **ROC-AUC Score**

9. **Plot ROC Curve**
   → Visualized performance at different thresholds using ROC curve.

10. **Tune Threshold**
    → Changed threshold from 0.5 to 0.3 to observe how it affects precision and recall.

11. **Understand Sigmoid Function**
    → Plotted the sigmoid function, which converts raw score to probability between 0 and 1.


