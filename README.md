# Restaurant Revenue Prediction using Machine Learning

## Project Overview
This project focuses on predicting restaurant monthly revenue using Machine Learning regression algorithms. It explores the relationship between different restaurant features and monthly revenue to identify the factors that influence restaurant performance.

The project also compares multiple regression models to determine which model performs best in predicting monthly revenue.

## Dataset
The dataset contains information about restaurants, including:

- Number of Customers
- Menu Price
- Marketing Spend
- Cuisine Type
- Average Customer Spending
- Promotions
- Reviews
- Monthly Revenue (Target Variable)

## Exploratory Data Analysis (EDA)
The following analysis was performed:
- Dataset inspection and statistical summary
- Missing value and duplicate checks
- Scatter plots to study relationships between features and revenue
- Correlation heatmap
- Box plot to compare revenue across cuisine types
- Grouping cuisine types by total monthly revenue
- Outlier detection using the IQR method

## Data Preprocessing and Feature Selection
- Encoded the categorical feature `Cuisine_Type` using Label Encoding.
- Calculated correlations between numerical features and the target variable.
- Selected the top 4 features based on their correlation with Monthly Revenue.
- Split the dataset into training and testing sets using an 80:20 ratio.

## Machine Learning Models
Three regression algorithms were implemented and compared:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## Model Evaluation
The models were evaluated using:

- **Mean Squared Error (MSE):** Measures the average squared difference between actual and predicted values.
- **R² Score:** Measures how much variation in the target variable is explained by the model.

### Linear Regression Results
- MSE: 4363.79
- R² Score: 0.9289

Random Forest was identified as the best-performing model among the three models in the notebook.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Conclusion
This project demonstrates how data analysis and regression techniques can be used to predict restaurant monthly revenue. By comparing Linear Regression, Decision Tree and Random Forest, the project identifies Random Forest as the best-performing model among the three evaluated.

## Future Improvements
- Hyperparameter tuning to improve model performance.
- Experimenting with additional feature engineering techniques.
- Evaluating models using additional metrics such as MAE and RMSE.
- Testing model performance on unseen restaurant data.
