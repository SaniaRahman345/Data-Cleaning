# Pandas Data Cleaning
Data cleaning is an essential step in the data analysis process, and Pandas is a powerful Python librarythat facilitates data manipulation and cleaning. Here are detailed steps involved in data cleaning using Pandas:

## 1- Importing Pandas: 
### 2-Loading the Data:
### 3-Understanding the Data:

Use df.head() and df.tail() to inspect the first and last few rows of the dataset.
Check the data types using df.info() to understand the types of columns.
4-Handling Missing Values:

Use df.isnull() to identify missing values in the DataFrame.
Use df.isnull().sum() to get the count of missing values in each column.

# 5-Decide how to handle missing values:

Use df.dropna() to drop rows with missing values.
Use df.fillna(value) to fill missing values with a specified value.
Interpolate missing values using df.interpolate().

# 6-Handling Duplicates:

Use df.duplicated() to identify duplicate rows.
Use df.drop_duplicates() to remove duplicate rows.

## 7-Handling Text Data:

Remove leading/trailing whitespaces using df.str.strip().

Use string methods (str.replace(), str.contains()) to correct inconsistent data.

# 8-Saving Cleaned Data:

Save the cleaned DataFrame to a new CSV or Excel file using df.to_csv() or df.to_excel().
