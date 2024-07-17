# Internship
# Week 1- Sales Analysis report
1. Watched playlist of Power BI and implemented
2. Worked on Power BI
3. ![image](https://github.com/user-attachments/assets/5741a249-19f8-4569-a9d1-8c64b34d485b)
4. ## Mall Customer Report
![image](https://github.com/user-attachments/assets/ccef9e24-7582-4b21-a0ff-c7354c8d1237)


# Week 2- Heart Dataset analysis

The heart data analysis conducted in this project aimed to explore and predict the presence of heart disease using a dataset containing various medical attributes. The analysis was performed in a Jupyter Notebook, which provided an interactive and flexible environment for data exploration, visualization, and modeling.

1. Data Preprocessing:
The dataset was first loaded into the Jupyter Notebook using the Pandas library. Initial steps involved handling missing values, encoding categorical variables, and normalizing numerical features to ensure the data was clean and ready for analysis. Exploratory Data Analysis (EDA) was conducted to understand the distribution of the data, identify outliers, and detect any correlations between features.

2. Exploratory Data Analysis:
EDA included generating summary statistics and visualizing the data through various plots. Histograms, box plots, and scatter plots were used to examine the distributions and relationships between features. Correlation heatmaps helped identify significant correlations between variables, providing insights into which features might be important for predicting heart disease.

Report on heart failure on Power BI
![image](https://github.com/user-attachments/assets/666f55ff-5c8a-4acc-af19-41e330d58e28)


# Week-3 Internet Service Provider and Gear Box Dataset Analysis

## Inter Service Provider 

Loading the Data: The first step involves loading the ISP dataset into a Pandas DataFrame. This dataset typically includes features such as customer demographics, service usage details, contract information, billing details, and customer satisfaction scores.

Understanding the Data: Summary statistics and data types of each column are reviewed to understand the dataset. Functions like df.describe() and df.info() help in getting an overview of the data.

Handling Missing Values: Missing values in the dataset are identified and handled appropriately. This could involve imputing missing values with statistical measures like mean or median, or dropping rows/columns with excessive missing data.

This ISP data analysis project demonstrates the application of data science techniques to understand and improve customer experiences in the telecommunications industry, showcasing the power of data-driven decision-making in enhancing service quality and customer satisfaction

## Gear Box Dataset

This project aims to analyze and model data from a gear box dataset to understand performance characteristics, identify potential faults, and predict maintenance needs. The analysis is performed using Jupyter Notebook, leveraging Python libraries such as Pandas, Matplotlib, Seaborn, and Scikit-Learn.

Loading the Data: The gear box dataset is loaded into a Pandas DataFrame. The dataset includes features such as temperature, rotational speed, torque, and vibration levels.

Understanding the Data: Summary statistics and data types of each column are reviewed to understand the dataset. Functions like df.describe() and df.info() are used to get an overview of the data, including the range, mean, and distribution of each feature.

Handling Missing Values: Missing values in the dataset are identified and handled appropriately. This could involve imputing missing values with statistical measures like the mean or median, or dropping rows/columns with excessive missing data to ensure the dataset's integrity.

### Linear Model

Data Splitting: The dataset is split into training and testing sets to evaluate the performance of the model. An 80-20 split is typically used to ensure that the model is tested on unseen data.

Model Training: A linear regression model is trained using the training set. This involves fitting the model to the selected features and the target variable.

Model Evaluation: The performance of the linear model is evaluated using metrics such as the R-squared value, mean absolute error (MAE), and root mean square error (RMSE). Cross-validation is employed to ensure the robustness of the model.

Residual Analysis: Residual plots are created to assess the fit of the model. These plots help identify any patterns in the residuals that suggest model inadequacies, such as non-linearity or heteroscedasticity.

This gear box data analysis project demonstrates the application of linear regression to industrial datasets, providing valuable insights into machinery performance and predictive maintenance strategies.

# Week- 4 Customer Segmentation analysis(Final Project)

## Data Exploration and Cleaning

Loading the Data: The customer dataset is loaded into a Pandas DataFrame. This dataset typically includes features such as age, income, spending score, gender, purchase history, and other demographic and behavioral attributes.

Understanding the Data: Summary statistics and data types of each column are reviewed to understand the dataset. Functions like df.describe() and df.info() are used to get an overview of the data, including the range, mean, and distribution of each feature.

Handling Missing Values: Missing values in the dataset are identified and handled appropriately. This could involve imputing missing values with statistical measures like the mean or median, or dropping rows/columns with excessive missing data to ensure the dataset's integrity.

## Data Visualization

Distribution Plots: Visualizations such as histograms and box plots are created to understand the distribution of each feature. These plots help in identifying outliers and understanding the spread of the data.

Correlation Matrix: A correlation matrix is generated to examine the relationships between numerical features. Heatmaps are used to visualize these correlations, highlighting which features are strongly correlated.

Pair Plots: Pair plots are created to visualize the relationships between multiple features, providing insights into potential patterns and clusters.

## Customer Segmentation

Clustering Analysis: Before applying regression models, clustering techniques like K-Means or hierarchical clustering are used to segment customers into distinct groups based on their attributes. This helps in understanding the natural groupings within the customer base.

Cluster Visualization: Clusters are visualized using scatter plots and cluster centroids are examined to understand the characteristics of each segment.

## Building the Linear Model

Data Splitting: The dataset is split into training and testing sets to evaluate the performance of the model. Typically, an 80-20 split is used.

Model Training (Linear Regression): A linear regression model is trained using the training set to predict continuous target variables such as customer spending score or income.

Model Evaluation: The performance of the linear model is evaluated using metrics such as the R-squared value, mean absolute error (MAE), and root mean square error (RMSE). Cross-validation is employed to ensure the robustness of the model.

Residual Analysis: Residual plots are created to assess the fit of the model. These plots help identify any patterns in the residuals that suggest model inadequacies, such as non-linearity or heteroscedasticity.

## Building the Logistic Model

Binary Target Definition: For logistic regression, a binary target variable is defined. For example, this could be whether a customer will churn (1) or not (0), based on their attributes.

Data Splitting: Similar to linear regression, the dataset is split into training and testing sets.

Model Training (Logistic Regression): A logistic regression model is trained using the training set to predict the binary target variable.

Model Evaluation: The performance of the logistic model is evaluated using metrics such as accuracy, precision, recall, F1-score, and the ROC-AUC curve. Cross-validation is employed to ensure the robustness of the model.

Confusion Matrix: A confusion matrix is generated to visualize the performance of the logistic model in terms of true positives, true negatives, false positives, and false negatives.

# Conclusion

The final section of the analysis presents the key findings from both the linear and logistic regression models. Significant predictors of customer behavior are highlighted, providing insights into factors that influence customer spending and retention.

The project concludes with actionable insights for marketing and customer relationship strategies, such as identifying high-value customer segments, targeting at-risk customers with retention campaigns, and recommending further research to refine the models and enhance prediction accuracy.

This customer segmentation project demonstrates the application of both linear and logistic regression to understand and predict customer behavior, providing valuable insights for data-driven decision-making in customer management.




