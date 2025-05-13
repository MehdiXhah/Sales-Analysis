Diwali Sales Analysis

This project explores consumer behavior and sales trends during the Diwali festival using a retail sales dataset. The analysis helps identify key customer segments, top-selling product categories, and revenue contributors to support data-driven marketing decisions.



Dataset

The dataset contains the following columns:

User_ID

Gender

Age

Marital_Status

Occupation

City_Category

Stay_In_Current_City_Years

Product_ID

Product_Category_1/2/3

Purchase



Tools & Libraries Used

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn



Steps Performed

1. Data Loading & Initial Exploration

Loaded dataset using pandas.read_csv()

Displayed first few rows with head()

Checked column names, data types, and null values using info() and isnull().sum()


2. Data Cleaning

Dropped unnecessary columns like User_ID, Product_ID, and Product_Category_2/3 (due to high missing values)

Handled missing values with dropna() or by removing irrelevant features


3. Exploratory Data Analysis (EDA)

Gender Distribution: Count plot and total purchase by gender

Age Group Analysis: Purchase trends across age groups

Marital Status Analysis: Purchase distribution by marital status

City Category Analysis: Sales comparison across city tiers

Occupation & Stay Analysis: Evaluated sales by occupation and stay duration

Product Category Analysis: Identified top-selling product categories


4. Insights and Observations

Female customers made more purchases

Married women contributed the highest revenue

Age group 26–35 made the most purchases, while 51–55 spent the most

City category affected spending patterns

Certain product categories generated higher revenue




Conclusion

This analysis provides insights into consumer behavior during Diwali, helping marketers and businesses tailor their offerings to the right customer segments.


Recommendations

Target married and young female audiences in Diwali campaigns

Create premium offers for older customers (51–55 age group)

Customize marketing by city tier

Promote high-revenue product categories more aggressively
