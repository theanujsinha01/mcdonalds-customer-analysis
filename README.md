# 🍔 McDonald's Customer Preference Analysis

This project analyzes customer feedback data to understand what drives people to like or dislike McDonald’s. Using Python and data visualization tools in a Jupyter Notebook, we explore how different factors—such as taste, price, health, and visit frequency—affect customer satisfaction.

---

## 📌 Objective

To identify key factors influencing McDonald’s likeability scores and generate insights that could help improve customer experience and business strategy.

---

## 📊 Dataset Overview

- **Source:** McDonald’s survey dataset
- **Total Records:** ~1500
- **Columns Include:**
  - Taste-based feedback: `yummy`, `tasty`, `disgusting`, etc.
  - Pricing & convenience: `cheap`, `expensive`, `fast`, etc.
  - Health perception: `fattening`, `healthy`
  - Demographics: `Age`, `Gender`
  - Behavioral: `VisitFrequency`, `Like` (score from -3 to +5)

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** – Data manipulation
- **Matplotlib** & **Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive coding and analysis

---

## 🔍 Analysis Steps

1. **Data Loading & Cleaning**
   - Converted Yes/No columns to 1/0
   - Checked for nulls and data types

2. **Univariate Analysis**
   - Distribution of Age, Gender, and Like scores
   - Most respondents are aged 40–70

3. **Bivariate Analysis**
   - Likeability by gender and visit frequency
   - Relationship between opinions (e.g. `yummy`, `cheap`) and `Like` score

4. **Correlation Heatmap**
   - Strong positive correlation with: `yummy`, `tasty`, `cheap`, `fast`
   - Strong negative correlation with: `disgusting`, `expensive`

---

## 💡 Key Insights

- Customers who said food was **"Yummy", "Tasty", "Cheap", and "Fast"** gave higher like scores.
- Negative traits like **"Disgusting"** and **"Expensive"** led to lower scores.
- Regular visitors (once a week/daily) rated McDonald's better.
- Most responses came from **female customers aged 40+**.

---

## 📌 Conclusion

McDonald's has strong brand loyalty among frequent visitors, especially due to **taste and affordability**. However, to improve further, it should work on changing negative perceptions about **price and quality**. This analysis can guide marketing and operational strategies.

---

## 📁 Files Included

- `main.ipynb` – Jupyter Notebook with full analysis
- `mcdonalds(1).csv.xlsx` – Original survey dataset


