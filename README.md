# Big data analysis : Systems and Methods for Big and Unstructured Data Project

Developed between October and Decemeber 2023 at Politecnico di Milano

The aim of this project is to work on a dataset that contains records of various scientific
publications in the field of Computer Science. The publications in the dataset include books,
articles, thesis and others. The analysis is perfomed using **Big Data methods and No-SQL Databases**.

The first step is to get the dataset from its publisher [dblp.org](https://dblp.org), direct link to the data : [link](https://dblp.uni-trier.de/xml/) and study the documentation
that comes with it to understand its structure. The raw data is an XML file.
DBLP contains:
* Over 7 million publications indexed.
* More than 3 million unique authors.
* Coverage of 60,000+ journal volumes and 60,000+ conference proceedings.


This poses many challenges as the size of the datset is huge (more than 50 GB) and the number of entries is over 7 million records. Records are listed by publication, for this reason, some queries become computationally expensive and even prohibitive (e.g. get all the collaborators of an author), No-SQL Databases and methods for Big Data are deployed to overcome the limitations of relational databases (SQL).

In the first phase a general analysis of the data is performed. Secondly for each technology data are reshaped to better handle the type of queries and the database used. Lastly the different tools are compared to demonstrate their advantages and drawbacks.

The following tools are used:
* **Graph DB: Neo4j**
* **Document DB: MongoDB**
* **distributed computing: PySpark**
* lxml (Python library)
* StAX (Java library)
* draw.io

The result is a pdf analysis where multiple queries are performed.




