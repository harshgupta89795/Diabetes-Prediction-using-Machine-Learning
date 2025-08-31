# Diabetes-Prediction-using-Machine-Learning

A simple Machine Learning project to predict diabetes using Support Vector Machine (SVM).

## Dataset

* Features: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age
* Target: Outcome (0 = No Diabetes, 1 = Diabetes)
* Dataset source: [Kaggle Diabetes Dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)

## Tech Stack

* Python
* NumPy, Pandas
* Scikit-learn

## Steps

1. Load and preprocess data (scaling with `StandardScaler`)
2. Split into training & test sets (80-20 split)
3. Train SVM (linear kernel) model
4. Evaluate using accuracy score

## How to Run

```bash
pip install numpy pandas scikit-learn
python diabetes_prediction.py
```

## Results

* Training Accuracy: \~85-90%
* Test Accuracy: \~75-85%


