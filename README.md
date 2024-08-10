# dataScience_imdbDataset
IMDB DATASET DATA SCIENCE PROJECT

# Prerequisites

Before running the code, make sure you have the following libraries installed:

+ pandas
+ matplotlib
+ seaborn
+ scikit-learn

You can install these libraries using pip:

pip install pandas matplotlib seaborn scikit-learn


# Getting Started
1) Clone this repository or download the IMDB.CSV dataset.
2) Place the dataset in the same directory as the code file.


# Code Overview
### 1. Exploratory Data Analysis
+ Load the dataset using pandas and display its information.
+ Check the columns in the dataset.
+ Display the first few rows of the dataset.
+ Explore the number of unique values for numerical columns.
+ Visualize categorical variables using count plots and pie charts.
+ Perform numerical variable EDA by creating pair plots, box plots, violin plots, and histograms.
+ Display a correlation heatmap

### 2. Handling Null Values
+ Visualize null values using a heatmap.
+ Check for null values in the dataset.
### 3. Label Encoding and Dummy Variables
+ Encode the "status" column using LabelEncoder.
+ Create dummy variables for categorical columns and drop the original columns.
### 4. Feature Selection
+ Split the data into features (X) and the target variable (y).
### 5. Train and Test Split
+ Split the data into training and testing sets using train_test_split.
### 6. Training the Model
+ Initialize a K-Nearest Neighbors (KNN) classifier.
+ Fit the model on the training data.
### 7. Making Predictions
+ Predict job placement status on the test data.
### 8. Evaluating the Model
+ Calculate the confusion matrix and plot it.
+ Calculate accuracy, precision, recall, and F1 score.

# Running the Code
+ You can run the code by executing it in a Python environment. Make sure to adjust the file paths if needed.

 # Result
 + The analysis provided valuable insights into movie ratings, genre popularity, and trends over time, which could be leveraged for further predictive modeling and data-driven decision-making.
