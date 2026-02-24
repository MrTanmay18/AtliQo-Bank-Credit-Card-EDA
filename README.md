# 💳 AtliQo Bank Credit Card Launch  
## Statistical EDA & A/B Testing for Business Decision Making

---

## 📌 Project Overview  

This project analyzes customer demographics, transaction behavior, and credit profiles to identify the ideal target segment for launching a new AtliQo Bank credit card.

The analysis is divided into two phases:

- **Phase 1:** Exploratory Data Analysis (EDA) & Data Cleaning  
- **Phase 2:** A/B Testing & Statistical Hypothesis Testing  

The project applies mathematical statistics concepts to make data-driven business recommendations.

---

# 📊 Phase 1 – Customer & Credit Profile Analysis

## 🎯 Objective  
Identify the most suitable customer segment for the new credit card launch.

## 🔍 Key Activities

- Data cleaning (handling null values & duplicates)
- Outlier detection using statistical thresholds
- Occupation-wise median imputation
- Age binning & segmentation
- Credit score segmentation
- Relationship analysis between credit score & credit limit

## 📈 Major Insights

- ~25% of customers belong to the **18–25 age group**
- This segment has:
  - Lower average income
  - Limited credit history
  - Lower credit limits
  - Lower credit card usage
- Credit limit shows a clear step-wise relationship with credit score
- Age and income outliers were handled using occupation-wise median replacement to preserve business realism

---

# 🧪 Phase 2 – A/B Testing for Campaign Effectiveness

## 🎯 Business Problem  
Should AtliQo Bank fully roll out the new credit card campaign?

## 📌 Pre-Campaign Design

- Statistical Power = 0.8  
- Significance Level (α) = 0.05  
- Minimum Detectable Effect Size = 0.4  
- Required Sample Size ≈ 100 customers (based on business constraints)

**Test Structure:**
- Control Group  
- Test Group  
- Campaign Duration: 2 Months  
- KPI: Average Transaction Amount  

---

## 📊 Hypothesis Testing Framework

**Null Hypothesis (H₀):**  
There is no significant difference in average transaction amount between control and test group.

**Alternative Hypothesis (H₁):**  
The test group has a higher average transaction amount than the control group.

**Statistical Test Used:**  
Two-Sample Z-Test (Right-Tailed)

---

## 📈 Results

- Control Group Mean ≈ 221.18  
- Test Group Mean ≈ 235.98  
- Z-Score ≈ 2.74  
- Critical Z (α = 0.05) ≈ 1.645  
- p-value ≈ 0.003  

Since:
- Z-score > Critical Z  
- p-value < 0.05  

**Conclusion:**  
We reject the null hypothesis. The new credit card campaign resulted in a statistically significant increase in average transaction amount.

---

# 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  
- Statsmodels  
- MySQL  

---

# 🧠 Statistical Concepts Applied

- Exploratory Data Analysis (EDA)  
- Outlier Detection (±3σ rule)  
- Median-based Imputation  
- Probability Distributions  
- Hypothesis Testing  
- Two-Sample Z-Test  
- Power Analysis  
- Effect Size Calculation  
- p-value Interpretation  
- One-tailed Testing  

---

# 🚀 Business Impact

This project demonstrates how statistical modeling and hypothesis testing can guide real-world business decisions, optimize marketing budget allocation, and reduce uncertainty in decision-making.

The findings support scaling the new credit card launch strategy based on statistically validated evidence.

---

# 📂 Repository Structure

```
AtliQo-Bank-Credit-Card-EDA/
│
├── Phase1_EDA.pdf
├── Phase2_AB_Testing.pdf
├── AtliQo_Notebook.ipynb
└── README.md
```

---

# 👨‍🎓 Academic Context

Developed as part of MSc Mathematics & Data Science coursework to apply statistical inference techniques in a real-world banking use case.

---

⭐ If you found this project interesting, feel free to connect with me on LinkedIn and explore more data-driven projects!
