# ML-Click-Through-Rate-Prediction-Model

# 📢 Ads Click-Through Rate (CTR) Prediction using Machine Learning

This project demonstrates how to use **Machine Learning** in Python to **analyze and predict user behavior** related to advertisements. Specifically, it focuses on predicting whether a user will click on an ad based on various user features like age, internet usage, and time spent on a website.

---

## 📊 Problem Statement

**Click-Through Rate (CTR)** is the percentage of users who click on an ad after seeing it. For example, if 5 out of 100 users click, the CTR is 5%.

### Objective:
Predict whether a user will click on an ad based on their characteristics using a classification model.

---

## 📁 Dataset

The dataset contains 10,000 records with the following key features:

- `Daily Time Spent on Site`
- `Age`
- `Area Income`
- `Daily Internet Usage`
- `Gender`
- `Country`
- `Timestamp`
- `Clicked on Ad` (Target: Yes or No)

📥 **Download Dataset:** [ad_10000records.csv](#)  
> *(Replace `#` with the actual dataset link)*

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Plotly (for interactive visualizations)
- scikit-learn (for ML modeling)

---

## 📈 Exploratory Data Analysis (EDA)

Analyzed how different user attributes affect CTR:

- **Time Spent on Site**: Higher time spent → Higher CTR
- **Daily Internet Usage**: Higher usage → Lower CTR
- **Age**: Users around 40 click more than younger users
- **Area Income**: Users from high-income areas click less

Used **Box Plots** to visualize relationships between features and CTR.

---

## 🔢 Calculating CTR

CTR is calculated as:

```python
click_through_rate = (4917 / 10000) * 100
# Output: 49.17%
