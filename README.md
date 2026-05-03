# 📊 A/B Testing Analysis Project

## 🚀 Overview

This project demonstrates an end-to-end A/B Testing analysis to evaluate the impact of a new feature/experiment on user behavior and business metrics.

The goal is to determine whether the **treatment group** performs significantly better than the **control group** using statistical analysis.

---

## 🎯 Objective

* Compare performance between Control (A) and Treatment (B)
* Measure key metrics such as:

  * Conversion Rate
  * Click-Through Rate (CTR)
  * Revenue / Engagement
* Perform statistical hypothesis testing
* Draw actionable business insights

---

## 📂 Project Structure

```
AB_Testing.ipynb   # Main notebook with analysis
README.md          # Project documentation
```

---

## 🧱 Dataset Description

The dataset contains user-level experiment data:

| Column         | Description                   |
| -------------- | ----------------------------- |
| user_id        | Unique user identifier        |
| group          | Control (A) or Treatment (B)  |
| converted      | Whether user converted (0/1)  |
| timestamp      | Event time                    |
| other features | Additional behavioral metrics |

---

## 🔍 Steps Performed

### 1. Explaination

A/B Testing — Real Life Story First
Forget code for 2 minutes. Understand the concept with this story.


The Story — Swiggy's New Offer
Swiggy's product team says:


"We think giving a 20% discount popup will increase orders. But we're not sure. Let's test it."


So they split their users into 2 groups:
control Normal app — no popup 5,000 users

Treatment20% discount popup5,000 users

After 2 weeks they check:


Control group placed 2,100 orders → 42% conversion

Treatment group placed 2,600 orders → 52% conversion


Question: Is the 10% difference REAL — or just lucky randomness?
That's exactly what A/B testing answers.


The 3 Questions A/B Testing Answers


Did it work? — Is treatment better than control?

Is it real? — Or did it happen by chance? (p-value)

How confident are we? — Confidence interval

---

### 2. Exploratory Data Analysis (EDA)

* Distribution of users across groups
* Conversion rate comparison
* Basic statistical summaries

---

### 3. Key Metric Calculation

* Conversion Rate:

  ```
  conversions / total users
  ```
* Group-wise performance comparison

---

### 4. Hypothesis Testing

#### Null Hypothesis (H0)

There is **no difference** between control and treatment

#### Alternative Hypothesis (H1)

There **is a significant difference**

* Performed:

  * Z-test / T-test (depending on data)
  * Confidence interval analysis

---

### 5. Statistical Significance

* Calculated p-value
* Compared against significance level (α = 0.05)

---

### 6. Business Interpretation

* Whether experiment is successful
* Impact on conversion / revenue
* Recommendation: Rollout or not

---

## 📊 Key Insights

* Identified whether treatment improves conversion
* Quantified uplift percentage
* Highlighted statistical confidence in results

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* SciPy / Statsmodels

---

## 📈 Example Output

* Conversion Rate Comparison
* p-value and confidence intervals
* Visualizations (bar charts, distributions)

---

## 💡 Business Impact

* Helps product teams make data-driven decisions
* Reduces risk before full feature rollout
* Improves user experience and revenue

---

## 🔥 How to Run

1. Clone the repository
2. Open `AB_Testing.ipynb`
3. Run all cells step-by-step

---

## 🧠 Learnings

* A/B testing fundamentals
* Statistical hypothesis testing
* Data-driven decision making
* Translating analysis into business insights

---

## 📌 Future Improvements

* Add more advanced metrics (retention, LTV)
* Automate experiment analysis pipeline
* Build dashboard for experiment tracking

---

## 👤 Author

**Shivakumar Kadagad**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub — it helps visibility!
