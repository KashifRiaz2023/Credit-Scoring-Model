Credit Scoring Model
A machine learning model that predicts the creditworthiness of individuals based on historical financial data.

Features
Data Handling: Missing data in categorical columns is filled with the most frequent value (mode).
Label Encoding: Categorical variables are label-encoded to prepare for model training.
Random Forest Classifier: The model uses a Random Forest Classifier with class_weight='balanced' to manage class imbalances.
Evaluation Metrics: Model performance is evaluated using accuracy, classification reports, and confusion matrices.
Algorithm Used
Random Forest Classifier: A popular ensemble learning method that combines multiple decision trees to improve prediction accuracy and handle imbalanced data.
Tech Stack
Python: Programming language used for data manipulation, model training, and evaluation.
Pandas: For data loading, cleaning, and preprocessing.
scikit-learn: Used for model building, data splitting, and evaluation.
Matplotlib: Planned for future data visualization needs.
Dataset
The dataset used for this project is german_credit_data.csv, containing financial details and the creditworthiness labels ("Risk") of individuals.

Demo Video
Demo Video
