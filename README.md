## Amazon Sales Analysis

Project Overview
This project focuses on performing end-to-end exploratory data analysis (EDA), data cleaning, feature engineering, visualization, and business insight extraction using an Amazon Sales dataset.
The goal of this project is to simulate a real-world e-commerce analytics workflow by analyzing product pricing, discounts, ratings, customer engagement, and category-level trends.
This project was built as part of a professional Data Analytics portfolio using Python, VS Code, Git, and GitHub.

Objectives (The primary objectives of this project are):
* Clean and preprocess a real-world e-commerce dataset
* Perform exploratory data analysis (EDA)
* Analyze Amazon discount strategies
* Investigate relationships between pricing, discounts, ratings, and popularity
* Generate business insights from data
* Create professional visualizations
* Build a portfolio-ready analytics project
* Dataset Information

Dataset Source:
Amazon Sales Dataset from Kaggle

Dataset contains:
* Product information
* Product categories
* Actual prices
* Discounted prices
* Discount percentages
* Product ratings
* Customer review counts
* Review text data
* Product links and images
* Tools & Technologies Used
* Tool	Purpose
* Python	Data analysis
* Pandas	Data cleaning and preprocessing
* NumPy	Numerical operations
* Matplotlib	Data visualization
* Seaborn	Statistical visualization
* VS Code	Development environment
* Git & GitHub	Version control
* Jupyter Notebook	Interactive analysis
* Project Structure
```
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

Data Cleaning & Preprocessing
Several preprocessing steps were performed to prepare the dataset for analysis.

Cleaning Tasks Performed
1. Currency Symbol Removal

Columns such as:

discounted_price
actual_price

contained currency symbols and commas.

Example:

₹1,299

These values were cleaned and converted into numeric format.

2. Discount Percentage Cleaning

Discount percentage values contained % signs.

Example:

53%

The symbols were removed and converted into float values.

3. Rating Count Cleaning

Rating counts containing commas were cleaned and converted into numeric values.

Example:

12,345
4. Missing Value Handling

Missing values were identified and removed where necessary.

5. Feature Engineering

Additional analytical features were created:

Feature	Description
category_encoded	Encoded category labels
product_name_length	Length of product title
review_length	Length of customer review text
main_category	Simplified top-level category
Exploratory Data Analysis (EDA)

Extensive exploratory data analysis was conducted to understand pricing behavior, customer engagement, and discount strategies.

Correlation Analysis

A professional correlation heatmap was created using engineered numerical features.

Key Findings
Actual price and discounted price show extremely high positive correlation.
Discount percentage has weak negative correlation with ratings.
Review length shows moderate relationship with product prices.
Discounts alone do not strongly influence product ratings.
Category Analysis

Top product categories were analyzed using grouped category visualizations.

Key Findings
Electronics and technology-related products dominate the marketplace.
Home Improvement products receive the highest average discounts.
Office Products and Toys & Games receive relatively lower discounts.
Technology markets appear highly competitive and promotion-driven.
Discount Analysis

The project investigated Amazon's discounting behavior and pricing strategy.

Discount Statistics
Metric	Value
Average Discount	47.69%
Median Discount	50%
Maximum Discount	94%
Minimum Discount	0%
Business Insights
Amazon relies heavily on promotional pricing strategies.
Most products receive medium-to-high discounts.
Several categories use aggressive discounting to compete in the market.
High discounts alone do not guarantee better ratings.
Popularity & Customer Engagement Analysis

Customer engagement was analyzed using rating counts as a popularity metric.

Key Findings
Products with medium-to-high discounts often receive higher engagement.
The relationship between discounts and popularity is not perfectly linear.
Product quality and customer trust likely influence engagement more strongly than discounts alone.
Visualizations Created

The following visualizations were created during the project:

Correlation Heatmap
Advanced Correlation Heatmap
Top Product Categories
Discount Distribution Histogram
Discount Percentage vs Rating Scatterplot
Discount Percentage vs Rating Count Scatterplot
Category-wise Average Discount Analysis
Review Length Distribution
Business Questions Answered

This project explored several important business questions:

Are most products heavily discounted?
Is Amazon using aggressive discount strategies?
Do higher discounts improve product ratings?
Which categories receive the highest discounts?
Do expensive products receive larger discounts?
Do discounts increase customer engagement?
Key Business Insights
Amazon products are heavily dependent on discount-driven pricing.
Technology-related categories experience intense pricing competition.
Discounts increase visibility and engagement but do not guarantee customer satisfaction.
Customer ratings are influenced by factors beyond pricing.
Several premium products use high discounting strategies to improve conversions.
Future Improvements

Potential future improvements for this project include:

Interactive Power BI dashboard
SQL-based analysis
Customer sentiment analysis using NLP
Machine learning prediction models
Time-series sales forecasting
Product recommendation systems
How to Run This Project
1. Clone Repository
git clone https://github.com/indra-swe/amazon-sales-analysis.git
2. Navigate to Project Directory
cd amazon-sales-analysis
3. Create Virtual Environment
python -m venv venv
4. Activate Environment
Windows
.\venv\Scripts\Activate.ps1
5. Install Requirements
pip install -r requirements.txt
6. Run Notebook

Open:

notebooks/amazon-data-analysis.ipynb
Skills Demonstrated

This project demonstrates practical skills in:

Data Cleaning
Exploratory Data Analysis
Feature Engineering
Statistical Analysis
Business Analytics
Data Visualization
Git & GitHub Workflow
Analytical Storytelling
Portfolio Development
Author

Indra

GitHub:

https://github.com/indra-swe

Conclusion

This project demonstrates a complete beginner-to-intermediate level data analytics workflow using a real-world e-commerce dataset.

The analysis provides insights into Amazon's pricing strategies, customer engagement behavior, and category-level competition while showcasing practical analytical and visualization skills.
