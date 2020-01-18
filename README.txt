# Summary

<p>
This main purpose of this project is to lever the data visualization options of PySpark.
Within this a random forest classifier is applied to the breast cancer data set.
PySpark itself does not implement data visualization techniques, but there are currently three major options utilizing the Spark API's.
</p>

<ul>
<li>toPandas()</li>
<li>Pyspark_dist_explore</li>
<li>HandySpark</li>
</ul>

<p>
Pandas is a widely know analytics package used for purposes like data wrangling
and data exploration. In view of PySpark it is interesting to point out that in
Pandas data frames are in-memory, single-server data structure whereas Pyspark are
based on Resilient Distributed Datasets (RDD's). Those are distributed over
the RAM or memory of many machines (possible remotely) in a (cloud) cluster.
By transforming a Pyspark RDD into a Pandas data frame all the analytical operations
of pandas are available and so are the data visualization capabilities of
pandas, matplotlib and seaborn.
</p>

<p>
HandySpark is "Bringing pandas-like capabilities to Spark data frames!" in Pandas.
It does this in PySpark and keeps the data frames distributed. HandySpark offers
a variety of functions for data cleaning and data visualization. It also
makes Pandas accessible by leveraging the Pandas object of the handy data frame.
</p>

<a href=" https://github.com/dvgodoy/handyspark" target="_blank">Github:
HandySpark - bringing pandas-like capabilities to Spark dataframes</a>

<p>
Pyspark_dist_explore allows fast views into DataFrames.
Currently three functions are given: hist(), distplot() and pandas_histogram()
</p>

<p>
Several data sets are used in several formats like csv, json and txt.
The data sources used are stored locally.
The functions and methods applied here include SQL-queries and
SQL-calculations and domain specific PySpark operations
like select, filter, and collect.
</p>

<p>
<b>Spark architecture</b>
</p>

<img src="cluster-overview.png" alt="Smiley face" height="500" width="500"> 


# Import packages