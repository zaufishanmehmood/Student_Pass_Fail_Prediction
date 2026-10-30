# Student Pass/Fail Prediction using Machine Learning

## Project Overview
This project uses Machine Learning to predict whether a student will pass or fail based on study time, absences, and previous examination grades.

## Algorithm
Logistic Regression (Binary Classification)

## Dataset
UCI Student Performance Dataset – Mathematics (`student-mat.csv`).

Dataset features:
- Study Time
- Absences
- First Period Grade (G1)
- Second Period Grade (G2)

Target:
- 1 = Pass (G3 >= 10)
- 0 = Fail (G3 < 10)

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Machine Learning Workflow
1. Dataset loading
2. Data exploration
3. Target column creation
4. Feature selection
5. Train-test splitting (80/20)
6. Feature scaling using StandardScaler
7. Logistic Regression training
8. Model prediction
9. Model evaluation
10. Model saving using Joblib

## Model Performance

| Metric | Result |
|---|---:|
| Accuracy | 88.61% |
| Pass Precision | 94% |
| Pass Recall | 89% |
| Pass F1-score | 91% |
| Fail Precision | 79% |
| Fail Recall | 88% |
| Fail F1-score | 84% |

## Project Files
- `Student_Pass_Fail_Prediction.ipynb` – Complete project notebook.
- `student_pass_fail_model.pkl` – Trained model and scaler.
- `confusion_matrix.png` – Model evaluation visualization.

## How to Use
1. Download the project files.
2. Install the required Python libraries.
3. Load the saved model and scaler using Joblib.
4. Provide student information.
5. Generate a PASS or FAIL prediction.

## Author
Machine Learning Student Project

## Disclaimer
This is an educational prediction project. Predictions are not guarantees of actual academic outcomes.
