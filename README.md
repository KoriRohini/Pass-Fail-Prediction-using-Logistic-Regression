# Pass/Fail Prediction (Logistic Regression)

<br>

## Overview

This project builds a **Logistic Regression** classifier to predict whether a student will pass or fail based on academic performance indicators. It uses Python, Pandas, Matplotlib, and Scikit-Learn within a Google Colab environment.

<br>

---

<br>

## Dataset Overview

- **Dataset:** Pass-Fail Dataset (`Pass-Fail Data.csv`)
- **Features:**
  - student_id: Unique identifier for each student
  - attendance_pct: Student attendance percentage
  - homework_pct: Homework completion percentage
  - midterm_score: Score achieved in the midterm exam
  - study_hours_per_week: Number of hours spent studying weekly
- **Target:** pass (0 = Fail, 1 = Pass)

<br>

---

<br>

## Tech Stack & Libraries

- Python
- Pandas (data handling & preprocessing)
- Scikit-Learn (train-test split, Logistic Regression, evaluation)
- Matplotlib (visualization)

<br>

---

<br>

## Workflow & Steps

1. Load dataset using Pandas
2. Explore and preprocess the data
3. Separate features (X) and target (y)
4. Perform 80-20 train-test split (`random_state=42`)
5. Train Logistic Regression classifier
6. Evaluate predictions with accuracy score
7. Visualize Attendance Percentage vs. Midterm Score scatter plot categorized by pass/fail outcome

<br>

---

<br>

## Results & Accuracy

- **Model Used:** Logistic Regression
- **Test Size:** 20% of the dataset
- **Random State:** 42
- **Evaluation Metric:** Accuracy Score
- **Visualization:** Scatter plot showing Pass and Fail student distributions

<br>

---

## About

A machine learning project implementing Logistic Regression in Python to analyze academic performance and predict student pass/fail outcomes using educational indicators.

<br>
