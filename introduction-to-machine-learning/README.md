# 🤖 Introduction to Machine Learning

<p align="center">
  <b>Informatics Practitioner Lecture Series</b><br>
  Exploring Machine Learning concepts through a practical case study.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Google Colab">
</p>

## 📌 Overview

This repository contains a practical implementation inspired by the *Introduction to Machine Learning* practitioner lecture.

The project demonstrates how Machine Learning can learn patterns from academic data and use them to predict student graduation status.

## 🎯 Objectives

- Understand the basic concept of Machine Learning.
- Apply the Supervised Learning approach to a classification problem.
- Implement a Decision Tree classification model.
- Evaluate model performance using standard classification metrics.
- Understand the limitations of predictions based on simulated data.

## 💡 Case Study: Student Graduation Prediction

**Problem:** How can academic data be used to predict whether a student graduates on time?

The implementation uses a simulated dataset containing the following features:

| Feature | Description |
|---|---|
| GPA (IPK) | Student grade point average |
| Attendance | Student attendance percentage |
| Passed Courses | Number of courses passed |
| Graduation Status | Target classification label |

The model uses academic features to classify students into *Lulus Tepat Waktu* and *Tidak Tepat Waktu*.

## ⚙️ Methodology

The project follows a basic Machine Learning workflow:

1. Generate a simulated academic dataset.
2. Explore and prepare the data.
3. Split the dataset into training and testing sets.
4. Train a Decision Tree classifier.
5. Predict graduation status.
6. Evaluate the model using Accuracy, Precision, Recall, and F1-score.
7. Visualize the confusion matrix and decision tree.
8. Test the model with a new student sample.

## 📊 Evaluation and Visualization

The notebook includes:

- **Classification Metrics** — measures model performance.
- **Confusion Matrix** — compares actual and predicted classes.
- **Decision Tree Visualization** — illustrates the model's decision rules.
- **Feature Importance** — shows how the model uses input features.

## 🛠️ Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Run each code cell sequentially.
3. Review the dataset, training process, evaluation metrics, and visualizations.
4. Experiment with new student data to observe the model's predictions.

## ⚠️ Limitations

This project uses simulated data and artificially generated graduation labels. The results are intended for educational purposes and do not represent the actual academic performance of students.

A real-world application would require valid historical data, careful evaluation, and bias assessment before the model could support academic decision-making.

## 📚 Lecture Information

- **Topic:** Introduction to Machine Learning
- **Program:** Informatics Practitioner Lecture Series
- **Date:** October 15, 2026

---

<p align="center">
  <i>Learning Machine Learning by turning data into meaningful predictions.</i> 🌱
</p>
