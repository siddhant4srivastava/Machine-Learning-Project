## Project Overview
Counterfeit medicines pose a significant threat to public safety, especially in developing countries where up to 30% of medicines may be counterfeit. This project aims to predict sales figures of counterfeit medicine operations using machine learning models, enabling authorities to prioritize high net-worth illegal operations for action.

## Dataset
The dataset consists of two files:
1. `counterfeit_train.csv` - Training dataset with features and target variable `Counterfeit_Sales`.
2. `counterfeit_test.csv` - Test dataset without the target variable (used for submission).

### Key Features
- **Medicine_ID**: Unique identifier for each medicine.
- **Other Features**: Various attributes such as distribution area, availability rating, and area demographics.

### Target Variable
- **Counterfeit_Sales**: Sales figures of counterfeit medicines.

## Modeling
### Data Preprocessing
1. Missing values were handled.
2. Categorical variables were encoded using `LabelEncoder`.
3. Numerical features were standardized with `StandardScaler`.

### Model Evaluation
Validation performance was measured using Root Mean Squared Error (RMSE).

## Algorithms Used
### 1. Linear Regression
Linear Regression serves as a baseline model:
- Features were scaled using `StandardScaler`.
- Model parameters were optimized using default settings.
- Validation RMSE was used for performance evaluation.

### 2. Decision Tree Regressor
Decision Tree Regressor is a non-linear model:
- Hyperparameters such as `max_depth` and `min_samples_split` were optimized using GridSearchCV.
- Offers interpretable results by splitting features at decision nodes.

### 3. Random Forest Regressor
Random Forest Regressor, an ensemble learning method:
- Combines predictions of multiple decision trees for improved accuracy.
- Hyperparameter tuning (e.g., `n_estimators`, `max_depth`) was performed using GridSearchCV.
- Achieved the best performance among tested models.


## Contributing
Contributions, suggestions, and improvements are welcome! Feel free to fork this repository and submit a pull request.

