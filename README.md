# Coffee Shop Descriptive Analysis

[Dataset source](https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales?resource=download)

In order to run the notebook you must:
- have a Unix-like system (Windows support coming with docker)
- have a valid 3.10+ python version
- clone the repo
- create a new virtual environment inside of the project's folder by running: `python3 -m venv .venv`
- activate the `.vevn` with `source <path-to-project>/.venv/bin/activate` (assuming that you have bash, sh or zsh)
- install the `requirements.txt` with `pip install -r requirements.txt`
- have your `kaggle.json` API key (for accessing [kaggle.com](https://www.kaggle.com/)) in your home directory ([More](https://github.com/Kaggle/kagglehub#option-3-read-credentials-from-kagglejson))
---
### With this project I answered the following 13 questions about 3 coffee shops in New York.

**General Sales & Transactions:**
- How does the average transaction quantity vary across different store locations, and which location exhibits the highest variance in sales volume?
- What is the median unit price for each product category, and how do the interquartile ranges compare across categories?
- Are there any outliers in the transaction quantities based on the IQR (Interquartile Range) method?

**Time-Based Analysis:**
- What is the distribution of total sales per hour of the day, and at what time do stores experience the highest and lowest median sales?
- How does revenue fluctuate by day of the week, and which weekday has the highest standard deviation in profit?
- What is the trend in total revenue over time—does it exhibit any seasonal patterns or anomalies?

**Store Performance:**
- What is the coefficient of variation (CV) in transaction quantities across different store locations, and which store shows the most consistent sales performance?
- How does the total revenue per store compare, and which store is the top performer in terms of both mean and median monthly revenue?
- Which store has the highest average transaction value, and is there a significant difference between the top and bottom performers?

**Product Analysis:**
- What is the most frequently purchased product type, and how does its sales distribution compare to the least frequently purchased one?
- Which product category has the highest price variability, and what does the standard deviation suggest about price dispersion?
- Is there a significant difference in average unit price between different product types within the same product category?

**Customer Spending Behavior:**
- What percentage of transactions fall into the top 10% of transaction values, and how does this compare across store locations?
