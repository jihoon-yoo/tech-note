# Big Data Engineering

Resources:
- https://www.kdnuggets.com/


Data Engineering?
- Build / maintain real-time data pipeline/streaming system
- Clean data, turn then into a usable state

Data Engineering Role:
- Communicate with stakeholders
- Build systems / solutions: loading, organizing, pipping, and returning intelligence

Data Engineering Skills:
- Programming in Python/R/Java/Scala
- SQL/NoSQL, Data Warehouse, Data Lake
- Cloud-based Distributed Systems: AWS, GCP
- Eco-system:
    - ingestion: Kafka, Kinesis
    - processing frameworks: Hadoop, Flink
    - storage engines: S3, HDFS, HBase, Kudu
- Machine Learning


Data Pipeline / Streaming:

BI (Business Intelligence): http://goo.gl/J5kN

DSS (Decision Support System): http://goo.gl/KhBP


# Hadoop ecosystem:
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
    - Data Acces:
        - MapReduce
        - Storm: distributed real-time computation system
        - Kafka:
        - HBase: NoSQL DB for interactive apps
        - HCatalog: metadata & table management
        - Hive: SQL interface for Hadoop
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

# Apache Spark: https://goo.gl/ve5tD1
- RDD (Resilient Distributed Dataset)
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

# Data Science: http://goo.gl/vlFhY
- Goals:
    - To understand consumer behavior
    - To find meaningful relationship between people
- data-driven services: recommendation, targeted advertising, personalized medicine
- predictive analysis: customer churn (behavior) modeling, credit risk scoring, hospital readmission, insurance modeling

