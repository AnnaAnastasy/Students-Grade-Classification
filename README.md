# Predicting Students' Grades

## Overview
This project explores and predicts students' academic performance based on various features, such as demographics, study habits, and parental involvement. By leveraging machine learning models, we aim to classify students into predefined performance categories.

## Project Highlights
- **Data Analysis**: Comprehensive exploration and preprocessing of student performance data.
- **Feature Engineering**: Excluding GPA and creating meaningful features for robust model training.
- **Modeling**: Experimented with various machine learning models, selecting CatBoost as the final model.
- **Performance**: Achieved an accuracy of **74%** with the CatBoost model.

## Dataset
The dataset includes:
- Demographic features
- Study habits and extracurricular activities
- Parental involvement
- Academic performance metrics

### Target Variable
`Grade_Class`: Represents the performance category of students (e.g., A, B, C, etc.).

> **Note:** The GPA column was excluded as it directly influenced the target variable.

## Dependencies
Install the necessary libraries with the following command:
```bash
pip install pandas numpy scikit-learn catboost matplotlib seaborn
```

## Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/predicting-students-grades.git
   cd predicting-students-grades
   ```

2. **Run the Notebook**:
   Open and execute the notebook to reproduce the analysis and results.

3. **Custom Predictions**:
   Replace the test dataset with your data in the provided format to generate predictions.

## Results
- Final model: **CatBoost**
- Accuracy: **74%**
