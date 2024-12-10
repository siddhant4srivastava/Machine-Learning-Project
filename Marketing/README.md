## Problem Statement

The objective is to predict customer interest in caravan insurance policies based on socio-demographic and product usage data.  
- **Target Variable**: `V86` (indicates whether a customer is interested in caravan insurance).  
- **Training Data**: 5000+ customer descriptions with labeled target variables.  
- **Test Data**: 4000 customer descriptions (target variable not provided).  

---

## Dataset Overview

- **Number of Features**: 86
- **Types of Features**:
  - Socio-demographic data (derived from zip area codes)
  - Product usage data
- **Training Set Size**: 5000+ samples
- **Test Set Size**: 4000 samples

---

## Methodology

1. **Data Preprocessing**:
   - Handled missing values and outliers.
   - Scaled and normalized numerical features.
   - Encoded categorical variables using one-hot encoding.
   
2. **Exploratory Data Analysis (EDA)**:
   - Analyzed distribution of features.
   - Identified correlations between features and the target variable.
   - Performed feature selection based on importance.

3. **Model Development**:
   - Experimented with various machine learning algorithms:
     - **Decision Trees**:
       - Built interpretable tree-based models to identify key decision paths for customer interest.
     - **Random Forest**:
       - Leveraged an ensemble of decision trees to reduce overfitting and improve generalization.
     - **Logistic Regression**:
       - Established baseline performance for comparison with tree-based methods.
   - Tuned hyperparameters using grid search and cross-validation for optimal performance.
   - Selected the best-performing model based on evaluation metrics.

4. **Evaluation**:
   - Used precision, recall, F1-score, and ROC-AUC to measure model performance.
   - Ensured balanced evaluation due to potential class imbalance in the target variable.


## Results

- **Best Model**: [Specify the best-performing model, e.g., Random Forest]
- **Key Metrics**: [Include key results such as accuracy, precision, recall, etc.]

## Contributing

Contributions are welcome! Please create an issue or submit a pull request for improvements or suggestions.


