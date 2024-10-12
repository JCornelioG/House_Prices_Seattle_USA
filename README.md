# Kaggle: Housing Price Analysis - Linear Regression and Clustering Techniques

## Introduction
Welcome to the repository for the Housing Price Analysis project. This repository showcases an approach to analyzing housing prices using Python, with a focus on correlation analysis, linear regression, and clustering techniques.
This project was developed as part of my exploration into predictive modeling and clustering techniques in Python. Additionally, I created a PowerPoint presentation summarizing the key findings and insights from the project, which is included in this repository. I hope it provides a comprehensive overview of the work and helps in understanding housing data better.

**Dataset Source:** [Kaggle Housing Dataset](https://www.kaggle.com/datasets/vikramamin/kc-house-dataset-home-prices)

### Data Preparation
The dataset was loaded from an Excel file and key features related to house prices were selected for further analysis. The selected columns include the number of bedrooms, bathrooms, square footage, and several other features related to house condition, location, and living space.


### Correlation Analysis
A correlation matrix was computed to understand the relationships between various features. Features like square footage of living space and grade of the house were highly correlated with house prices, while features like the number of bedrooms and bathrooms also showed moderate correlations. The matrix was visualized using a heatmap for better clarity.


### Linear Regression Model
A linear regression model was built to predict house prices based on several independent variables. The model showed that certain features, such as the grade of the house, square footage, and location (latitude and longitude), significantly impacted the price. This model provided a reasonable fit for the data, and diagnostics were performed to assess its accuracy.


### Clustering Analysis
To explore natural groupings of houses, the K-Means clustering algorithm was applied. The optimal number of clusters was determined using the elbow method, which suggested three clusters. Each cluster represents houses with similar characteristics in terms of size, condition, and location. The clusters were further analyzed by comparing the mean values of features within each cluster.


### Conclusion
The analysis revealed key factors influencing house prices, such as square footage, grade, and location. The linear regression model provided a predictive framework, while clustering highlighted different groups of houses with shared characteristics. This approach helps in understanding the housing market and could assist in making more informed pricing decisions.

## Packages Used
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn (for linear regression, clustering)





