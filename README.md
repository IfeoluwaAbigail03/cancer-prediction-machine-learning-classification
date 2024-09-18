# coursera-supervised-machine-learning-classification
A Coursera final project demonstrating supervised machine learning techniques for classification tasks. The project involves predicting cancer diagnoses using various classification models and evaluating their performance.

This project focuses on supervised machine learning techniques for classification tasks, specifically predicting cancer diagnoses using various classification models. The dataset includes features related to cancer cells, such as measurements of radius, texture, and smoothness.

## Dataset Overview
- **Rows**: 569
- **Columns**: 32
- **Key Features**: radius_mean, texture_mean, perimeter_mean, area_mean, smoothness_mean, etc.
- **Target Variable**: diagnosis (M for malignant, B for benign)

## Key Highlights
- **Classification Models Used**: Logistic Regression, Support Vector Machine (SVM), Random Forest, and Gradient Boosting.
- **Best Performing Models**:
  - **SVM**: Achieved high accuracy and precision with a linear kernel.
  - **Random Forest**: Provided robust performance with high feature importance.

## Objectives
- **Prediction**: Predict cancer diagnoses using classification techniques.
- **Evaluation**: Compare model performance using metrics such as accuracy, precision, recall, and F1-score.

## Steps Performed
1. **Data Cleaning**: Addressed missing values and outliers.
2. **Feature Engineering**: Selected important features and scaled data.
3. **Model Training**: Applied various classification models and tuned hyperparameters.
4. **Evaluation**: Assessed model performance with confusion matrix and classification metrics.

## Tools & Libraries
- **Languages**: Python
- **Libraries**: NumPy, pandas, scikit-learn, matplotlib, seaborn

## Next Steps
- **Feature Engineering**: Explore additional features or interaction terms.
- **Model Improvement**: Experiment with advanced techniques such as ensemble methods and hyperparameter optimization.
- **Data Expansion**: Collect more diverse data to improve model generalization.

## Conclusion
SVM and Random Forest were identified as the top models for classifying cancer diagnoses, with SVM performing exceptionally well in terms of accuracy and precision.

## How to Run
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
