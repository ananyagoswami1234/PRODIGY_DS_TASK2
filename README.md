# PRODIGY_DS_TASK2
🚢 Diving Deep into the Titanic Dataset: A Comprehensive Data Analysis and Machine Learning Project! 📊

I'm excited to share my latest project, which involves a thorough analysis of the Titanic dataset. This project, completed during my internship, showcases the power of data science in uncovering insights from historical data and making predictive models. Here’s a detailed look at what I achieved:

Project Overview:
Data Cleaning:

🔄 Handling Missing Values:
Age: Filled missing values with the median age of passengers.
Embarked: Filled missing values with the most frequent port of embarkation ('S').
Cabin: Dropped the 'Cabin' column due to a large number of missing values.
Data Exploration (EDA) and Visualization:
Survival Rate by Passenger Class:
Visualized using a bar plot, showing higher survival rates in 1st class compared to lower classes.
Survival Rate by Sex:
A bar plot highlighted significantly higher survival rates for females compared to males.
Age Distribution:
Histograms and KDE plots revealed that most passengers were in the 20–30 age range.
Fare Distribution:
A histogram with KDE showed a skewed fare distribution with some outliers.
Survival Rate by Embarkation Port:
Bar plots indicated higher survival rates for passengers embarking from port 'C'.
Survival Rate by Family Size:
Bar plots depicted higher survival rates for small families.
Correlation Heatmap:
Analyzed correlations between numerical features, highlighting key relationships impacting survival.
Survival Rate by Age and Gender:
Violin plots showed higher survival rates for younger females.
Passenger Count by Embarkation Port:
Count plots provided insights into the number of passengers from each port.
Survival Rate by Age:
KDE plots demonstrated survival variations across different age groups.
Fare Distribution by Survival:
Box plots revealed fare differences between survivors and non-survivors.
Survival Rate by Passenger Class and Gender:
Bar plots showed survival patterns across different demographics.
Survival Rate by Age Group:
Bar plots categorized survival rates into age groups, offering insights into age-based survival trends.
FacetGrid for Survival Rate by Age, Passenger Class, and Gender:
Used FacetGrid to visualize survival rates across combinations of age, passenger class, and gender.
Pair Plot of Numerical Features and Survival Outcome:
Pair plots and KDE plots highlighted relationships and distribution differences between survivors and non-survivors.

Machine Learning Model Building and Evaluation:
Data Preprocessing:
Created age groups, handled missing values, encoded categorical variables, and scaled numerical features.

Model Training:
Trained multiple models (logistic regression, decision tree, random forest, SVM) and evaluated their performance.

Hyperparameter Tuning:
Used GridSearchCV to optimize model performance, identifying the best parameters for each model.

Analysis and Recommendations:
Model Performance:
Random Forest emerged as the top-performing model with the highest accuracy (~82%) and balanced performance metrics.

Recommendations:
Recommend using Random Forest for predicting survival due to its high accuracy and balanced performance.
Further refinement and ensemble techniques could enhance predictive capabilities.

Conclusion:
This project provided valuable insights into the factors influencing survival rates on the Titanic. By leveraging EDA and machine learning techniques, I uncovered patterns and relationships within the data, leading to actionable recommendations for predictive modeling. This approach not only enhances our understanding of historical events but also demonstrates the application of data science methodologies in real-world scenarios.


