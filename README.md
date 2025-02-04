# NetflixData_Big_Data_Analystic #
Netflix is a popular streaming service that offers a vast catalog of movies, TV shows, and original contents.
This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

The commands that I used in this project :

* head() - It shows the first N rows in the data (by default, N=5).
* tail () - It shows the last N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe.
* size - To show No. of total values(elements) in the dataset.
* columns - To show each Column Name.
* dtypes - To show the data-type of each column.
* info() - To show indexes, columns, data-types of each column, memory at once.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* unique() - It shows the all unique values of the series.
* nunique() - It shows the total no. of unique values in the series.
* duplicated( ) - To check row wise and detect the Duplicate rows.
* isnull( ) - To show where Null value is present.
* dropna( ) - It drops the rows that contains all missing values.
* isin( ) - To show all records including particular elements.
* str.contains( ) - To get all records that contains a given string.
* str.split( ) - It splits a column's string into different columns.
* to_datetime( ) - Converts the data-type of Date-Time Column into datetime[ns] datatype.
* dt.year.value_counts( ) - It counts the occurrence of all individual years in Time column.
* groupby( ) - Groupby is used to split the data into groups based on some criteria.
* sns.countplot(df['Col_name']) - To show the count of all unique values of any column in the form of bar graph.
* max( ), min( ) - It shows the maximum/minimum value of the series.
* mean( ) - It shows the mean value of the series.

