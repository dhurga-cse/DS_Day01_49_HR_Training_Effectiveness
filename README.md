# DS_Day01_49 — HR Training Effectiveness

## Project Overview

This project analyzes employee training data to evaluate whether training improves employee performance.

The analysis compares trained and untrained employees, investigates training duration and attendance, compares different course types, and studies performance improvement across departments.

A Decision Tree model is also built to predict whether an employee's performance improved.

## Dataset

The dataset contains 300 employee records with the following fields:

- Employee_ID
- Department
- Training_Status
- Training_Duration
- Course_Type
- Training_Attendance
- Pre_Training_Performance
- Post_Training_Performance

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## Analysis

The project includes:

- Data cleaning and validation
- Descriptive statistics
- Trained vs untrained comparison
- Training duration analysis
- Course type comparison
- Department-level analysis
- Attendance analysis
- Performance improvement analysis
- Confounding factor discussion

## Visualizations

Four main visualizations were created:

1. Performance improvement: Trained vs Untrained
2. Training Duration vs Performance Improvement
3. Performance Improvement by Course Type
4. Performance Improvement by Department

## Machine Learning

### Algorithm

Decision Tree Classifier

### Prediction Target

- `0` → Not Improved
- `1` → Improved

Performance improvement is calculated as:

`Post_Training_Performance - Pre_Training_Performance`

## Model Evaluation

The Decision Tree model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Feature importance is also analyzed to understand which factors contribute to the prediction.

## Key Insights

The analysis identifies:

- Performance differences between trained and untrained employees
- Relationship between training duration and improvement
- Differences between training programmes
- Department-level performance improvement
- Effect of training attendance
- Factors used by the Decision Tree model

## Practical Applications

The findings can support:

- Training programme evaluation
- Employee development planning
- Course selection
- Training attendance monitoring
- Department-specific training strategies
- Future HR decision-making

## Limitations

This project uses a **synthetically generated dataset for educational purposes** because an original dataset was not provided.

The results therefore should not be interpreted as evidence about a real company's employees.

Training effectiveness can also be affected by factors such as employee experience, job role, motivation, prior skill level, manager support, and course difficulty.

## Future Improvements

- Use real company training data
- Collect data over a longer period
- Include employee experience and job role
- Compare multiple training programmes over time
- Test additional machine learning algorithms
- Deploy the model as an HR analytics dashboard
