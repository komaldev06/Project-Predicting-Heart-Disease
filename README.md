# Project-Predicting-Heart-Disease
Outcome of the Exploratory Data Analysis
1. Dataset Overview
Number of Features: The dataset contains [number of features] features.
Number of Observations: The dataset includes [number of observations] observations.
Features Included: The dataset features a mix of categorical and numerical data relevant to heart disease prediction.
2. Data Quality
Missing Values: No missing values were found (or details of any missing values if present). This indicates that the dataset is complete, and no imputation is required before model building.
3. Categorical Feature Analysis
Distribution of Categorical Features:

Sex: The dataset is fairly balanced between males and females.
ChestPainType: Typical Angina is the most common type of chest pain among patients.
RestingECG: A significant proportion of patients show normal results in their resting ECG.
ExerciseAngina: More patients report exercise-induced angina than those who do not.
ST_Slope: The distribution of ST segment slopes varies, with a notable number of patients having flat slopes.
These distributions help us understand the categorical variables and their impact on heart disease prediction.

4. Numerical Feature Analysis
Distributions:
Age: The age distribution shows a range of ages, with some clustering around middle age.
RestingBP: Resting blood pressure values vary widely, with a few outliers.
Cholesterol: Serum cholesterol levels also exhibit a broad range, with some extreme values.
MaxHR: Maximum heart rate achieved varies, with the majority of patients reaching high heart rates.
Oldpeak: Values of oldpeak show a variety of ST depression levels.
The histograms and boxplots reveal the spread and central tendencies of these numerical features.
5. Correlation Analysis
Correlation with Heart Disease:
Age and MaxHR show a moderate correlation with heart disease, where older age and lower maximum heart rate are associated with a higher likelihood of heart disease.
Cholesterol and Oldpeak also exhibit some correlation with heart disease, indicating that higher cholesterol levels and greater ST depression could be related to the condition.
The heatmap of correlations helps visualize relationships between numerical features and their impact on heart disease.
6. Feature Relationships
Pairwise Relationships:
The pairplot reveals that features such as age, cholesterol, and max heart rate are important for distinguishing between patients with and without heart disease.
Relationships such as the negative correlation between max heart rate and heart disease, and the positive correlation between oldpeak and heart disease, are visible.
