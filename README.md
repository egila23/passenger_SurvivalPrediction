# Titanic Dataset Classification - 

## Overview
This project implements machine learning classification models on the Titanic dataset to predict passenger survival.

## Project Structure
- `aarefain_assignment_III.ipynb` - Main Jupyter notebook containing the analysis and models
- `titanic3.csv` - Titanic dataset with passenger information
- `README.md` - This file

## Dataset
The project uses the **Titanic dataset** (`titanic3.csv`) which contains information about passengers aboard the Titanic, including:
- Survival status
- Passenger class (pclass)
- Gender (sex)
- Age

## Key Components

### Q4.1 - Data Loading & Preprocessing
- Loads the Titanic dataset from CSV
- Creates a new dataframe with required columns: `survived`, `pclass`, `sex`, `age`
- Removes rows with missing values (NaN)
- Encodes the categorical `sex` column using LabelEncoder

### Q4.2 - Train/Test Split
- Splits the data into training (70%) and testing (30%) sets
- Uses `random_state=20` for reproducibility

### Q4.3 - Model Training
- Scales input features using StandardScaler
- Trains two classification models:
  - Decision Tree Classifier
  - Logistic Regression

## Dependencies
- pandas
- scikit-learn
- numpy

## How to Run
1. Ensure you have Jupyter Notebook installed
2. Open `aarefain_assignment_III.ipynb` in Jupyter
3. Run all cells to execute the analysis and train the models

## Models Used
- **Decision Tree Classifier** - A tree-based model for classification
- **Logistic Regression** - A linear model for binary classification

## Notes
- The analysis uses standardized features for better model performance
- The dataset is preprocessed to handle missing values
- Categorical variables are encoded for model compatibility
