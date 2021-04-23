# Project Title
Analyzing Supermarket Data Across the Country - Company XYZ

# Project Description
Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen to increase.

# Project Steps

## Step 1 Loading the Dataset
- Using the python glob module, collect the needed csv file by matching patterns and append to a list. 
- After using the pandas concat method combine the 3 csv's into a single csv then export to a csv file with a name of your choosing.

## Step 2 - Data Exploration
- Read the new csv file and then view the first rows.
- Check for the shape of the dataframe with the shape attribute.
- Check the column names with the column attribute.
- Use the decribe method to get a statistical summary of your data.
- Check for missing values in your data using the isna method.
- Use .info() to check out the data type of each column.

## Step 3 - Dealing with DateTime Features
- Convert the date and time columns from object to datetime.
- Extract the month, day, and year from the date column and assign to new columns respectively.
- Extract the hour from the time column to a new column.
- Check the unique hours customers purchased goods using the unique column.

## Step 4 - Unique Values in Columns
- Select the categorical columns and assign to a list.
- Find the number of unique values in each categorical column using the unique method.
- Count the number of each unique value in the categorical columns using .value_counts()

## Step 5 - Aggregration with GroupBy


# Insights

To-Do - Explain the insights you were able to uncover from the analysing the datasets.

# Future Work

To-Do - Suggest tasks you might include in future work to make this project more robust.

# Standout Section

To-Do - Explain what you did differently in the project following the instructions in the notebook.

# Executive Summary.

To-Do - Include your Executive Summary document in your repository.
