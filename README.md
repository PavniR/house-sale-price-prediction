##  Objective

The primary objective of this project is to build and evaluate regression models for predicting house sale prices using supervised machine learning techniques.

data preprocessing and exploratory data analysis to model training, evaluation, feature engineering, and regularization.

### Project Workflow

- Load and inspect the house sales dataset.
- Perform data cleaning and preprocessing.
- Handle missing values and correct data types.
- Conduct Exploratory Data Analysis (EDA) to understand feature relationships.
- Analyze feature correlations with house prices.
- Build and evaluate a Simple Linear Regression model.
- Build and evaluate a Multiple Linear Regression model.
- Apply Polynomial Feature Engineering to model non-linear relationships.
- Standardize features using `StandardScaler`.
- Machine Learning Pipeline.
- Apply Ridge Regression (L2 Regularization) to improve model generalization.
- Compare model performance using the **R² Score**.

---

## Dataset Information

The dataset contains residential house sales from King County, Washington, USA.

| Feature | Description | Data Type |
|---------|-------------|-----------|
| `id` | Unique house identifier | Integer |
| `date` | Date the house was sold | Date |
| `price` | Sale price of the house (Target Variable) | Float |
| `bedrooms` | Number of bedrooms | Integer |
| `bathrooms` | Number of bathrooms | Float |
| `sqft_living` | Living area (square feet) | Integer |
| `sqft_lot` | Lot size (square feet) | Integer |
| `floors` | Number of floors | Float |
| `waterfront` | Waterfront property indicator | Integer (0/1) |
| `view` | Quality of view rating | Integer |
| `condition` | House condition rating | Integer |
| `grade` | Construction and design grade | Integer |
| `sqft_above` | Square footage above ground | Integer |
| `sqft_basement` | Basement area (square feet) | Integer |
| `yr_built` | Year the house was built | Integer |
| `yr_renovated` | Year renovated (if applicable) | Integer |
| `zipcode` | ZIP code | Integer |
| `lat` | Latitude | Float |
| `long` | Longitude | Float |
| `sqft_living15` | living area in 2015-renovation | Integer |
| `sqft_lot15` | lot size in 2015-renovation | Integer |


---
practiced:

- Building regression models using Scikit-learn.
- Understanding the differences between simple, multiple, polynomial, and regularized regression.
- Applying feature scaling and polynomial transformations.
- Creating reusable preprocessing and training pipelines.
- Evaluating regression models and interpreting model performance using R² scores.
- Understanding the effects of overfitting and how Ridge Regression improves generalization.

> **Note:** This is a practice project.
```
