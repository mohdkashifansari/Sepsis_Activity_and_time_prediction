# Sepsis Next Activity and Remaining Time Prediction Model



## This project focuses on predicting the next activity and remaining time for Sepsis patients based on event logs. The data undergoes thorough cleaning, feature selection, and model training to enhance predictive accuracy.

## Table of Contents
- [Installation](#installation)
- [Data Cleaning & Feature Selection](#data-cleaning--feature-selection)
- [Model Training](#model-training)

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
   git clone https://github.com/mohdkashifansari/Sepsis_Activity_and_time_prediction.git

 
2. Navigate to the project directory:
   cd Sepsis_Activity_and_time_prediction

3. Install dependencies:
   pip install -r requirements.txt


## Data Cleaning & Feature Selection

The dataset undergoes several preprocessing steps to ensure meaningful features are used for training:

- **Data Loading:** Importing the Sepsis event log into a dataframe.
- **Feature Selection:** Dropping irrelevant columns and filtering cases to focus on essential attributes.
- **Activity Flow Processing:** Ensuring all cases start with ER Registration.
- **Visualization:** Scatter plots are used to examine activity counts and remove rare cases.
- **Attribute Processing:** Extracting important attributes like Biomarkers (Leucocytes, CRP, Lactic Acid).
- **Correlation & SHAP Analysis:** Identifying the most relevant features using correlation analysis and SHAP values.

## Model Training

Once the data is preprocessed, machine learning models are trained to predict:
- **Next Activity** in the patient’s journey.
- **Remaining Time** until treatment completion.

The training process includes:
- Selecting the best-performing model.
- Evaluating model performance using appropriate metrics.
- Fine-tuning hyperparameters for better accuracy.

