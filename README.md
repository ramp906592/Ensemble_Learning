📌 Ensemble Learning Techniques
📖 Introduction

Ensemble Learning is a machine learning technique where multiple models (learners) are combined to solve the same problem and improve overall performance.
Instead of relying on a single model, ensemble learning uses the power of multiple models to achieve better accuracy, stability, and robustness.

🎯 Why Ensemble Learning?
Single machine learning models may:
Overfit data
Underperform on unseen data
Be sensitive to noise
Ensemble learning helps to:
✅ Increase accuracy
✅ Reduce overfitting
✅ Improve generalization
✅ Produce more reliable predictions


🔑 Types of Ensemble Learning
1️⃣ Bagging (Bootstrap Aggregating)
Trains models on different random subsets of data
Reduces variance
Models are trained independently
📌 Example:
Random Forest
Advantages:
Handles overfitting well
Works great with high variance models

2️⃣ Boosting
Models are trained sequentially
Each new model focuses on previous model’s errors
Reduces bias
📌 Examples:
AdaBoost
Gradient Boosting
XGBoost
Advantages:
High accuracy
Works well on complex datasets

3️⃣ Stacking
Combines predictions from multiple models
Uses a meta-model to make final predictions
📌 Example:
Logistic Regression as meta-model
Advantages:
Very powerful
Uses strengths of different models
