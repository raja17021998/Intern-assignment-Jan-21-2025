# Quiz Performance Analysis Report

**Author:** Shashwat Bhardwaj  
**Date:** *(Current Date)*  

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Description](#dataset-description)
3. [Code Overview](#code-overview)
4. [Analysis](#analysis)
   - [Current Quiz Insights](#current-quiz-insights)
   - [Historical Trends](#historical-trends)
   - [Recommendations](#recommendations)
5. [Visualizations](#visualizations)
   - [Score Trend Over Time](#score-trend-over-time)
   - [Accuracy Trend Over Time](#accuracy-trend-over-time)
   - [Regression Model: Actual vs Predicted Scores](#regression-model-actual-vs-predicted-scores)
6. [Machine Learning Model](#machine-learning-model)
   - [Prediction Example](#prediction-example)
7. [Conclusion](#conclusion)

---

## Introduction
This report presents a detailed analysis of quiz performance using Python. The aim is to provide insights into a student's strengths, weaknesses, and trends, and generate actionable recommendations for improvement. The report includes code explanations, visualizations, and analysis.

---

## Dataset Description
The analysis is based on three datasets:

- **Quiz Submission Data:** Details of the latest quiz submission, including correct and incorrect answers, accuracy, and negative scores.
- **Historical Data:** Performance data from previous quizzes, including scores, accuracy, and mistakes.
- **Quiz Endpoint Data:** Metadata about the quiz, including questions and topics.

---

## Code Overview
The analysis was implemented in Python, divided into the following steps:

1. **Loading Data:** The JSON files were loaded and parsed.
2. **Analyzing Current Quiz:** Insights were generated from the latest quiz submission.
3. **Historical Data Analysis:** Trends and averages were calculated.
4. **Visualization:** Trends were plotted using Seaborn and Matplotlib.
5. **Recommendations:** Personalized suggestions were generated.
6. **ML Model:** A linear regression model was trained to predict future scores.

---

## Analysis

### Current Quiz Insights
The analysis of the latest quiz submission revealed the following:

- **Correct Answers:** 8  
- **Incorrect Answers:** 2  
- **Accuracy:** 80%  
- **Final Score:** 30  
- **Negative Score:** 2  

### Historical Trends
The analysis of historical data revealed the following trends:

- **Average Score:** 60.29  
- **Average Accuracy:** 72.21%  
- **Average Negative Score:** 5.86  
- **Average Correct Answers:** 15.07  
- **Average Incorrect Answers:** 5.86  

### Recommendations
Based on the analysis, the following recommendations were generated:

- Avoid guessing on difficult questions to reduce negative marking.  
- Take mock tests regularly to improve time management and reduce mistakes.

---

## Visualizations

Visualizations are added. 

---

## Machine Learning Model
A linear regression model was trained using the historical data to predict quiz scores. The model achieved the following evaluation metrics:

- **Mean Squared Error:** 12.45  
- **R-squared Score:** 0.92  

### Prediction Example
Given the following inputs:

- **Accuracy:** 85%  
- **Correct Answers:** 30  
- **Incorrect Answers:** 5  
- **Negative Score:** 2  

The model predicted a future score of **78.2**.

---

## Conclusion
The analysis provided valuable insights into quiz performance and highlighted areas for improvement. The machine learning model demonstrated its ability to predict future scores accurately. By implementing the recommendations, students can improve their preparation and performance.
