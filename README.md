# House Price Prediction

## About This Project

This is one of the projects from my Pluto Academy AI & Machine Learning Internship program where we were asked to develop and train several machine learning models to make predictions on house prices according to certain property factors.

## Dataset

**House Prices: Advanced Regression Techniques** dataset from Kaggle is being used in this particular project.

**train.csv** is the main dataset and has 1,460 rows and 81 features regarding residential houses. The features present in this dataset are related to overall quality of the property, lot area, area covered by garage, year of construction, total rooms and many more.

## Project Workflow

### Data Preparation

Exploration of the data and handling of any missing values was done before proceeding towards developing and training the models. Additionally, the data was processed and prepared by selecting important features and encoding categorical features.

### Feature Analysis

Correlation analysis was carried out on selected features. In order to increase the efficiency of our model and understand which features impact the dependent variable.

### Model Training

Train Test Split of Data:

* Train: 80%
* Test: 20%

Three regression models have been developed and analyzed as follows:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor


## Model Evaluation

| Model                   | RMSE  | MAE   | R² Score |
| ----------------------- | ----- | ----- | -------- |
| Linear Regression       | 37148 | 23571 | 0.8201   |
| Decision Tree Regressor | 38532 | 23997 | 0.8064   |
| Random Forest Regressor | 29056 | 18321 | 0.8899   |

### Optimal Model

The **Random Forest Regressor** has proven to be the optimal choice as it demonstrated the smallest prediction errors (RMSE and MAE) and obtained the highest R² score.

Thus, this model can be considered the most accurate one among all models analyzed.

## Graphs and Plots

In order to provide insights into data analysis and machine learning models used, I produced the following graphs:

* Correlation heatmap
* Feature importance plot
* Residuals analysis plot
* Models comparison plot

## Technologies & Tools Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab

## Key Observations

The most fascinating observation made through this experiment was the significance of **OverallQual (Overall Quality)**.

It was found that the Overall Quality of the house had more impact on the price than other features such as some size-related features. The houses that had good overall quality ratings were priced relatively higher.

This demonstrated that the quality of construction and finishes are very significant factors when determining the value of a house.

## Conclusion

Through this project, I was able to gain practical knowledge about data pre-processing, feature engineering, model training, and model performance assessment. Comparison of different machine learning algorithms on the same dataset gave an insightful look into how models compare to one another.

## Author

**Aditya Tiwari**
MCA Student
Pluto Academy AI & Machine Learning Internship
