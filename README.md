
## Loan Status 

Dream Housing Finance company deals in all kinds of home loans. Have a presence across all urban, semi-urban, and rural areas. The customer first applies for a home loan and after that company validates the customer's eligibility for the loan.
The company automates the loan eligibility process based on customer detail provided while filling out an online application form.

- Details like Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others.
- To automate this process, they have provided a dataset to identify the customer segments that are eligible for loan amounts so that they can specifically target these customers.
- After you find the Hidden Trends and Patterns and build a Robust Model by learning all the Trends and Patterns can be used for Predicting the Loan Status of the Candidates.
- Building the Model , also checks and Evaluates the Performance of the Model Created.
The Company can Confidently use the Predictive Model built by us.
- Evaluating the Model uses different Performance Metrics such as Accuracy, Precision, Recall, and F1 Score
and Finally comes up with the Best Model to Predict the Loan Status of the Candidates.

## Installation
Python Libraries: -
- Numpy
- Pandas
- Seaborn
- Matplotlib
- Sklearn
- Imblearn

Set the Background for your Data Visualizations: -Select the “Fivethirtyeight” Background.

If you wish to select any other Background for your Charts then you can just type the command: “plt.style.available” and pick up any of the Styles for your Charts.
    Perform Descriptive Statistics for both Continuous and Categorical Variables present in the Data.
## Contributing


Import the Dataset into the Notebook using the read_csv function available in the pandas library.

Check the shape of the Dataset: -

You are getting an Output of (614, 13) for your Dataset.
This means that your Dataset consists of 614 Rows, and 13 Columns.

The Columns of the Data set: -
The Columns present in the dataset are 'Loan_ID', 'Gender', 'Married', 'Dependents', 'Education', 'Self_Employed', 'ApplicantIncome', 'CoapplicantIncome', 'LoanAmount', 'Loan_Amount_Term', 'Credit_History', 'Property_Area', 'Loan_Status'


## Documentation

 Descriptive Statistics

Count of the records present in the columns.
Average value of the records present in the column.
Standard deviation present in the column.

- Outliers are considered to be bad for Predictive Models, as These Outliers can distort or destroy the Learning Patterns of the Data, which might lead to bad performance of your Model even after Training.

- Understand the Dynamics and Statistics of the Categorical Columns Present in the Dataset.
- Univariate Data Analysis
Three types of Bivariate Data Analysis: -
- Categorical vs Numerical
- Categorical vs Categorical
- Numerical vs Numerical

Encoding the rest of Categorical Columns.
Split the Target Column from the Dataset.

Important Step: 
don't remove from the Dataset, then the Machine Learning Model will learn all the Patterns from the Target Column also.

Perform Statistical Resampling on the Dataset for Predictive Modelling.

- Resampling is the method that consists of drawing repeated samples from the original data samples.
- The method of Resampling is a non-parametric method of statistical inference.

There are many Statistical Methods you can use for Resampling the Data such as: -

- Over Sampling
- Cluster based Sampling
- Under Sampling


Oversampling and Undersampling in data analysis are techniques used to adjust the class distribution of a data set.


These terms are used both in statistical sampling, survey design methodology and in machine learning.

Oversampling and undersampling are opposite and roughly equivalent techniques
Use Oversampling in this case Instead of Undersampling to avoid data loss.


For Oversampling, we use the “Imblearn Library” which we imported earlier.
From the Imblearn Library, use the “SMOTE” Algorithm for performing Oversampling.

Logistic Regression: -

Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist.

- Import the Logistic Regression Algorithm: -

From Sklearn.linear_model package

Define a Model: -

Train your Training Data set that is x-train, and y-train using the fit function.

The Precision for Class 0, is 86% whereas the Precision for Class 1 is 77%.

Similarly, the Recall for Class 0 is 73% and Class 1 is 88%.

This means that Logistic Regression is not the Best Model for this Dataset.

- Import the Gradient Boosting Algorithm from Sklearn.ensemble package.

Check the Confusion Matrix and Classification Report to make sure that this Model works better than the latter.

Precision, and Recall. They are quite similar. You can check the Cross Validation Scores also. And you can see that the Scores are not varying too much. Meaning that the Model has been Trained well.

Cannot expect this Model to work very well, as the Number of Records in the Training Data is very less.

Gradient Boosting is a Good Model to go with.





## Insight

Data Analysis, Data Cleaning, Data Visualization, Data Processing and Finally Modelling.

The Modelling Part: -

- Modelled our Data with Logistic Regression and Gradient Boosting.
- Both of the Models worked pretty well, But Gradient Boosting did a little better as compared to the Logistic Regression Model.
- Understood that we cannot get very good results, as the Number of Records in our Training Data is very less. 
That’s why the Gradient Boosting is a Good Model, as the Cross Validation Scores also came very good.
Used Accuracy, Precision, also Evaluate the Model Performance.

Key Takeaways: -

- If we have an Imbalanced Data, we need to apply some Resampling Techniques to make it balanced.
- If we have some Skewed Features in the Dataset, we need to apply some Data Transformation techniques.
- You Must Perform Univariate and Bivariate Analysis to understand the Better.
- Try more and more Predictive Models, Compare them using various Evaluations Metrics is a good way of finding the Best Model.