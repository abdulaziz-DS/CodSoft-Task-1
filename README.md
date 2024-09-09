# CodSoft Task 1: Iris Flower Classification 

This project focuses on building a predictive model that classifies Iris flowers into their respective species (Setosa, Versicolor, and Virginica) based on various features such as sepal and petal length and width. The primary goal is to analyze the Iris flower dataset and develop a machine learning model that accurately predicts the species of the flower based on these measurements.

As a Data Science Intern at CodSoft, I was tasked with performing data cleaning, exploratory data analysis (EDA), and building a classification model using the Iris dataset.

Here's a detailed overview of the steps I took and the insights I gained:

## Data Cleaning

### Step 1: Importing the Dataset
I began by importing the Iris flower dataset from the provided CSV file.

### Step 2: Data Inspection
I inspected the dataset to understand its structure, identified the features (sepal and petal measurements), and ensured no missing values were present.

### Step 3: Data Preprocessing
I encoded the target labels (species) into numerical values, making the dataset ready for machine learning algorithms.

## Exploratory Data Analysis (EDA)

### Step 1: Descriptive Statistics
I calculated descriptive statistics to understand the central tendencies and variability in the sepal and petal measurements.

### Step 2: Visualizing Relationships
I visualized the relationships between features using scatter plots and pair plots to explore how each feature correlates with the species of Iris flowers.

### Step 3: Identifying Patterns
Through data visualization, I identified clear separations between the species based on sepal and petal lengths and widths, which confirmed the viability of using these features for classification.

## Model Development

### Step 1: Splitting the Data
I split the dataset into training and testing sets, ensuring an 80-20 split for model training and evaluation.

### Step 2: Training the Model
I trained a Logistic Regression model to classify the Iris flowers based on the sepal and petal measurements.

### Step 3: Model Evaluation
After making predictions on the test set, I evaluated the model's performance using accuracy metrics and generated a classification report to assess precision, recall, and F1-score for each species.

## Visualization

### Step 1: PCA for Dimensionality Reduction
To visualize the dataset in 2D, I applied Principal Component Analysis (PCA), reducing the features to two principal components while retaining most of the variance.

### Step 2: Plotting the Classification Results
I plotted the training data and test predictions, using different colors for each species, which showed a clear distinction between Setosa, Versicolor, and Virginica.

## Insights Gained

- **Feature Correlation**: Petal length and petal width are strong predictors for distinguishing between Versicolor and Virginica.
- **Separation of Species**: The Setosa species is clearly separated from the other two species based on both sepal and petal measurements.
- **Model Accuracy**: The Logistic Regression model achieved an accuracy of over 95% in classifying the Iris flower species, indicating strong predictive power using these features.

## Conclusion
This project allowed me to develop a robust classification model for the Iris dataset, perform comprehensive EDA, and visualize the relationships between features and species. The insights gained from this process helped in understanding the natural separations between the Iris species and the effectiveness of machine learning models in classifying them.

---

#CodSoft #Internship #DataScience #IrisFlowerClassification
