# Apache Spark: Distributed Databases
#### Contributor(s): Yash Sethia, Ritesh Kumar, Shubham
![Snapshot](https://www.edureka.co/blog/wp-content/uploads/2018/09/Picture5-2.png)

----------
### About

*Apache Spark*, written in Scala, is a general-purpose distributed data processing engine. Or in other words: load big data, do computations on it in a distributed way, and then store it. <br/> <br/>
Apache Spark contains libraries for data analysis, machine learning, graph analysis, and streaming live data. Spark is generally faster than *Hadoop*. 
This is because Hadoop writes intermediate results to disk (that is, lots of I/O operations) whereas Spark tries to keep intermediate results in memory 
(that is, in-memory computation) whenever possible. Moreover, Spark offers lazy evaluation of operations and optimizes them just before the final result; 
Sparks maintains a series of transformations that are to be performed without actually performing those operations unless we try to obtain the results. 
This way, Spark is able to find the best path looking at overall transformations required (for example, reducing two separate steps of adding number 5 and
20 to each element of the dataset into just a single step of adding 25 to each element of the dataset, or not actually doing operations on part of the dataset
which will eventually will be filtered out in the final result). 
<br/><br/>
This makes Spark one of the most popular tools for big data analytics currently.
PySpark is an interface for Apache Spark in Python. It not only allows you to write Spark applications using Python APIs, but also provides the PySpark shell for interactively analyzing your data in a distributed environment.<br/><br/>

In this Notebook, we have the data of an Ecommerce website with the following fields:
- Email ID of the user
- Address of the user
- Average Session Length of the user
- Time spent by the user on the app
- Time spent by the user on the website
- Length of the membership of the user
- Yearly amount spent by the user
The database is however distributed. Thus we use Pyspark API of Apache Spark to handle this data to bring out meaningful inferences and try to predict the Amount spent by users using Linear Regression.

### To run this in your system:
- Clone this repository
- In a terminal, navigate to the folder containing this repository and run the following command:
```
jupyter notebook
```
- This will open the base directory of this repository in your browser. Now, open the   file
- Run all the cells of this file to see the results

