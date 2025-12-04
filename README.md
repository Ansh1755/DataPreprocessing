# DataPreprocessing
Data preprocessing is the process of cleaning, transforming, and organizing raw data so that machine learning models can understand it better.  Better the data → Better the model performance


# Why is Data Preprocessing Important?
Handles missing values
Fixes incorrect or inconsistent data
Improves model accuracy
Converts text data into numerical form
Removes noise and outliers
Helps models learn patterns more easily

# Data Preprocessing Workflow Summary
1. Import libraries  
2. Load dataset  
3. Handle missing values  
4. Encode categorical features  
5. Scale numerical features  
6. Split dataset  
7. Train model

# Steps in Data Preprocessing
1.Import Libraries & Dataset

2️. Handling Missing Values


3️. Encoding Categorical Data
Label Encoding
from sklearn.preprocessing import LabelEncoder


One-Hot Encoding


4️. Feature Scaling

Feature scaling helps all numerical features stay in the same range.

from sklearn.preprocessing import StandardScaler



5️. Train-Test Split

Split data into training and testing sets.
