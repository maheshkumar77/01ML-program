# Student Placement Prediction using Logistic Regression

## 1. Introduction

This project focuses on building a **basic Machine Learning algorithm** to predict whether a student gets placed or not based on academic and cognitive attributes. The main goal of this project is to understand how **Logistic Regression**, a supervised classification algorithm, works in a real-world scenario.

The model uses **student IQ and CGPA** as input features and predicts a **binary output**:

* **1 → Placed**
* **0 → Not Placed**

The achieved training accuracy of the model is **66.9%**, which is reasonable for a beginner-level ML project with limited features.

---

## 2. Problem Statement

Many students want to understand how their academic performance and aptitude influence placement opportunities. The problem is to build a model that can:

* Analyze student data
* Learn patterns between IQ, CGPA, and placement status
* Predict placement outcomes for new students

This is a **binary classification problem**.

---

## 3. Dataset Description

The dataset consists of student-related features:

| Feature | Description                                  |
| ------- | -------------------------------------------- |
| IQ      | Represents the student’s cognitive ability   |
| CGPA    | Cumulative Grade Point Average               |
| Placed  | Target variable (1 = Placed, 0 = Not Placed) |

The dataset is preprocessed before training to remove inconsistencies and improve learning quality.

---

## 4. Algorithm Used: Logistic Regression

Logistic Regression is a **classification algorithm** used when the output variable is categorical.

### Why Logistic Regression?

* Simple and easy to understand
* Works well for binary classification problems
* Provides probabilistic output
* Efficient for small datasets

The model uses the **sigmoid function** to map predicted values between 0 and 1:

> Probability = 1 / (1 + e^(-z))

If the probability is greater than a threshold (usually 0.5), the student is predicted as *placed*.

---

## 5. Model Training Process

1. Load student dataset
2. Separate features (IQ, CGPA) and target variable (Placed)
3. Split data into training and testing sets
4. Train the Logistic Regression model
5. Evaluate model performance using accuracy

---

## 6. Model Performance

* **Training Accuracy:** **66.9%**

This means the model correctly predicts placement status for nearly **67 out of 100 students** in the training data.

### Interpretation

* The accuracy is acceptable for a first ML project
* Limited features reduce prediction power
* Accuracy can be improved with more data and features

---

## 7. Advantages of the Model

* Easy to implement and interpret
* Requires less computational power
* Good starting point for ML beginners
* Helps understand real-world classification problems

---

## 8. Limitations

* Uses only two features (IQ and CGPA)
* Does not consider skills, internships, or communication ability
* Moderate accuracy
* Performance depends heavily on data quality

---

## 9. Future Improvements

* Add more features (skills, projects, internships)
* Increase dataset size
* Apply feature scaling
* Try advanced models like Decision Trees or Random Forest
* Perform cross-validation for better evaluation

---

## 10. Conclusion

This project successfully demonstrates how **Logistic Regression** can be used to solve a real-world classification problem. With a training accuracy of **66.9%**, the model provides a solid foundation for understanding machine learning concepts such as data preprocessing, model training, and evaluation.

This project is ideal as a **first Machine Learning project** and can be further enhanced with additional data and advanced techniques.

---

**Project Type:** Beginner Machine Learning Project
**Algorithm:** Logistic Regression
**Domain:** Student Placement Prediction
