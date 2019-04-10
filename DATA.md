# Big Data Engineering

### Resources:
- https://www.kdnuggets.com/

### Data Engineering?
- Build / maintain real-time data pipeline/streaming system
- Clean data, turn then into a usable state

### Data Engineering Role:
> Communicate with stakeholders. Build systems / solutions: loading, organizing, pipping, and returning intelligence

### Data Engineering Skills:
- Programming in Python/R/Java/Scala
- SQL/NoSQL, Data Warehouse, Data Lake
- Cloud-based Distributed Systems: AWS, GCP
- Ecosystem:
    - ingestion: Kafka, Kinesis
    - processing frameworks: Hadoop, Flink
    - storage engines: S3, HDFS, HBase, Kudu
- Machine Learning

### MapReduce: http://goo.gl/Dmj3
> a programming model for processing large data sets with a parallel, distributed algorithm on a cluster.

### Data Pipeline / Stream Processing: https://bre.is/3TPrtvoeX


# Apache Hadoop Ecosystem:
- https://goo.gl/nHjfe0
- Platform for big data applications
- 2 major layers / components:
    - Processing / Computation Layer (MapReduce)
        - Map: put data into analysis friendly format
        - Reduce: performing mathematical operations
    - Storage Layer: HDFS
- additional modules:
    - Hadoop Common: Java libraries required by other modules
    - Hadoop YARN: framework for job scheduling and cluster resource management

- 5 elements of Hadoop
    - Data management:
        - HDFS (Hadoop Distributed File System): Java-based file system that provides scalable and reliable data storage that is designed to span large clusters of commodity servers.
        - YARN (Yet Another Resource Negotiator): framework for Hadoop data processing extending MapReduce capabilities by supporting non-MapReduce workloads associated with other programming models.
    - Data Access:
        - MapReduce
        - Storm: distributed real-time computation system
        - Kafka: Strema processing platform
        - HBase:
        - HCatalog: metadata & table management
        - Hive: SQL interface, data warehouse on top of Hadoop
        - Pig: scripting language for Hadoop
        - Solr: search engine
        - Slider:
        - Mahout:
    - Data Governance and Integration:
        - Workflow Management
        - Flume: store log files & events
        - Sqoop: move structured data from/to SQL databases
    - Security
        - Knox:
        - Ranger:
	- Operations
        - Ambari: management & monitoring
        - Oozie: workflow & scheduling
        - ZooKeeper:

# Apache Spark
- https://goo.gl/ve5tD1
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
- Formula?
- Parallel programing features
	- Accumulator
	- Broadcast variables
- Performance and debugging
	- SparkConf() class
	- Spark Web UI
- Spark Fundamentals I Course: https://goo.gl/4StVDv
- Apache Beam: Programming model to implement batch and streaming data processing jobs.

# Data Science:
- http://goo.gl/vlFhY
- Goals:
    - To understand consumer behavior
    - To find meaningful relationship between people
- data-driven services: recommendation, targeted advertising, personalized medicine
- predictive analysis: customer churn (behavior) modeling, credit risk scoring, hospital readmission, insurance modeling

# BI (Business Intelligence):
- http://goo.gl/J5kN

# DSS (Decision Support System):
- http://goo.gl/KhBP


# RDBMS => distributed NoSQL
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

