# Pandas_Profiling-EDA
Pandas profiling is an open source Python module with which we can quickly do an exploratory data analysis with just a few lines of code. Besides, if this is not enough to convince us to use this tool, it also generates interactive reports in web format that can be presented to any person, even if they don’t know programming.
In short, what pandas profiling does is save us all the work of visualizing and understanding the distribution of each variable. It generates a report with all the information easily available.

How to use pandas profiling

1.First step is to install it with this command:

pip install pandas-profiling

2.Then we generate the report using these commands:

from pandas_profiling import ProfileReport

prof = ProfileReport(df)

prof.to_file(output_file='output.html')

Here we are, it’s been that simple. We can see the report generated in the output.html file.

Pandas profiling disadvantage

The main disadvantage of pandas profiling is its use with large datasets. With the increase in the size of the data the time to generate the report also increases a lot.
