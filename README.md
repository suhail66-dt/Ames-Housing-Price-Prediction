# Ames-Housing-Price-Prediction
Machine Learning regression project predicting house prices using the Ames Housing dataset. Includes data cleaning, exploratory data analysis, feature engineering, model comparison, Ridge Regression with hyperparameter tuning, and evaluation using R², MAE, RMSE, and cross-validation.
# Ames Housing Price Prediction using Machine Learning

---

## Dataset

Dataset: Ames Housing Dataset (Kaggle)

The dataset contains information about residential properties including:

- Overall quality
- Living area
- Garage features
- Basement features
- Year built
- Neighborhood information
- Other structural and categorical features

Target variable:

`SalePrice`

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

Performed:

- Dataset inspection
- Statistical analysis
- Missing value analysis
- Correlation analysis
- Feature relationship visualization

---

### 2. Data Preprocessing

Steps performed:

- Handled missing values based on feature meaning
- Filled numerical missing values using statistical methods
- Encoded categorical variables using One-Hot Encoding
- Removed irrelevant features

---

### 3. Target Transformation

Applied logarithmic transformation:

to reduce target skewness and improve regression performance.

---

## Machine Learning Models

Implemented and compared:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- Gradient Boosting Regressor

---

## Model Optimization

Used:

- Pipeline
- StandardScaler
- GridSearchCV

for Ridge Regression hyperparameter tuning.

---

## Model Evaluation

Evaluation metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- 5-Fold Cross Validation

---

## Results

Ridge Regression and Linear Regression achieved the best performance.

Ridge Regression:

- Test R²: ~0.915
- Cross-validation R²: ~0.860

The models showed strong predictive performance with reasonable generalization.

---

## Key Learnings

- Importance of proper missing value handling
- Effect of log transformation on skewed targets
- Comparing multiple algorithms rather than relying on one model
- Using cross-validation for reliable evaluation
- Applying regularization techniques for regression problems

---

## Future Improvements

Possible improvements:

- Advanced ensemble models
- Gradient boosting optimization
- Feature selection techniques
- Model deployment using Flask/FastAPI
