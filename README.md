# Salary Prediction using Polynomial Regression

## Objective
The objective of this project is to predict employee salaries based on their position level using the Polynomial Regression algorithm. Since the relationship between position level and salary is non-linear, Polynomial Regression provides more accurate predictions than Linear Regression.

---

## Dataset
- **Dataset Name:** Position Salaries Dataset
- **Dataset Source:** https://www.kaggle.com/datasets/akram24/position-salaries

---

## Libraries Used
- pandas
- numpy
- matplotlib
- scikit-learn

---

## Methodology

1. Loaded the dataset using Pandas.
2. Displayed the first five records.
3. Identified the input feature (`Level`) and target variable (`Salary`).
4. Checked dataset information and summary statistics.
5. Verified that there were no missing values.
6. Split the dataset into 80% training data and 20% testing data.
7. Transformed the input feature using Polynomial Features (Degree = 3).
8. Trained the Polynomial Regression model.
9. Predicted salaries for the test dataset.
10. Evaluated the model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
11. Visualized the original data and Polynomial Regression curve.

---

## Results

- The Polynomial Regression model successfully captured the non-linear relationship between position level and salary.
- The model produced accurate salary predictions.
- The Polynomial Regression curve closely fits the original data points.
- Evaluation metrics (MAE, MSE, and R² Score) indicate good model performance.

---

## Conclusion
The Polynomial Regression model was used to predict employee salaries based on their position level. The model successfully captured the non-linear relationship   
between position level and salary, providing accurate predictions. The evaluation metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² 
Score, indicated good model performance. Linear Regression fits a straight line and works best for linear relationships, whereas Polynomial Regression fits a 
curved line and is suitable for non-linear data. For this dataset, Polynomial Regression is more effective because salary growth is not linear across different 
position levels. Its ability to model complex relationships makes it a better choice for predicting salaries, especially when the increase in salary becomes much 
steeper at higher position levels.
