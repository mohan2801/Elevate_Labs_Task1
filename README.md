-->Titanic Dataset Analysis & Preprocessing
____________________________________________
This repository contains Python code for cleaning, preprocessing, and visualizing the Titanic dataset. The goal is to prepare the data for machine learning by handling missing values, encoding categories, and analyzing trends.

-->Dataset
____________
The Titanic dataset includes passenger details like age, gender, ticket class, fare, and whether they survived.

-->Tools Used:
   . Python

   . Pandas (for data manipulation)

   . NumPy (for numerical operations)

   . Seaborn & Matplotlib (for visualizations)

-->Steps Performed
_______________________
1. Data Exploration
Checked the dataset structure (rows, columns, missing values).

2. Handling Missing Data
Removed the Cabin column (too many missing values).

Filled missing Age values with the average age.

Replaced missing Embarked values with the most common port.

3. Encoding Categorical Data
Converted Sex to numbers: male = 0, female = 1.

Converted Embarked ports to numbers: C = 0, Q = 1, S = 2.

4. Normalizing Numerical Data
Scaled Age and Fare to have a mean of 0 and standard deviation of 1.

5. Removing Outliers
Detected outliers in Age and Fare using boxplots.

Removed extreme values using the IQR method.

Visualizations
Survival Count: How many passengers survived vs. did not survive.

Survival by Gender: Comparison of male and female survival rates.

Survival by Embarked Port: Survival based on boarding location.

Target & Features:
____________________
Target (Y): Survived (0 = No, 1 = Yes).

Features (X): All other preprocessed columns.

