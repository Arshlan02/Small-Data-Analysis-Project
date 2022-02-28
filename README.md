In this Small Data Analysis Project we will see how data will be Analyzed. And,How to extract the data from bunch of information or file.
In this project, I learn how to work on a real project of Data Analysis with Python. 
At first I created number of questions given below regarding with the project and then I solved that questions with the help of Python. 
It is a project of Data Analysis with Python or you can say, Data Science with Python.

Questions:

Q. 1) Instruction ( For Data Cleaning ) - Find all Null Values in the dataset. If there is any null value in any column, then fill it with the mean of that column.
Q. 2) Question ( Based on Value Counts )- Check what are the different types of Make are there in our dataset. And, what is the count (occurrence) of each Make in the data ?
Q. 3) Instruction ( Filtering ) - Show all the records where Origin is Asia or Europe.
Q. 4) Instruction ( Removing unwanted records ) - Remove all the records (rows) where Weight is above 4000.
Q. 5) Instruction ( Applying function on a column ) - Increase all the values of 'MPG_City' column by 3.

The commands that used in this project :

* import pandas as pd -- To import Pandas library
* pd.read_csv - To import the CSV file in Jupyter notebook
* head() - It shows the first N rows in the data (by default, N=5)
* shape - It shows the total no. of rows and no. of columns of the dataframe
* df.isnull( ).sum( ) - It detects the missing values from each column of the dataframe.
* fillna() - To fill the null values of a column with some particular value
* value_counts - In a column, it shows all the unique values with their count. It can be applied to a single column only.
* isin() - To show all records including particular elements
* apply() - To apply a function along any axis of DF



What is Data Analysis?
Data Analysis: Data analysis is the process of analyzing data in various formats. Even though data is abundant nowadays, it’s available in different forms and scattered over various sources. Data analysis helps to clean and transform all this data into a consistent form so it can be effectively studied.

Once the data is cleaned, transformed, and ready to use, it can do wonders. Not only does it contain a variety of useful information, studying the data collectively results in uncovering very minor patterns and details that would otherwise have been ignored.

So, you can see why it has such a huge role to play in research. Research is all about studying patterns and trends, followed by making a hypothesis and proving them. All this is supported by appropriate data.
