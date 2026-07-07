# Uterine Corpus Endometrial Carcinoma Data Analysis

This project focuses on performing exploratory data analysis (EDA), statistical analysis, and outlier detection on the Uterine Corpus Endometrial Carcinoma dataset using Python. The main objective of this analysis is to understand the structure and characteristics of the dataset, clean the clinical data, calculate important statistical parameters, identify abnormal observations, and visualize patterns within the data.

The dataset contains clinical and genomic information related to uterine corpus endometrial carcinoma patients. In this analysis, the Mutation Count feature was mainly studied to understand its distribution and variation among patients. The Diagnosis Age feature was also used to visualize the relationship between patient age and mutation count.

The project begins with loading the CSV dataset using the Pandas library. Data cleaning was performed by converting the Mutation Count column into numerical format and handling invalid values by converting them into missing values. Duplicate records were also checked to maintain data quality. After cleaning, the dataset was inspected using functions such as columns(), info(), describe(), head(), tail(), and shape() to understand the available features, data types, statistical summary, and overall structure of the dataset.

Statistical analysis was performed on the Mutation Count variable using NumPy. The mean, median, variance, standard deviation, maximum value, and minimum value were calculated to understand the central tendency and spread of mutation values. These statistical measures provide insights into the genetic variation present in the dataset.

Outlier detection was performed using two different approaches: the Interquartile Range (IQR) method and the Z-score method. The IQR method identifies extreme values based on the difference between the first and third quartiles, while the Z-score method detects values that are more than three standard deviations away from the mean. These techniques help identify unusual mutation counts that may influence further analysis.

Data visualization was performed using Matplotlib. Box plots were created to compare mutation count values before and after outlier removal. A histogram was generated to observe the distribution and frequency of mutation counts. A relationship plot between Mutation Count and Diagnosis Age was also created to explore possible patterns between genetic mutations and patient age.

This project demonstrates the basic workflow of biomedical data analysis, including data loading, cleaning, inspection, statistical evaluation, outlier detection, and visualization. The analysis can be further extended by applying machine learning techniques such as feature engineering, feature scaling, classification models, and predictive analysis for cancer-related outcomes.

Technologies Used: Python, Pandas, NumPy, and Matplotlib.

Author: Eyman Shafiq  
Biomedical Engineering Student interested in Machine Learning and Biomedical Data Science.
