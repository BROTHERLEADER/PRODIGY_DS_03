# PRODIGY_DS_03

Task-03

Building a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Used  the Bank Marketing dataset from the UCI Machine Learning Repository.






Import necessary libraries: We import all the necessary libraries for data manipulation (pandas), numerical operations (numpy), model building and evaluation (sklearn).

Load the dataset: We load the dataset from a CSV file using pandas.

Explore the dataset: We use head(), info(), and describe() methods to get an initial understanding of the data.

Data Cleaning and Preprocessing: We check for missing values and convert categorical variables to numeric values using LabelEncoder. This step is crucial as machine learning algorithms work with numerical data.

Feature Selection and Splitting Data: We separate the features (independent variables) from the target variable (dependent variable). Then, we split the dataset into training and testing sets to evaluate the performance of the model.

Build the Decision Tree Classifier: We initialize, fit, and make predictions using the DecisionTreeClassifier. We then evaluate the model's performance using accuracy and classification report metrics.
