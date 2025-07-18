# Credit-Card-fraud-detection

This project demonstrates the use of Random Forest Classifier to detect fraudulent credit card transactions using a real-world dataset. It includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and visualization.

📁 Dataset
The dataset used is the Credit Card Fraud Detection Dataset from Kaggle. It contains transactions made by European cardholders in September 2013.
Total Transactions: 284,807
Fraudulent Transactions: 492 (0.172%)
Features: 30 (V1 to V28 are PCA components, plus Time, Amount)
Target: Class (0 = Valid, 1 = Fraud)

Technologies Used:
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn (sklearn)

Exploratory Data Analysis:
Basic statistics and data insights
Class imbalance analysis
Fraud vs. valid transaction comparison (based on Amount)
Correlation matrix using a heatmap.


 Model: Random Forest Classifier
✅ Steps:
Load and preprocess data
Visualize data correlations and distribution
Split data into training (80%) and testing (20%) sets
Train a Random Forest model
Predict on the test set
Evaluate using metrics


Evaluation Metrics:
Accuracy
Precision
Recall
F1-Score
Matthews Correlation Coefficient
Confusion Matrix
🔍 Example Output:
The model used is Random Forest classifier
Accuracy: 0.999
Precision: 0.90
Recall: 0.84
F1-Score: 0.87
Matthews correlation coefficient: 0.87


Confusion Matrix:
|                   | Predicted Normal  | Predicted Fraud   |
| ----------------- | ----------------- | ----------------- |
| **Actual Normal** | ✅ True Negatives  | ❌ False Positives |
| **Actual Fraud**  | ❌ False Negatives | ✅ True Positives  |



