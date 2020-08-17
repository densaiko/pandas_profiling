# Pandas Profiling Overview
Pandas profiling is a module from python that can show a brief Exploratory Data Analysis and interactive report in HTML from our dataset. 
There are several things that we can have from pandas profiling such as:
- **Type inference:** detects the type of columns in a dataframe
- **Esentials:** type, unique and missing values
- **Quantile Statistics:** minimum values, Q1, median, Q3, maximum, range, interquartile range
- **Histogram**
- **Correlation**
- **Missing Values:** count, Heatmap of missing values

# How to Install Pandas Profiling
First, install the library in this command
> pip install pandas-profiling

Second, import pandas profiling library
> from pandas_profiling import ProfileReport

Finally, run our dataframe using pandas profiling
> profile_report = df.profile_report(explorative=True, html={'style': {'full_width': True}})

> profile_report
