# Patient Readmission Prediction Using Machine Learning

## Overview
This project predicts whether a patient will be readmitted within 30 days of discharge using machine learning techniques in Python.

## Project Objectives
- Clean and preprocess healthcare data
- Perform Exploratory Data Analysis (EDA)
- Select significant features
- Build and compare machine learning models
- Evaluate model performance

## Dataset Description
The dataset contains:
- Patient ID
- Age
- Gender
- Admission Type
- Length of Stay
- Number of Diagnoses
- Blood Pressure
- Blood Sugar
- Previous Admissions
- Readmission Status

### Target Variable
Readmission:
- Yes = Readmitted within 30 days
- No = Not readmitted within 30 days

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Databricks
- GitHub

## Machine Learning Workflow

### Data Preprocessing
- Missing value handling
- Duplicate detection
- Encoding categorical variables
- Feature scaling

### Exploratory Data Analysis
- Distribution analysis
- Correlation analysis
- Data visualisation

### Feature Selection
- Correlation-based selection
- Predictor justification

### Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Key Findings
- Previous admissions strongly affect readmission risk.
- Length of stay is an important predictor.
- Random Forest often achieves the best performance.

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Deep learning approaches
- Real-time deployment

## Author
Moscow William

## License
MIT License
