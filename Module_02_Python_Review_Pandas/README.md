# Pandas

## Topics covered in today's module

* Introduction to Pandas
* Tabular Data
* Operations on Tabular data

## Main takeaways from doing today's assignment
<img src="https://media.geeksforgeeks.org/wp-content/uploads/finallpandas.png" width=50% height=50%> \
&minus; Initialize a Dataframe using `pd.DataFrame(data, columns)`
- data: list of series of data of any type
- columns: list of string labels for columns

&minus; Useful analysis and manipulation tools: 
- Basic statistics (mean, std, quartiles, etc): `describe()`
- Memory Monitoring: `memory_usage(deep=True)`
- Casting: `frame.column_name.astype("target_column")`
- Delete Duplicates: `drop_duplicates(inplace=True)`
- Merge: `merge(frame, on="name", how="left")`
- Sort: `sorted_values(by="name", inplace=True)`

## Challenging, interesting, or exciting aspects of today's assignment
&minus; Dataframes are easier to create and manipulate than SQL tables \
&minus; SQL tables fetch elements much faster than Pandas
- ***I now see why Python is useful in backend web development, which I thought was strange. Pandas allows for data analysis and visualization OF the data held in a SQL database***

## Additional resources used 
[idxmin Function](https://www.geeksforgeeks.org/python-pandas-dataframe-idxmin/) \
[Filter Dataframes](https://www.listendata.com/2019/07/how-to-filter-pandas-dataframe.html) \
[Filter Dataframes](https://builtin.com/data-science/pandas-filter) \
[groupby Function](https://www.geeksforgeeks.org/python-pandas-dataframe-groupby/) \
[Find Unique Values in Columns](https://sparkbyexamples.com/pandas/pandas-find-unique-values-from-columns/) \
[Pandas vs. SQL: Data Analysis](https://medium.com/analytics-vidhya/pandas-vs-sql-for-data-analysis-5a5cd8dc81d5) \
[Pandas vs. SQL: Features and Uses](https://www.scaler.com/topics/pandas/sql-vs-pandas/) \
[Useful Pandas Functions](https://www.analyticsvidhya.com/blog/2021/05/pandas-functions-13-most-important/) \
[Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
