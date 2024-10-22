# Credit Scoring Model

A Credit Scoring Model that predicts the creditworthiness of individuals using historical financial data. The model is built using machine learning classification algorithms to assess the risk associated with potential borrowers.

## Features

- **Data Handling**: The model processes missing data by filling categorical columns with their respective modes.
- **Label Encoding**: All categorical variables are label-encoded to prepare them for model training.
- **Model**: A Random Forest Classifier is used with `class_weight='balanced'` to address class imbalances in the dataset.
- **Evaluation Metrics**: The model's performance is evaluated using accuracy, classification reports, and confusion matrices.

## Algorithm Used

- **Random Forest Classifier**: A robust and widely used classification algorithm that uses an ensemble of decision trees to make predictions.

## Tech Stack

- **Python**
- **Pandas**: For data loading and preprocessing.
- **scikit-learn**: Used for splitting data, training the Random Forest classifier, and evaluating model performance.
- **Matplotlib**: For future data visualization needs.

## Dataset

The dataset used for this project is `german_credit_data.csv`, which contains financial information and labels of creditworthiness ("Risk") for each individual.

## Demo Video

[Demo Video Link](https://github.com/user-attachments/assets/3e3d584d-e9e6-4382-8db9-920416cdf7ef)








