SUV Purchase Prediction
This Jupyter Notebook contains Python code for predicting SUV purchases based on a dataset using Logistic Regression. It includes data preprocessing, model training, and evaluation steps.

Prerequisites
Before running this notebook, ensure you have the following libraries installed:

scikit-learn
pandas
seaborn
matplotlib

You can install them using pip:
pip install scikit-learn pandas seaborn matplotlib

Dataset
The dataset used for this analysis is stored in a CSV file named 'suv_data.csv'. Make sure the file is in the same directory as this notebook. The dataset should have the following columns:

Feature 1
Feature 2
...
Feature N
Target (Binary: 0 or 1)
Code Overview
Importing Required Libraries: We start by importing the necessary Python libraries - scikit-learn, pandas, seaborn, and matplotlib. We also enable inline plotting with %matplotlib inline.

Loading the Dataset: We read the dataset from the 'suv_data.csv' file into a Pandas DataFrame.

Data Preprocessing: We split the data into features (X) and the target variable (y). Then, we split the dataset into training and testing sets using the train_test_split function from scikit-learn. Standardization is performed on the feature data using StandardScaler.

Model Training: We create a logistic regression classifier using LogisticRegression from scikit-learn, fit it to the standardized training data, and then use it to make predictions on the test data.

Model Evaluation: We calculate the accuracy score of the model on the test set using accuracy_score from scikit-learn. The accuracy score is displayed as a percentage.

Running the Notebook
You can run this notebook cell by cell to execute each step. Ensure that the dataset file 'suv_data.csv' is in the same directory as this notebook. You can modify the dataset file or the code as needed to adapt it to your specific dataset and analysis requirements.

Feel free to explore and visualize the data further or modify the model and its hyperparameters for better predictions. Happy coding!
