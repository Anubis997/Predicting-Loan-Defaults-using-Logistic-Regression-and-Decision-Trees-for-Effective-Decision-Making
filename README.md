# Predicting-Loan-Defaults-using-Logistic-Regression-and-Decision-Trees-for-Effective-Decision-Making
Aim: The aim of the project is to predict whether a loan will default or not, based on past customers' records and their
profile, in order to assist banks in their decision-making process.

Data Description: The dataset contains 20,000 observations with 15 variables, including the target variable "Bad_loan." 

Exploratory Data Analysis: The analysis involves exploring and visualizing the categorical variables in the dataset. 
Findings indicate that the most common purpose of taking a loan was debt consolidation, and observations were made on
variables such as "Grade," "Home_ownership," "Term," and "Bad_loan." The dataset is found to be unbalanced, with approximately
80% of applications being paid loans and a default rate of about 20%.

Heatmap for Variables: A heatmap was created to examine the correlation between variables and the target variable "bad_loan."
Results indicate that no variables have significant correlation with the target variable, and the variable "last_major_derog_none"
had a high number of null values and was dropped from the analysis.

Data Cleaning: The data cleaning process involved handling null values, removing unnecessary columns, encoding categorical variables
using one-hot encoding, imputing missing values, and normalizing numerical values. The dataset was then split into training and testing sets.

Models and Evaluation: Four models, namely Logistic Regression, K Nearest Neighbor (KNN), Gradient Boosted Decision Tree (GBDT), and Random Forests (RF), 
were implemented for predictive modeling. Performance comparisons were made using the ROC AUC metric. Logistic Regression achieved the highest AUC of 66%
and had the minimal misclassification of default loans.

Conclusion: Based on the results, Logistic Regression was selected as the best model for predicting loan defaults. The model's accuracy and focus 
on minimizing misclassifications of default loans make it suitable for assisting banks in their decision-making process.
