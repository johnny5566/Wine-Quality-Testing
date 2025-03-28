# Wine-Quality-Testing
Wine Quality Analysis
Project Overview
This project analyzes the Wine Quality Dataset from the UCI Machine Learning Repository. The dataset contains physicochemical properties of red wine samples and their corresponding quality ratings. The goal of this analysis is to explore the dataset, preprocess the data, and apply transformations to improve feature distributions.

Dataset
Source: UCI Machine Learning Repository

File Used: winequality-red.csv

Number of Records: 1,599

Features: 12 (11 numerical features + 1 quality label)

Libraries Used
pandas - Data manipulation

numpy - Numerical computations

matplotlib & seaborn - Data visualization

scipy.stats - Statistical transformations

sklearn.preprocessing - Data preprocessing

Key Analysis Steps
Loading the Dataset: Importing the CSV file into a Pandas DataFrame.

Exploratory Data Analysis (EDA): Displaying dataset information, summary statistics, and visualizing distributions.

Missing Values Check: Ensuring data completeness.

Feature Skewness Analysis: Identifying skewed distributions.

Feature Transformation: Applying power transformation (Yeo-Johnson) to reduce skewness.

Visualization of Transformed Data: Comparing distributions before and after transformation.

How to Run
Install the required dependencies:

nginx
Copy
Edit
pip install pandas numpy matplotlib seaborn scipy scikit-learn
Open and execute the Wine_quality_dataset.ipynb notebook in Jupyter Notebook or Google Colab.

Results
Features with high skewness were successfully transformed, leading to a more normal distribution.

The dataset is now ready for further machine learning applications, such as classification or regression modeling.

Author
Tej Patel
