# Apache Flink

![Apache Flink](../assets/apache-flink.png)

- `Apache Flink` is an open-source, unified stream-processing and batch-processing framework developed by the Apache Software Foundation.
- It was created in 2011 as a research project at the `Technical University of Berlin`, and became a top-level `Apache project` in 2014.
- It is designed to run in all common cluster environments, perform computations at `in-memory` speed and at any scale, and support various use cases such as event-driven applications, stream and batch analytics, and data pipelines and ETL.

# Key Components

- The core of Apache Flink is a `distributed streaming data-flow` engine written in Java and `Scala`, which executes arbitrary dataflow programs in a data-parallel and pipelined manner.

- Flink provides two core APIs: a `DataStream API` for bounded or unbounded streams of data, and a `DataSet API` for bounded data sets.

- Flink also offers a `Table API`, which is a SQL-like expression language for relational stream and batch processing, and a SQL API, which is semantically similar to the Table API and represents programs as SQL query expressions.

- Flink supports various programming languages, such as Java, Scala, Python, and SQL, and provides connectors to systems such as `Apache Kafka`, `HDFS`, Apache Cassandra, and `ElasticSearch`.

# Use Cases

Flink can be used for a variety of use cases, such as:

- `Event-driven applications`: These are stateful applications that ingest events from one or more event streams and react to incoming events by triggering computations, state updates, or external actions. Examples include fraud detection, online gaming, and social network analysis.

- `Stream and batch analytics`: These are analytical jobs that extract information and insight from raw data. Flink supports both traditional batch queries on bounded data sets and real-time, continuous queries from unbounded, live data streams. Examples include sentiment analysis, anomaly detection, and machine learning.

- `Data pipelines and ETL`: These are processes that convert and move data between storage systems. Flink can read and write data from various sources and sinks, and perform transformations such as `filtering`, `aggregating`, joining, and enriching. Examples include data ingestion, `data cleansing`, and data integration.
