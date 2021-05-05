# Project Title
Analyzing Supermarket Data Across the Country - Company XYZ

# Project Description
Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen to increase.

# Project Steps

## Step 1 - Loading the Dataset
- Using the python `glob` module, collect the needed csv file by matching patterns and append to a list. 
- After using the pandas concat method combine the 3 csv's into a single csv then export to a csv file with a name of your choosing.

## Step 2 - Data Exploration
- Read the new csv file and then view the first rows.
- Check for the shape of the dataframe with the `shape` attribute.
- Check the column names with the `column` attribute.
- Use the `describe` method to get a statistical summary of your data.
- Check for missing values in your data using the `isna` method.
- Use `.info()` to check out the data type of each column.

## Step 3 - Dealing with DateTime Features
- Convert the date and time columns from object to datetime.
- Extract the month, day, and year from the date column and assign to new columns respectively.
- Extract the hour from the time column to a new column.
- Check the unique hours customers purchased goods using the `unique` method.

## Step 4 - Unique Values in Columns
- Select the categorical columns and assign to a list.
- Find the number of unique values in each categorical column using the `unique` method.
- Count the number of each unique value in the categorical columns using `.value_counts()`.

## Step 5 - Aggregration with GroupBy
- Create a groupby object with the "City", and an aggregation function of sum and mean.
- Use the above to create various tables grouped by 'City' and summarised in terms of mean and sum.

## Step 6 - Data Visualization
This is the most important part of your analysis because it allows us to gain insight from our data.
Experiment and explore with various plots such as `countplot`, `boxplot`, `catplot`, `lineplot` and various columns of the dataset.
### Example of plots are:
- A countplot showing the 'Branch' with the highest sales.
- A countplot showing payment method most preffered by the customers.
- A boxplot of the rating accross the 3 branches.
- A catplot Product line per unit price, and Product line per Quantity.


# Insights
Insights have been discussed in 'Summary.ipynb'

# Future Work

To-Do - Suggest tasks you might include in future work to make this project more robust.

# Standout Section

Carried out more analysis to determine relationships and patterns among variables in the dataset through more visualizations (lineplots and catplot)

# Executive Summary.

The excutive summary of this analysis can be found in the repositry as 'Summary.ipynb'
