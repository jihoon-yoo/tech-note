# Big Data Engineering

## Resources

- <https://www.kdnuggets.com/>

## Data Engineering

- Build / maintain real-time data pipeline(streaming) system and related tools.
- Clean data, turn then into a usable state
- Build systems / solutions: loading, organizing, pipping, and returning intelligence.

## Data Engineering Skills

- Programming in Scala / Java / Python / R
- SQL/NoSQL, Data Warehouse / Lake
- Cloud-based Distributed Systems: AWS, GCP
- Ecosystem:
  - processing frameworks: Hadoop, Flink
  - storage engines: S3, HDFS, HBase, Kudu
  - ingestion: Kafka, Kinesis
- Machine Learning >>> AI 
- Data pipeline / streaming system.

## MapReduce

- [Wiki](http://goo.gl/Dmj3)
- a programming model for processing large data sets with a parallel, distributed algorithm on a cluster.


## Data Pipeline / Steaming: [Wiki](https://bre.is/3TPrtvoeX)

### Apache Kafka

- [Wiki](https://en.wikipedia.org/wiki/Apache_Kafka)
- an open-source stream-processing software platform developed by LinkedIn: donated to the Apache Software Foundation, written in Scala and Java.
- The storage layer is essentially a "massively scalable pub/sub message queue designed as a distributed transaction log".

## Apache Hadoop


- "Open-source software platform for big data applications."
- [Wiki](https://goo.gl/nHjfe0)
- [Ecosystem](https://hadoopecosystemtable.github.io/)
- 2 major layers / components:
  - Storage Layer: HDFS (Hadoop Distributed File System)
  - Processing / Computation Layer (MapReduce)
    - Map: put data into analysis friendly format
    - Reduce: performing mathematical operations
  - additional modules:
    - Hadoop Common: Java libraries required by other modules
    - Hadoop YARN (Yet Another Resource Negotiator): framework for job scheduling and cluster resource management
    - Hive: SQL interface, data warehouse on top of Hadoop
    - HBase: a NoSQL Database for Hadoop.
    - Pig: scripting language for Hadoop.
    - Kafka: Stream processing platform
    - Storm: distributed real-time computation system
    - Ambari: simple management & monitoring over clusters
    - ZooKeeper: maintaining configuration information, naming, providing distributed synchronization, and providing group services.

## Apache Spark

- [Wiki](https://goo.gl/ve5tD1)
- RDD (Resilient Distributed Dataset)
  - Architectural Foundation
  - Cluster-computing framework
  - logically partitioned collection of objects which are usually stored in-memory
  - Programming model for ETL, ML, Streaming, Graph computation
- DStream (Discretized Stream): micro-batch of RDDs
- capabilities
  - Performance: use RAM in smart way
  - Ease of use: Python, Scala, Java
  - Components: SparkSQL, Streaming, MLib, GraphX, and etc.
- Spark Streaming
- Spark MLlib
- Parallel programing features
  - Accumulator
  - Broadcast variables
- Driver vs Executor
- Performance and debugging
  - SparkConf() class
  - Spark Web UI
- DataFrame API
- [Spark Fundamentals I Course](https://goo.gl/4StVDv)
- [Why a Spark application fails or slows](https://bre.is/myC7R0MAe)


## Apache HBase
- open-source, column-oriented distributed DB.
- it was Google Big Table, later re-named as HBase
- columnar DB built on top of HDFS
- all the columns are grouped together as Column families
- written in Java
- low latency operations


## Apache Flink

> Stateful Computations over Date Streams

## Apache Beam

> Programming model to implement batch and streaming data processing jobs.

## Data Science

- [Wiki](http://goo.gl/vlFhY)
- Goals:
  - To understand consumer behavior
  - To find meaningful relationship between people
- data-driven services: recommendation, targeted advertising, personalized medicine
- predictive analysis: customer churn (behavior) modeling, credit risk scoring, hospital readmission, insurance modeling

## BI (Business Intelligence)

- <http://goo.gl/J5kN>

## DSS (Decision Support System)

- <http://goo.gl/KhBP>

## RDBMS >>> distributed NoSQL

- Old SQL can not keep up all big data
  - Schema is fixed
  - Not good for Agile Dev.
  - Inefficient query with multiple tables: join, index, sorting
  - Cashing issue: ACID (atomicity, consistency, isolation, durability) in Transaction is expensive.
  - Sharding issue
- NoSQL/document: Cassandra, CouchDB, MongoDB
- NoSQL/key-value: Redis, Memcached, Amazon DynamoDB, Riak, Ehcache
  - Agile: since no schema
  - Scalable: linear in HW, $$
  - Good hash improve speed
  - Sharing, backup are simple
  - Often, session data
- NoSQL/wide column store: Cassandra, Google BigTable, Apache Hbase
  - No schema
  - 2-D key-value store: the value may be another key-value
- NoSQL/Graph: Neo4J, Titan, Gems
  - Good for: semantic web, graphs
  - Bad for: visualization, serialization, queries more complicated
  - Queries: Sparql, Cypher (Neo4J only)
