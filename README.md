# Crustacean Age Prediction
Crustacean Age Prediction is a project focused on predicting the age of crustaceans using machine learning techniques. By analyzing various features such as length, diameter, and weight, this project aims to provide accurate estimations of the age of crustaceans. The prediction models are trained and evaluated using algorithms like Random Forest and XGBoost.

The project involves several stages including data exploration, data cleaning, feature engineering, modeling, and testing. Through data exploration, insights into the dataset and the relationships between different features are gained. Data cleaning ensures the removal of outliers and handles missing values. Feature engineering involves creating new features based on domain knowledge to enhance the model's performance.

The models are trained on the prepared dataset and evaluated using metrics such as mean squared error, mean absolute error, and R-squared score. The best-performing model is then used for prediction on the testing dataset.

Additionally, this project provides visualizations and analytics to further analyze the results and understand the importance of different features in predicting the age of crustaceans.

The ultimate goal of Crustacean Age Prediction is to contribute to a better understanding of crustacean growth patterns and provide a useful tool for researchers and marine biologists in estimating the age of these fascinating marine creatures.

## Prerequisites
To run this project, you need the following dependencies:

1. Python 3.10.^
`pandas`
`numpy`
`matplotlib`
`seaborn`
`scikit-learn`
`xgboost`

2. You can install the required packages using pip:
```shell
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```
3. Dataset : `data.csv` and `testdata.csv`

4. Bat file (xgboost) : `best_xgb.dat`

## Installation

1. Clone the repository or download the project files.
```shell
git clone https://github.com/viv3k19/crustacean_Age_Prediction-using-Python-ML.git
```
2. Make sure you have the required dependencies installed.
3. Open the crustaceanAgePrediction.ipynb notebook in Jupyter or any other compatible environment.

## Usage
* Open the crustaceanAgePrediction.ipynb notebook.
* Run the notebook cells sequentially to execute the code.
* Follow the comments and code explanations to understand the process.
* The notebook performs data exploration, data cleaning, feature engineering, modeling, and testing.
* The final model's performance metrics are displayed at the end.

## Data Exploration
The notebook starts with data exploration to understand the dataset's structure and relationships between features. Various visualizations and statistical analyses are performed to gain insights into the data.

## Data Cleaning
After the initial exploration, data cleaning steps are implemented to handle missing values and outliers. In this case, outliers in the "Height" feature are removed, and the missing record is dropped.

## Feature Engineering
Feature engineering is an important step in building a predictive model. This notebook demonstrates the creation of new features based on domain knowledge. Features such as "Size," "Density," "Density_shucked," "Density_viscera," "Weight_no_Shell," and "Density_no_shell" are created.

## Modelling
Two models, Random Forest and XGBoost, are trained and evaluated in this notebook. Grid search is used to tune the hyperparameters of each model, and the best model is selected based on the mean squared error metric.

## Testing
The performance of the selected models is evaluated using the testing dataset. Mean squared error (MSE), root mean squared error (RMSE), mean absolute error (MAE), and R-squared score (R2) are calculated and compared for both models.

![categorialVariable](https://github.com/viv3k19/crustacean_Age_Prediction-using-Python-ML/assets/82309435/dc657122-e7eb-4099-bfd6-8117d34dcb29)

## Results
The results of the model evaluation are displayed, showing the performance metrics for both the XGBoost and Random Forest models.

![floatRepresentation](https://github.com/viv3k19/crustacean_Age_Prediction-using-Python-ML/assets/82309435/d2a2a704-fc67-4441-95a5-b18b480a2c00)

## Analytics
Additional analytics and visualizations are provided to further analyze the results. The feature importance of the best XGBoost model is plotted, and the distribution of the "Shell Weight" feature across different ages is visualized.

![ShellWeight_Size_Age](https://github.com/viv3k19/crustacean_Age_Prediction-using-Python-ML/assets/82309435/ff872b11-c475-4713-b7d1-0c00554c031e)

## Dataset
The dataset used for this project is available at repository `/dataset`. It contains information about crustaceans and their corresponding age. The dataset includes the following columns:

- Length: Length of the crustacean
- Diameter: Diameter of the crustacean
- Height: Height of the crustacean
- Whole Weight: Total weight of the crustacean
- Shucked Weight: Weight of the meat (without shell)
- Viscera Weight: Weight of the internal organs
- Shell Weight: Weight of the shell
- Sex: Sex of the crustacean
- Age: Age of the crustacean (target variable)

Please refer to the dataset for more details on the variables and their descriptions.
You can download the dataset from the provided link and use it for your own analysis or to reproduce the results mentioned in the notebook.
Note: Make sure to place the dataset file ("data.csv") in the same directory as the notebook file before running the code.

# Project Creator
* Vivek Malam - Feel free to contact me at viv3k.19@gmail.com for any questions or feedback.
