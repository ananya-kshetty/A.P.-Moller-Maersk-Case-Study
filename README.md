# A.P.-Moller-Maersk-Case-Study

The goal of this research is to use machine learning models to forecast the sourcing costs of different product combinations. The dataset includes details on a variety of characteristics, including product size, sourcing channel, manufacturer, area code, and type of product. The objective is to use data from July 2020 to May 2021 to anticipate the sourcing costs for June 2021.

## A little bit more about this Dataset
- The dataset comprises rows representing the sourcing of one unit of a particular product combination.
- Each unique product combination is represented by attributes in Columns A to F.
- Training data spans from July 2020 to May 2021, and June 2021 is the test set.
- Multiple rows may have the same combination in the training dataset.
- The test set (June 2021) contains only a single value for each combination.

## Methodology
1. **Exploratory Data Analysis (EDA)**: Recognise the distributions, relationships, and structure of the dataset.
2. **Data Preprocessing**: Take care of feature engineering, data cleansing, and outliers as well as poor quality data.
3. **Model Building and Evaluation**: Put different machine learning algorithms—like random forests, decision trees, and linear regression. Utilising measures such as MSE, RMSE, MAE, and R-squared score to assess their performance.
4. **Optimisation**: Use optimisation strategies, such feature engineering and outlier reduction, to improve the performance of the models.
5. **Model Selection** : Based on evaluation metrics, select the model that performs the best, and refine it further if needed.
6. **Forecasting**: Project the sourcing expenses for June 2021 using the chosen approach.

## Libraries used:
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
