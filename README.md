Coffee Shop Revenue & Funnel Analysis
Project Overview

This project analyzes a coffee shop dataset to understand customer behavior, revenue generation, and conversion funnel performance. The goal is to transform raw transactional data into meaningful insights that can support data-driven business decisions.

 Objectives
Clean and preprocess raw data
Build a customer conversion funnel
Calculate key performance metrics
Identify drop-off points in the funnel
Perform category-level analysis
Visualize insights using charts

 Dataset

The dataset contains transactional records from a coffee shop, including:

Product details
Quantity purchased
Revenue generated
Product categories

 Technologies Used
Python
Pandas – Data manipulation
Matplotlib & Seaborn – Data visualization
Jupyter Notebook

 Data Preprocessing
Standardized column names (lowercase, underscores)
Handled missing values
Created new features:
visitor – total interactions
lead – potential buyers (quantity > 0)
customer – confirmed purchases (revenue > 0)

 Funnel Analysis
Funnel Stages:
Visitors – Total records
Leads – Users showing purchase intent
Customers – Users who completed a purchase
Key Metrics:
Visit → Lead Conversion Rate
Lead → Customer Conversion Rate

 Drop-off Analysis

The project identifies where potential customers are lost:

Visitors who did not become leads
Leads who did not convert to customers

 Visualizations
Funnel overview bar chart
Drop-off analysis chart
Category performance comparison

 Insights
Highlights inefficiencies in the sales funnel
Identifies high-performing product categories
Reveals opportunities to improve customer conversion

 How to Run the Project
Clone the repository:
git clone https://github.com/your-username/coffee-shop-analysis.git
Navigate to the project folder:
cd coffee-shop-analysis
Install dependencies:
pip install pandas matplotlib seaborn
Run the notebook:
jupyter notebook

 Future Improvements
Build an interactive dashboard (Streamlit / Power BI)
Add time-series analysis for revenue trends
Implement predictive models for sales forecasting
Perform customer segmentation

 Author
Bonolo Rentsi


License

This project is for academic and educational purposes.
