# Data Mining #

In this repository, there is Python code that reads a dataset called CoffeeRatings. With this dataset, we perform the following tasks:

1. **Exploratory Data Analysis (EDA)**: Conduct a thorough exploration of the dataset to understand the distribution, relationships, and patterns in the data. This involves visualizing data through histograms, box plots, scatter plots, and other relevant charts.

2. **Outlier Analysis**: Identify and analyze outliers that may skew the results of subsequent analyses. Techniques such as the Interquartile Range (IQR) or Z-score are used to detect and potentially remove these anomalies from the dataset.

3. **Data Standardization**: Standardize the dataset to bring all features to a similar scale, which is crucial for algorithms that rely on distance metrics, such as Support Vector Machines (SVM). This involves transforming the data so that each feature has a mean of zero and a standard deviation of one.

4. **Application of SVM with Linear Kernel**: Implement a Support Vector Machine (SVM) with a linear kernel to classify and analyze the data. The linear kernel is effective when the data is linearly separable or nearly so.

5. **Application of SVM with Gaussian Kernel**: Apply an SVM with a Gaussian (RBF) kernel to handle non-linear relationships in the data. This kernel is particularly useful for capturing complex patterns that a linear kernel cannot.

6. **Random Forest for Coffee Color Prediction**: Use a Random Forest classifier to predict the color of coffee based on its attributes. Random Forest is an ensemble method that builds multiple decision trees and merges them to improve accuracy and control overfitting.

7. **Balanced Dataset Analysis**: Repeat the analysis, this time balancing the dataset in advance to address any class imbalance issues. Balancing the dataset helps to ensure that the model does not favor the majority class and provides a more accurate and fair prediction across all classes.
