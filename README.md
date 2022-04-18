# Apache-Spark
![Snapshot](https://www.edureka.co/blog/wp-content/uploads/2018/09/Picture5-2.png)
#### Contributor(s): Shubham, Yash Sethia, Ritesh Kumar 

----------
### About

*Apache Spark*, written in Scala, is a general-purpose distributed data processing engine. Or in other words: load big data, do computations on it in a distributed way,
and then store it.
Apache Spark contains libraries for data analysis, machine learning, graph analysis, and streaming live data. Spark is generally faster than Hadoop. 
This is because Hadoop writes intermediate results to disk (that is, lots of I/O operations) whereas Spark tries to keep intermediate results in memory 
(that is, in-memory computation) whenever possible. Moreover, Spark offers lazy evaluation of operations and optimizes them just before the final result; 
Sparks maintains a series of transformations that are to be performed without actually performing those operations unless we try to obtain the results. 
This way, Spark is able to find the best path looking at overall transformations required (for example, reducing two separate steps of adding number 5 and
20 to each element of the dataset into just a single step of adding 25 to each element of the dataset, or not actually doing operations on part of the dataset
which will eventually will be filtered out in the final result). This makes Spark one of the most popular tools for big data analytics currently.

### Running Spark in Local Mode:
Spark runs on JVM. It exposes a Python, R, Scala and SQL interface. It runs on a single server. 
Thus it provides benefit from parallelization across all the cores in your server, but not across several servers
For Python, Spark provides Python API via PySpark, which is available in PyPI and so can be installed via pip. 
It can be imported or directly invoked as pyspark to get an interactive shell.
To run this in your system, follow these steps:
- Clone this repository
- In a terminal, navigate to the folder containing this repository and run the following command:
```
jupyter notebook
```
- This will open the base directory of this repository in your browser. Now, open the   file
- Run all the cells of this file to see the results

