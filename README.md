# 📊 Amazon Sales Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-blue)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📌 Project Overview

This project performs an **end-to-end Exploratory Data Analysis (EDA)** on an Amazon Sales dataset. The analysis simulates a real-world e-commerce analytics workflow by cleaning raw data, engineering useful features, creating professional visualizations, and extracting business insights.

The project showcases practical data analytics skills using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**, making it an excellent portfolio project for aspiring Data Analysts.

---

# 🎯 Project Objectives

The primary objectives of this project are to:

- Clean and preprocess a real-world e-commerce dataset
- Perform Exploratory Data Analysis (EDA)
- Analyze Amazon discount strategies
- Investigate relationships between pricing, discounts, ratings, and popularity
- Generate actionable business insights
- Create professional visualizations
- Build a portfolio-ready data analytics project

---

# 📂 Dataset Information

### Dataset Source

**Amazon Sales Dataset** from Kaggle

### Dataset Includes

- Product information
- Product categories
- Actual prices
- Discounted prices
- Discount percentages
- Product ratings
- Customer review counts
- Customer review text
- Product links
- Product images

---

# 🛠 Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| Python | Data Analysis |
| Pandas | Data Cleaning & Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| VS Code | Development Environment |
| Jupyter Notebook | Interactive Analysis |
| Git | Version Control |
| GitHub | Project Hosting & Portfolio |

---

# 📁 Project Structure

```text
amazon-sales-analysis/
│
├── data/
│   ├── amazon.csv
│   └── amazon_cleaned.csv
│
├── notebooks/
│   └── amazon-data-analysis.ipynb
│
├── outputs/
│   ├── correlation_heatmap.png
│   ├── advanced_heatmap.png
│   ├── top_categories.png
│   ├── discount_distribution.png
│   ├── discount_vs_rating.png
│   └── discount_vs_rating_count.png
│
├── dashboards/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# 🧹 Data Cleaning & Preprocessing

Several preprocessing techniques were applied to transform the raw dataset into an analysis-ready format.

## ✔ Currency Symbol Removal

The following columns contained currency symbols (`₹`) and commas.

- `discounted_price`
- `actual_price`

Example:

```
₹1,299
```

These values were converted into numeric format.

---

## ✔ Discount Percentage Cleaning

Discount values originally contained percentage symbols.

Example:

```
53%
```

The `%` symbol was removed and values were converted to numeric format.

---

## ✔ Rating Count Cleaning

Rating counts contained commas.

Example:

```
12,345
```

They were cleaned and converted into integer values.

---

## ✔ Missing Value Handling

- Identified missing values
- Removed or handled incomplete records where appropriate

---

## ✔ Feature Engineering

Additional analytical features were created.

| Feature | Description |
|----------|-------------|
| category_encoded | Encoded category labels |
| product_name_length | Length of product title |
| review_length | Length of review text |
| main_category | Simplified top-level category |

---

# 📈 Exploratory Data Analysis (EDA)

The project investigates pricing behavior, customer engagement, discounts, ratings, and product categories.

---

# 🔥 Correlation Analysis

A professional correlation heatmap was created using engineered numerical variables.

## Key Findings

- Actual Price and Discounted Price have an extremely strong positive correlation.
- Discount Percentage shows a weak negative correlation with ratings.
- Review Length has a moderate relationship with product prices.
- Discounts alone do not strongly influence customer ratings.

---

# 🏷 Category Analysis

Product categories were grouped and analyzed to understand pricing strategies.

## Key Findings

- Electronics and technology products dominate the marketplace.
- Home Improvement products receive the highest average discounts.
- Office Products and Toys & Games receive relatively smaller discounts.
- Technology markets appear highly competitive and promotion-driven.

---

# 💸 Discount Analysis

The project explores Amazon's pricing strategy through discount behavior.

## Discount Statistics

| Metric | Value |
|---------|-------|
| Average Discount | **47.69%** |
| Median Discount | **50%** |
| Maximum Discount | **94%** |
| Minimum Discount | **0%** |

### Business Insights

- Amazon heavily relies on promotional pricing.
- Most products receive medium-to-high discounts.
- Several categories use aggressive discounting strategies.
- Higher discounts do not necessarily result in better ratings.

---

# ⭐ Popularity & Customer Engagement Analysis

Customer engagement was analyzed using product rating counts.

## Key Findings

- Medium-to-high discounted products often receive greater engagement.
- The relationship between discounts and popularity is not perfectly linear.
- Product quality and customer trust have a stronger influence than discounts alone.

---

# 📊 Visualizations Created

The project includes the following visualizations:

- Correlation Heatmap
- Advanced Correlation Heatmap
- Top Product Categories
- Discount Distribution Histogram
- Discount Percentage vs Rating Scatter Plot
- Discount Percentage vs Rating Count Scatter Plot
- Category-wise Average Discount Analysis
- Review Length Distribution

---

# ❓ Business Questions Answered

This project answers several practical business questions:

- Are most Amazon products heavily discounted?
- Is Amazon using aggressive pricing strategies?
- Do higher discounts improve customer ratings?
- Which categories receive the highest discounts?
- Do expensive products receive larger discounts?
- Do discounts increase customer engagement?

---

# 💡 Key Business Insights

- Amazon heavily depends on discount-driven pricing strategies.
- Technology-related categories experience intense price competition.
- Discounts improve product visibility and engagement.
- Customer satisfaction depends on factors beyond pricing.
- Premium products also use aggressive discounts to increase conversions.

---

# 🚀 Future Improvements

Possible extensions of this project include:

- Interactive Power BI Dashboard
- SQL-Based Analysis
- Customer Sentiment Analysis (NLP)
- Machine Learning Prediction Models
- Sales Forecasting
- Product Recommendation System

---

# ▶ How to Run This Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/indra-swe/amazon-sales-analysis.git
```

---

## 2️⃣ Navigate to the Project Directory

```bash
cd amazon-sales-analysis
```

---

## 3️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

---

## 4️⃣ Activate the Environment

### Windows

```powershell
.\venv\Scripts\Activate.ps1
```

### macOS / Linux

```bash
source venv/bin/activate
```

---

## 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 6️⃣ Launch the Notebook

Open:

```
notebooks/amazon-data-analysis.ipynb
```

---

# 💼 Skills Demonstrated

This project showcases practical skills in:

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Statistical Analysis
- Business Analytics
- Data Visualization
- Git & GitHub Workflow
- Analytical Storytelling
- Portfolio Development

---

# 👨‍💻 Author

**Badhon Indra**

GitHub:

https://github.com/indra-swe

---

# 📜 Conclusion

This project demonstrates a complete beginner-to-intermediate level data analytics workflow using a real-world Amazon e-commerce dataset.

The analysis provides valuable insights into Amazon's pricing strategy, customer engagement, and category-level competition while showcasing practical data analysis, visualization, and storytelling skills suitable for a professional data analytics portfolio.

---

⭐ **If you found this project helpful, consider giving it a star!**
