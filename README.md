Adidas and Nike — Data Analysis Project

Project Overview

This project analyzes and compares Adidas and Nike products using data extracted from an e-commerce dataset. The goal is to understand how each brand positions itself in the market and how customers respond in terms of pricing, ratings, discounts, and engagement.


Objectives

- Compare pricing strategies between Adidas and Nike  
- Analyze customer ratings and satisfaction  
- Evaluate product popularity (engagement)  
- Identify differences in discount strategies  
- Understand customer perception of value  

Technologies Used

- Python (PySpark)  
- Databricks  
- SQL  
- Data Cleaning & Feature Engineering  
- Exploratory Data Analysis (EDA)  

Project Structure

adidas-nike-analysis/
│
├── notebooks/
│   ├── 01_problem_definition.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_analysis.ipynb
│   ├── 04_visualizations.ipynb
│   └── 05_conclusion.ipynb
│
├── images/ (optional)
└── README.md

---

Data Preparation

- Column names standardized (snake_case)  
- Duplicate products removed  
- Missing values handled  
- Brands normalized (Adidas vs Nike)  
- Dataset balanced between brands  
- Price normalization applied (scale correction)  

Feature Engineering

- Price difference  
- Discount percentage  
- Price category  
- Rating category  
- Popularity (based on reviews)  
- Date transformation (year extraction)  


Key Insights

Pricing Strategy
- Nike has significantly higher average prices  
- Adidas operates in a more accessible price range  

Nike positions itself as a **premium brand**, while Adidas focuses on accessibility.



Discount Strategy
- Adidas offers higher average discounts  
- Nike maintains lower discount levels  

Adidas uses discounts as a **competitive advantage**.


Customer Engagement
- Adidas has significantly higher average number of reviews  
- Dominates most positions in popularity ranking  

Adidas generates **more customer interaction and engagement**.


Customer Ratings
- Adidas has higher average ratings  
- Nike shows lower satisfaction levels  

Adidas delivers **better perceived customer experience**.


Main Insight

> Nike builds value through premium positioning, while Adidas captures customers through accessibility, volume, and perceived value.

Limitations

- Original dataset was imbalanced between brands  
- Data may not represent the full global market  
- Lack of product category segmentation (e.g., running, lifestyle, etc.)


Future Improvements

- Product category analysis  
- Sentiment analysis using NLP  
- Customer segmentation  
- Predictive modeling (rating prediction)  
- Dashboard creation (Power BI)  

Conclusion

This project demonstrates how data analysis can reveal strategic differences between brands and provide valuable insights into customer behavior. By combining pricing, engagement, and rating metrics, it becomes possible to better understand market positioning and decision-making strategies.


Author

Lucas Passion  
Data Analyst | Python | SQL | PySpark  

