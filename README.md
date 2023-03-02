Project title:
# Analyze Supermarket Data Across the Country - Company XYZ

Project description:
Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen.

# Project Steps
* Various liberies were imported such as: os, glob, numpy, pandas, matplotlib.pyplot etc
* The data containing information of each branch in the 3 major cities were loaded and combined using pd.concat to form a single dataframe with csv extention and then   save as a new file in the local directory conataining the project.
 # 1. The first major task was data exploration
       * The first 5 rows of the newly created file 'Market_data.csv' was displayed
       * no of rows and columns was checked using df.shape
       * check various column name in the dataset using df.columns 
       * statistical surmary was checked using df.describe()
       * Missing data was checked using the isnull
       * General Information of the data was checked using .info
 # 2. The second: Dealing with datetime features
       * Convert the date column to datetime
       * The above was also done for the time column
       * Extract year, month and day from the date column and also hour from from the time column
       * Determine the unique ours of sales in the supermarket and return result as an array.
 # 3. Check for unique value in columns
       * Get a list of the categorical column in the dataset, check if each element in the column is of type object
       * generate the unique values in the categorical columns in this case, Payment, product line, gender and customer type
       * Get a Series containing counts of unique values for various categories
 # 4.  Aggregration with GroupBy
       * Create a groupby object with the "City Column", and aggregation function of sum and mean.
       * Display a table that shows the gross income of each city, and determine the city with the highest total gross income.
 # 5. Data Visualization
       * Determine the branch with the highest sales record using countplot.
       * Determine the highest & lowest sold product line, using Countplot
       * Determine the Payment channel used by most customer to pay for each product line.
       * Determine the Payment channel for each branch.
       * Determine the branch with the lowest rating
       * Generate visualization for the "product line" per gender
       * Generate visualization for the "product line" per "Total" column
       * plot Product line per unit price, and Product line per Quantity
# Insights
      Insights gotten from analysing the dataset consisting of sales record of the 3 branches( Lagos, Abuja and Port-Harcourt) of the supermarket belonging to Company XYZ are:
     
      * Dataset consist of !000 rows and 18 columns
      * Each city is represented as branch; A - Lagos Branch; B - Abuja Branch; C - Port Harcourt Branch
      * Dataset contains no null values
      * The dataset contains records of 501 female customer and 499 male customers
      * Port-Harcourt records the highest revenue(gross income) while Lagos follows next and the Abuja
      *Lagos has the highest no of customers while followed by abuja and the least is Port-Harcourt
      * The most used payment method in general is EBAY and the least is Card
      * The most sold product line in all 3 branches is food and beverages in the city of Port-Harcourt, next is Home and lifestyle in Lagos and the 3rd most sold productline is 'fashion and accessories' in Port-Harcourt. However, in Abuja, the most sold is 'Travel and sport'.
      * The most used payment method with resp to 'Product line' is Cash
      * The branch with the lowest rating is "A" which stands for "Abuja"
      
To-Do - Explain the insights you were able to uncover from the analysing the datasets.

# Future Work

To-Do - Suggest tasks you might include in future work to make this project more robust.

# Standout Section

To-Do - Explain what you did differently in the project following the instructions in the notebook.

# Executive Summary.

To-Do - Include your Executive Summary document in your repository.
