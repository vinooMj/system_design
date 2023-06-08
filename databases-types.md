Understanding databases⬇

There are different ways to classify databases based on various criteria. Here I am explaining three major databases.

Relational databases:
These databases use tables to store data, where each table has rows and columns. Each row represents an instance of an entity, 
and each column represents an attribute of the entity. Relational databases use SQL (Structured Query Language) to query and manipulate 
data. Examples of relational databases are MySQL, Oracle, SQL Server, etc.

Non-relational or NoSQL databases: 
These databases do not use tables to store data, but rather use other data structures such as documents, key-value pairs, columns, 
or graphs. Non-relational databases are more flexible and scalable than relational databases, and can handle large volumes of unstructured
or semi-structured data. Examples of non-relational databases are MongoDB, Cassandra, Redis.

A time series database:
TSDB is a database optimized for storing and serving time series data, which are data points that are associated with a timestamp and 
measure change over time. ¹² Time series data can be found in many domains, such as sensor data, IoT data, application performance 
monitoring, network data, stock trading, etc. 
Some examples of time series databases are InfluxDB, Prometheus, TimescaleDB, Apache Druid, etc. 
