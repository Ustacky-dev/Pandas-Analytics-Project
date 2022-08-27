# Project Title Here
Analyze Supermarket Data Across the Country - Company XYZ

With an increase in Supermarket competition, Company XYZ seeks to understand sales trends and determine its growth. Data sets from from 3 branches (A:Lagos, B:Abuja, and C:Port Harcourt) of Company XYZ are to be analyzed. Each data file contain the following attributes: 
  Invoice ID: Customer Identification number,
  Branch: Supermarket Branch across the country (A, B, C)
    A - Lagos Branch,
    B - Abuja Branch.
    C - Port Harcourt Branch,
  City: Supermarket Location,
  Customer Type: Type of customers, Members - Returning customer with membership card, Normal - Customer without membership (could be returning, first-time or walk-    in customer),
  Gender: Customer Gender Information,
Product line: Product categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and    travel,
 Unit Price: Price of each product in Naira,
Quantity: Number of products purchased by customer,
Tax: 5% tax fee for customer buying,
Total: Total price including tax,
Date: Date of purchase (Supermarket Record available from January 2019 to March 2019),
Time: Purchase time (Supermarket Hours - 10am to 9pm),
Payment: Payment used by customer for purchase (3 methods are available – Cash, Card and Epay),
COGS: Cost of goods sold,
Gross margin percentage: Gross margin percentage,
Gross income: Gross income,
Rating: Customer Satisfaction rating on their overall shopping experience (On a scale of 1 to 10).
The Data Scientist intends to analyze the data sets using popular data analytical packages such as python packages and visualization packages, to provide the company with the information they need to make decisions about their growth.




# Project Steps
Step 1 - Loading Datasets

Correct use of pathname pattern - glob 
and to Combine all the files generated in a list and export to a CSV. 

Step 2 - Data Exploration
  Using the head() method to view first few rows of the dataset,
  Checking the number of rows and columns present in the data using the shape attribute,
  Generate the names of the columns using the columns attribute,
  Using describe function to generate the statistical summary of the dataframe,
  Using meaningful sentences to describe findings from the data statistical summary,
  Using of correct method to check for Missing values,
  Checking the information of the DataFrame using the info method.

Step 3 -  Dealing with DateTime Features
  Using to_datetime() to convert the date column to datetime,
  Checking the datatype to confirm if it's in datetime,
  Accurate conversion of the time column & prints appropriate data type,
  Accurate extraction of the Day, Month, Year & Hour features,
  Determinig the numbers of unique hours of sales in the supermarket are accurately,
  Display result that shows an array that contains the unique sales hours.

Step 4 - Unique Values in Columns
  Using appropriate method to generate the unique values in the categorical columns (apart from the example - Branch column),
  Generating the count figure of the categorical values using the value_counts() method,

Step 5 -  Aggregation with GroupBy
  Use of groupby object with the "City Column", and aggregation function of sum and mean,
  Display a table that shows the gross income of each city, and determines the city with the highest total gross income,
  Optional - Use of appropriate methods & descriptions to explore other columns such as Unit Price, Quantity.

Step 6 - Data Visualization
  Appropriate use of countplot to determine the branch with the highest sales record,
  Appropriate use of countplot to determine the most used payment method & city with the most sales,
  Appropriate use of countplot to determine the highest & lowest sold product line,
Diplay result that shows the Payment channel used by most customers to pay for each product line with Chart showing the "product line" column on the Y-axis, and   the  "hue" parameter for the "Payment" column,


# Insights
The insights obtained from project's analysis are as follows:

Data set is large with exactly 17,000 elements (1000 rows and 17 columns),

The elements for categorical raw data are complete,

Python packages such as pandas analytical tools, Numpy, and Matplotlib as well as data illustrative tools such as Seaborn's statistical visualization package are very efficient and powerful in analysing huge data sets,

Coding lines are not too restictive, i.e packages are user-friendly and flexible. Users creativity shows that usage can be interesting,

Some 'take-home' facts about the company XYZ include:
Sales of Electronic and fashion accessories are almost at par. Sales across cities are very competitive with close matching records. However some details from analyses include:
    -Branch A has the highest sales record.
    -The most used payment method is Epay with a count of 345.
    -The City with the most sales is Lagos.
    -The highest product line sold is Fashion accessories.
    -The lowest product line sold is Health and Beauty.
    -Females purchased higher quantity of products. This might be explained by the higher tendency of women to always go shopping than men.
    -Branch with the lowest rating is B
    -Branch A had slightly higher normal customers than member customers.
    -Branch B had almost equal number of Member and normal customers' patronage.
    -Branch C had more member customers than normal customers.
    -Though quantities purchased for product lines generally are low, most customers prefer using Cash and Epay payment methods.
    -Home and lifestyle gave the highest overall income followed closely by Sports and travel.
This is supported by the fact that home most home utilities are essentials used by a large population of people

Though quantities purchased for product lines generally are low, most customers prefer using Cash and Epay payment methods.

# Future Work
More information can be obtained from this project by including data cleaning and munging.

# Standout Section
Use of appropriate methods & descriptions to explore other columns such as Unit Price, Quantity in Aggregation with GroupBy.
A barplot was made to:
    Display and the gross income for each city.
    Determine the highest customer type patronage;
    Determine the Rating distribution.
    Determine the gender with the highest product purchases.

# Executive Summary.
Summary

Data set is large with exactly 17,000 elements (1000 rows and 17 columns).

The elements for categorical raw data are complete.

Approach:

The approaches for data analyses for company XYZ were to combine seperate data set for each city, make inferential and descriptive statistical analyses and obtain key facts that show and compare the sales performances for Company's branches.

Method:
These were accomplished using some python packages such as pandas analytical tools, Numpy, and Matplotlib as well as data illustrative tools such as Seaborn's statistical visualization package.

Insights:
Python packages such as pandas analytical tools, Numpy, and Matplotlib as well as data illustrative tools such as Seaborn's statistical visualization package are very efficient and powerful in analysing huge data sets.

Coding lines are not too restictive, i.e packages are user-friendly and flexible. Users creativity shows that usage can be interesting.

A 'take-home' fact about the company XYZ include:
Sales of Electronic and fashion accessories are almost at par. Sales across cities are very competitive with close matching records. 
