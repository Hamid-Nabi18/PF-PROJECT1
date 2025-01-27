# PF PROJECT1
# Project Nanme : Sleep Prediction Dataset
## Data Inspection
* df.head(n): View the first n rows (default is 5).
* df.tail(n): View the last n rows.
* df.shape: Get the dimensions of the DataFrame.
* df.info(): Get a summary of the DataFrame.
* df.describe(): Get statistics for numeric columns.
* df.columns: Get or set column names.
* df.dtypes: View data types of each column.


 ## Data Selection

* df['column']: Select a single column.
* df[['col1', 'col2']]: Select multiple columns.
* df.loc[]: Select rows and columns by label.
* df.iloc[]: Select rows and columns by index.
*df.at[]: Access a single value by row/column label.
* df.iat[]: Access a single value by row/column index.



## Data Cleaning

* df.dropna(): Remove missing values.
* df.fillna(): Replace missing values.
* df.isnull(): Check for missing values.
* df.notnull(): Check for non-missing values.
* df.drop(): Drop specified rows or columns.
* df.rename(): Rename columns or indices.
* df.duplicated(): Identify duplicate rows.
* df.drop_duplicates(): Remove duplicate rows.



## Data Transformation

* df.apply(): Apply a function along an axis.
* df.map(): Apply a function to a Series.
* df.replace(): Replace values.
* df.astype(): Change the data type of a column.



## Aggregation and Grouping

* df.groupby(): Group data by a column.
* df.agg(): Apply aggregation functions.
* df.mean(), df.sum(), df.min(), df.max(): Aggregate column values.
* df.cumsum(), df.cumprod(): Calculate cumulative sums/products.


## Merging and Joining

* pd.merge(): Merge DataFrames based on a common column.
* pd.concat(): Concatenate DataFrames along a specific axis.


## Graphs

* df["WorkoutTime"].plot(kind='bar', color='black') : It will create a Bar graph
* df["WorkoutTime"].plot(kind='hist',color='red') : It will create a Histogram graph
* df["WorkoutTime"].plot(kind='barh',color='green') : It will create a Horizontal bar graph
