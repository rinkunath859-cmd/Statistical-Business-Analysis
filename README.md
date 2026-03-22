# 📊 Statistical Business Analysis

## 🧾 Project Overview
This project presents a comprehensive statistical analysis of business sales data using real-world techniques to extract actionable insights and support data-driven decision-making.

The analysis evaluates how key variables such as **Quantity, Price, and Region** influence **Total Sales**, using statistical modeling and hypothesis testing.

---

## 🎯 Problem Statement
Businesses often collect large amounts of transactional data but fail to utilize it effectively.  
This project aims to identify key factors affecting sales performance and provide insights using statistical techniques.

---

## 🎯 Objectives
- Perform descriptive statistical analysis  
- Analyze data distribution and test for normality  
- Identify relationships between variables  
- Conduct hypothesis testing for validation  
- Estimate population parameters using confidence intervals  
- Build predictive models using regression  
- Translate insights into business recommendations  

---

## 📂 Dataset Description

| Column        | Description |
|--------------|------------|
| Date          | Transaction date |
| Product       | Product category |
| Quantity      | Units sold |
| Price         | Price per unit |
| Customer_ID   | Unique customer ID |
| Region        | Sales region |
| Total_Sales   | Total revenue generated |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|--------|
| Python | Core programming |
| Pandas | Data manipulation |
| NumPy | Numerical analysis |
| Matplotlib | Visualization |
| Seaborn | Advanced visualization |
| SciPy | Statistical testing |
| Scikit-learn | Regression modeling |

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Checked for missing values  
- Verified data types  
- Selected relevant features  

### 2. Descriptive Statistics
- Mean, Median, Standard Deviation  
- Used to summarise the dataset  

### 3. Distribution Analysis
- Histogram plotted  
- Shapiro-Wilk Test applied  

📌 Result: Data is **not normally distributed (p < 0.05)**  

---

### 4. Correlation Analysis
- Pearson correlation used  
- Heatmap visualization  

📌 Finding:  
- Quantity → Strong positive relationship with sales  

---

### 5. Hypothesis Testing
- Normality Test (Shapiro-Wilk)  
- One-Sample T-Test  

📌 Statistical significance evaluated at **5% level**  

---

### 6. Confidence Interval
- 95% confidence interval calculated  
- Provides a range of true means  

---

### 7. Regression Analysis

Model:
Total_Sales = f(Quantity)

- R² ≈ 0.47  

📌 Interpretation:
Moderate predictive power → multiple variables influence sales  

---

## 📊 Results Summary

- Average Sales: ₹123,650  
- Standard Deviation: ₹100,161  
- Data is not normally distributed  
- Regression model explains ~47% variance  

---

## 💡 Key Insights

- Sales exhibit high variability  
- Quantity is a key driver of revenue  
- Data contains skewness and possible outliers  
- Sales are influenced by multiple factors  

---

## 🚀 Business Recommendations

- Implement multi-variable regression models  
- Perform region-wise and product-wise analysis  
- Optimise pricing strategies  
- Use data-driven decision-making frameworks  

---

## ⚠️ Limitations

- No marketing spend variable available  
- Non-normal data distribution  
- Limited feature set  
- Simple regression model  

---

## 🔮 Future Scope

- Apply multiple regression techniques  
- Include marketing and seasonal data  
- Use machine learning models  
- Perform time-series forecasting  

---

## 🧪 Testing & Validation

- Statistical tests validated using SciPy  
- Results cross-verified with visualisations  
- Outputs consistent with expected statistical behaviour  

---

## 📊 Visualizations

The project includes:
- Histogram (Distribution Analysis)  
- Heatmap (Correlation Analysis)  
- Scatter Plot (Regression Relationship)  

Each visualisation is supported with an interpretation in the notebook.

---

## 📁 Project Structure

Statistical-Business-Analysis/
│
├── statistical_analysis.ipynb
├── business_data.csv
├── statistical_report.pdf
├── requirements.txt
├── hypothesis_tests_results.txt
└── README.md

---

## ▶️ How to Run

1. Install dependencies:
pip install -r requirements.txt

2. Run the notebook:
Jupyter Notebook statistical_analysis.ipynb

---

## 🏁 Conclusion

This project demonstrates how statistical analysis can be applied to real-world business data to extract meaningful insights. It highlights the importance of multivariate analysis in improving prediction accuracy and decision-making.

---

## ⭐ Final Statement

“All statistical analyses were conducted at a 5% significance level, ensuring reliability and validity of results. The study emphasizes the importance of multivariate statistical modeling in real-world business scenarios.”
