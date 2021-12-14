# Quantium Internship Chips products data analysis: Project Overview
<img src="https://github.com/Aellawah/Quantium-Internship-Chips-products-data-analysis/blob/main/Data%20files/Chips.jpeg">
Our client is a company that owns several hypermarkets in the region that sells different types of products, the client wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region.

The client has provided us with two datasets related to chips transactions:

- Transactions dataset
- Customers dataset

- Generated thorough insights from the data that will help the company to improve it's business

# Code and Resources Used

**Python Version:** 3.7

**Packages:** Pandas,numpy,sklearn,matplotlib,seaborn

# Data Cleaning:

The client as i mentioned has provided me with Two datasets Transactions dataset,Customers dataset:

- Changed Data column types
- Removed Duplicates

# Features Engineering:

- Extractied from DATE column year,month,week_day_name,month_day_name columns

# Outliers handling:

- Removed Outliers from Product Quantity,Packet Size,Total Sales

# Exploratory Data analysis
In this section i joined the Two data togethor and applied(Univariate analysis,Bivariate analysis,Multivariate analysis)

Univariate Analysis main findings:

- Transactions amount are almost the same over the months but it is the most in March and the least in February
- Transactions are distributed over the week with almost the same amount but it increases slightly on sunday
- Decreases by the end of the month in 29,30,31
- The chips are more popular among the old people than young people since older singles,retirees,older families
- Mainstream segment buy chips more frequently than other segments

Bivariate Analysis main findings:

- Most of the sales are coming from older singles/couples,retirees,older families
- Most of the sales are coming from Mainstream segment
- Most of the sales are coming in March
- Sales amount tend to be higher on sunday beacause people go shopping more often in their vacation than other days

Multivariate Analysis main findings:

- Kettle products are most popular among the most purchasing segment
- Most sales driving packet size is 135 which is bought mostly in 1 units or 2 units per transaction
- The best selling product among all Mainstream,budget,premium customers segments is Kettle Mozzarella Basil & Pesto 175g
- Most sales are made by OLDER FAMILIES in the budget segment,RETIREES,YOUNG SINGLES/COUPLES in Mainstream segment
- The most admired product is (Kettle Mozzarella Basil & Pestoamong) among Young singles/couples - Mainstream & Older Families Budget & Kettle Honey Soy Chicken among Retirees

Final conclusion:
- Transactions are almost done on sunday since it's a vacation and everyone is free for shopping so the sales amount increases on that day, most of our sales in general are coming from singles/couples,retirees,older families they seem to admire chips more than younger people, most of them are from mainstream segment, people tend to like kettle chips more than any other chips,Kettle Mozzarella Basil & Pesto 175g has the highest sales record

- We have made further investigation to find more precise results and found out that the best customers that derive the highest amount of sales to us are older families in budget segment,Retirees & young singles/couples in Mainstream segment so we should increase our marketing effort towards them ,the most admired product for them is (Kettle Mozzarella Basil & Pesto 175 g)
