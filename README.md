# California House Price Prediction
Predicting house prices in California using linear regression. This project includes data exploration, visualization, and feature engineering. Features are selected based on correlation analysis.

## Dataset
The California housing dataset is utilized for this project. It includes features such as median housing price, housing median age, average rooms, etc. The target variable is the median house value for California districts.

## Project steps
### 1.Data Exploration and Visualization:  
-We load California housing dataset using scikit-learn.
-We explore and visualize the dataset using libraries such as Plotly, Seaborn and Matplotlib.

### 2.Data preprocessing:

- Checked for missing data in the dataset.
- Explored the distribution of the target variable i.e., SalesPrice and applied log transformation to address skewness.

### 3.Feature selection:

- Analyzed feature importance using correlation matrices and visualized it through a heatmap.

### 4.Model training:

- Split data into train and test sets.
- Used Linear Regression model from scikit-learn for training.
 
### 5.Model evaluation:

- Evaluated the model's performance on the test set using metrics such as MSE(Mean Square Error) and RMSE(Root Mean Square Error).

## Results
This model demonstrates its ability to predict house prices in California based on selected features. 
