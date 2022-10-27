# Ecommerce-data-warehouse-in-HIVE-using-AWS
Designed data warehouse for e-commerce application to perform Hive analytics on Sales and Customer Demographics. This big data project will look at Hive's capabilities to run analytical queries on massive
datasets. Used Adventure works dataset in a MySQL dataset for this project.

<img width="1101" alt="Screen Shot 2022-10-26 at 6 22 58 PM" src="https://user-images.githubusercontent.com/68578215/198169251-1faf85b6-11b1-40e7-a2cd-9be00b409421.png">

## Aim
To perform Hive analytics on Sales and Customer Demographics data using big data
tools such as Sqoop, Spark, and HDFS.

## Data Description
Adventure Works is a free sample database of retail sales data. In this project, we will
be only using Customer test, Individual test, Credit card, Sales order details, Store,
Sales territory, Salesperson, Sales order header, Special offer tables from this
database.

## Tech Stack
➔ Language: SQL, Scala
➔ Services: AWS EC2, Docker, MySQL, Sqoop, Hive, HDFS, Spark

### AWS EC2
Amazon EC2 instance is a virtual server on Amazon's Elastic Compute Cloud (EC2) for
executing applications on the Amazon Web Services (AWS) architecture. Corporate
customers can use the Amazon Elastic Compute Cloud (EC2) service to run
applications in a computer environment. Amazon EC2 eliminates the need for upfront
hardware investment, allowing customers to design and deploy projects quickly. Users
can launch up to 10 virtual servers, configure security and networking, and manage
storage on Amazon EC2.

### Docker
Docker is a free and open-source containerization platform, and it enables programmers
to package programs into containers. These standardized executable components
combine application source code with the libraries and dependencies required to run
that code in any environment.

### MySQL
MySQL is a SQL (Structured Query Language) based relational database management
system. The platform can be used for data warehousing, e-commerce, logging
applications, etc.

### Sqoop
Sqoop is a data transfer mechanism for Hadoop and relational database servers. It is
used to import data from relational databases such as MySQL and Oracle into Hadoop
HDFS, Hive, and export data from the Hadoop file system to relational databases.

### Scala
Scala is a multi-paradigm, general-purpose, high-level programming language. It's an
object-oriented programming language that also supports functional programming.
Scala applications can be converted to bytecodes and run on the Java Virtual Machine
(JVM). Scala is a scalable programming language, and Javascript runtimes are also
available.

### Hive
Apache Hive is a fault-tolerant distributed data warehouse that allows for massive-scale
analytics. Using SQL, Hive allows users to read, write, and manage petabytes of data.
Hive is built on top of Apache Hadoop, an open-source platform for storing and
processing large amounts of data. As a result, Hive is inextricably linked to Hadoop and
is designed to process petabytes of data quickly. Hive is distinguished by its ability to
query large datasets with a SQL-like interface utilizing Apache Tez or MapReduce.

## Approach
- Create an AWS EC2 instance and launch it.
- Create docker images using docker-compose file on EC2 machine via ssh.
- Create tables in MySQL.
- Load data from MySQL into HDFS storage using Sqoop commands.
- Move data from HDFS to Hive.
- Integrate Hive into Spark.
- Using scala programming language, extract Customer demographics information
from data and store it as parquet files.
- Move parquet files from Spark to Hive.
- Create tables in Hive and load data from Parquet files into tables.
- Perform Hive analytics on Sales and Customer demographics data.

## Takeaways
- Understanding various services provided by AWS
- Creating an AWS EC2 instance
- Connecting to an AWS EC2 instance via SSH
- Visualizing the complete Architecture of the system
- Usage of docker-composer and starting all tools
- Copying a file from a local machine to an EC2 machine
- Understanding the schema of the dataset
- Data ingestion/transformation using Sqoop, Spark, and Hive
- Moving the data from MySQL to HDFS
- Creating Hive table and troubleshooting it
- Using Parquet and Xpath to access schema
- Understanding the use of GROUP BY, GROUPING SETS, ROLL-UP, CUBE
clauses
- Understanding different analytic functions in Hive


