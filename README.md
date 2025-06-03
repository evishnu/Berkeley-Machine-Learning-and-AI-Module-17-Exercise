# Bank Marketing Campaign – Classifier Comparison

This project compares four machine learning models — Logistic Regression, KNN, Decision Tree, and SVM — to predict whether a customer will subscribe to a term deposit based on campaign data from a Portuguese bank.

## Business Objective
Improve marketing efficiency by predicting customer subscription likelihood and optimizing outreach strategies.

## Models Evaluated
- Logistic Regression (balanced)
- K-Nearest Neighbors (sampled for performance)
- Decision Tree Classifier
- Support Vector Machine (SVM)

## Key Findings:
- Best performing model (based on ROC AUC): Logistic Regression
- Logistic Regression offers interpretability.
- SVM and Decision Trees show competitive accuracy.
## Actionable Insights:
- Use the selected model to target customers more likely to subscribe.
- Avoid contacting customers who match the lowest predicted probability segment.

## Recommendations:
- Implement model in a pilot campaign.
- Monitor uplift in conversion.
- Consider ensemble methods like Random Forest or XGBoost for further improvement.

## File Structure and NoteBook
Berkeley-Machine-Learning-and-AI-Module-17-Exercise/ │ ├── README.md ├── prompt_III.ipynb ├── data/ │ └── bank-additional-full.csv ├── images/ └── *.png (Class-Distribution, Correlation-Matrix, Feature-Distribution, and ROC-AOC-Curve-LogisticRegression)

