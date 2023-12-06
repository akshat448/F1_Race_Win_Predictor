# Project Report: Predicting Formula 1 Race Winners using Logistic Regression

## Introduction

Formula 1 is one of the most popular and competitive motorsport events in the world. Predicting the race winner can be a challenging task due to various factors such as the driver's skills, car performance, and race conditions. In this project, we aim to develop a predictive model for Formula 1 race winners using a logistic regression algorithm. The project involves data analysis, data preprocessing, and feature engineering to create a robust model.

## Dataset

We used the Formula 1 dataset available on Kaggle. The dataset contains historical data about Formula 1 races, including details about drivers, teams, circuits, and race results. The primary target variable for our analysis is "Race Winner," and we have a variety of features that can be used for prediction.
(https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)

## Data Preprocessing

### Data Filtration

To improve the quality of the dataset and the model, we filtered the data by:
- Select relevant features (e.g., driver, team, circuit, race conditions, lap times, etc.).
- Removing irrelevant or duplicate data.

### Skewness and Outlier Treatment

We addressed skewness and outliers in the dataset by:
- Identifying skewed features.
- Detecting and handling outliers using techniques like IQR (Interquartile Range) or Z-scores to avoid their negative impact on model performance.

### Label Encoding

Categorical variables like driver names, team names, and circuit names were encoded using label encoding to convert them into numerical values for input to the model.

## Models

Different models like logistic regression, random forest classifier, and TensorFlow's neural networks have been used in this project to achieve different accuracies.

## Results

On test dataset(Both standardized and normal test data):
- Logistic regression: 99.989 (After standardization of data)
- Random forest classifier: 100
- TensorFlow: 100 (After standardization of data)

## Conclusion

In this project, we developed a predictive model to forecast Formula 1 race winners using logistic regression. We performed thorough data analysis, preprocessing, feature engineering, label encoding, and model evaluation. While logistic regression is a simple model, it provided reasonable results for this binary classification task. TensorFlow and random forest classifier provided perfect accuracies  Further improvements can be made by experimenting with more advanced machine learning algorithms and incorporating additional features.

## Future Work

The project is still not complete. Further work I wish to do such as dividing the data for cross-validation so it can be checked that the models are not being overfitted on the training set.

## References

- https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020
- https://www.kaggle.com/code/anandaramg/f1-champ-eda-classification-100-accuracy

---

