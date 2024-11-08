# Student Ability and Question Difficulty Analysis

This project analyzes how students' abilities to answer questions change over time, examines if questions are becoming easier or harder, and builds a predictive model to determine if a student will answer a question correctly. Below is an overview of the questions we explore and the approach taken for each, aimed at both technical and non-technical audiences.

---

## Project Objectives

### 1. How did the student’s ability to answer the questions change?
To assess if a student’s ability improved, remained stable, or declined over time, we calculated the average "ability" score per year for each student. This data was then visualized to reveal trends in student performance over time. A time-series analysis provided insights on:
- Individual student progress year-over-year.
- Identification of students with consistent improvement or needing additional support.

**Visual Output**: A line chart for each student showing their ability score across the years.

### 2. Did the questions get more difficult or easier?
To understand question difficulty trends, we analyzed the average "difficulty" score across years. By tracking whether questions became harder or easier over time, we were able to identify:
- Trends in difficulty that could impact student performance.
- Potential patterns indicating shifts in educational standards or question design.

**Visual Output**: A trend line showing average question difficulty over time.

### 3. Can you create a model that can predict if a student will answer a question correctly?
Using the data on "student ability," "question difficulty," and other features, we developed a predictive model to estimate the likelihood of a student answering a question correctly. The model could:
- Help anticipate areas where students may struggle and inform targeted support.
- Assist educators in understanding key factors influencing student performance.

**Technical Overview**:
- **Model Type**: Classification model
- **Input Features**: Student ability, question difficulty, and other relevant data points.
- **Output**: Probability of a correct response for each question.

### 4. Additional Observations
In addition to the above analysis, several patterns were noted:
- **Correlation**: A positive correlation was observed between "student ability" and "answered_correctly," suggesting that higher-ability students generally performed better.
- **Yearly Variability**: Some students exhibited fluctuations in ability, possibly due to external factors or varying question difficulty.
- **Difficulty Clusters**: Certain years had clusters of high or low difficulty questions, which could be explored further to understand changes in curriculum or exam standards.

---

## Key Insights for Stakeholders

- **Performance Tracking**: Insights on student progress can guide personalized learning strategies.
- **Question Design Feedback**: Understanding how question difficulty changes can inform future assessment design.
- **Predictive Potential**: The model highlights which students may need additional support, helping to proactively address learning challenges.

---

## Requirements

- **Python Libraries**: pandas, matplotlib, sklearn
- **Dataset Columns**: `student_id`, `question_id`, `ability`, `difficulty`, `answered_correctly`, `year`

---
