# Linear_Regression-Arfa_ML_Project
Machine Learning Project Using Simple Linear Regression

This project implements a Simple Linear Regression model using Python and Scikit-learn.
The purpose of this project is to train a machine learning model that predicts a student's marks based on their number of hours studied.

## Dataset

The dataset contains 8 observations:

| Hours Studied | Marks Obtained |
|---------------|----------------|
| 1 | 35 |
| 2 | 40 |
| 3 | 50 |
| 4 | 55 |
| 5 | 65 |
| 6 | 70 |
| 7 | 78 |
| 8 | 85 |

### Input Feature

- Hours Studied

### Target Variable

- Marks Obtained

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## Machine Learning Model

The project uses:

**Simple Linear Regression**

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

The model was trained using python
model.fit(X_train, y_train)

Model Results
The trained model learned this linear relationship:
Marks = 6.14 × Hours Studied + 26.80

Model Parameters
Slope: 6.14
Intercept: 26.80
R² Score: 0.992

The R² score indicates that the model explains a large proportion of the variation in marks for this small test dataset.

Prediction
The trained model was used to predict marks for the testing data.

ActualMarks:
[40 65]
Predicted Marks:
[39.1 63.7]

Conclusion
This project demonstrates the basic machine learning workflow for Simple Linear Regression, including data preparation, model training, prediction, evaluation, visualization, and saving the trained model.
