## 5 NoSQL Databases And Why They Are Used.

### What is NoSQL?
* NoSQL can also said as NO SQL or Not Only SQL.
* It is used when we need to store large amount of data.
* It is better readable and more scalable than RDBMS.

### Why NoSQL?
* Due to increase in digital interaction between the enterprises.
* The new enterprise technology architecture needs to be far more agile than ever before, and requires an approach to real-time data management that can accommodate unprecedented levels of scale, speed, and data variability.
* NoSQL databases are built to be flexible, scalable, and capable of rapidly responding to the data management demands of modern businesses. 

### Types of NoSQL Databases

#### Key Value Database
* Key-value stores are the least complex of the NoSQL databases.
* They are, as the name suggests, a collection of key-value pairs.
* ![Image for Key Value Pair](https://user-images.githubusercontent.com/95225089/183360583-a408d21c-83c4-4d81-bcb6-862366d1c38c.png)
* Examples of key-value stores are Redis, Voldemort, Riak, and Amazon’s Dynamo.

#### Document Database
* Document stores are one step up in complexity from key-value stores: a document store does assume a certain document structure that can be specified with a schema.
* ![Image for document database](https://user-images.githubusercontent.com/95225089/183365707-83fd9e0f-bcfb-4e27-91c4-314c870f0967.png)
* Examples of document stores are MongoDB and CouchDB.

#### Column Oriented Database
* These are NoSQL databases built for highly analytical, complex-query tasks. Unlike relational databases, columnar databases store their data by           columns, rather than by rows. These columns are gathered to form subgroups.

    The keys and the column names of this type of database are not fixed.
* ![Image for column database](https://user-images.githubusercontent.com/95225089/183368781-065bf412-07a1-4208-b1a4-0d2b213bdf62.png)
* Examples of column-family stores are Apache HBase, Facebook’s Cassandra, Hypertable.

#### Graph Database
* The last big NoSQL database type is the most complex one, geared toward storing relations between entities in an efficient manner. When the data is highly interconnected, such as for social networks, scientific paper citations, or capital asset clusters, graph databases are the answer. Graph or network data has two main components:

    Node—: The entities themselves. In a social network this could be people.

    Edge: The relationship between two entities. This relationship is represented by a line and has its own properties. An edge can have a direction, for             example, if the arrow indicates who is whose boss. 
 * ![Image for graph database](https://user-images.githubusercontent.com/95225089/183368089-0dc10ac3-86f1-456e-8fa2-fb028320393d.png)
 * Neo4j is the most popular graph database in use.
 ### Apache Cassandra
 * Apache Cassandra is a highly scalable, high-performance distributed database designed to handle large amounts of data across many commodity servers,      providing high availability with no single point of failure.
 * Apache Cassandra is a Column-Oriented Database.
 * Apache Cassandra, enables organisations to process large volumes of fast moving data in a reliable and scalable way. That's why companies like            Facebook, Instagram and Netflix use Apache Cassandra for mission-critical features.
 * ![image](https://user-images.githubusercontent.com/95225089/183370774-84bccb1f-7ab4-4894-b6d8-c0d27bf340fb.png)
 
 ### Apache Hbase
 * Use Apache HBase™ when you need random, realtime read/write access to your Big Data.
 * This project's goal is the hosting of very large tables -- billions of rows X millions of columns -- atop clusters of commodity hardware. 
 * Apache HBase is an open-source, distributed, versioned, non-relational database modeled after Google's Bigtable.
 
 #### Features
 * Linear and modular scalability.
 * Strictly consistent reads and writes.
 * Automatic and configurable sharding of tables.
 * Automatic failover support between RegionServers.
 * Convenient base classes for backing Hadoop MapReduce jobs with Apache HBase tables.
 * Easy to use Java API for client access.
 * And many more.
 * ![image](https://user-images.githubusercontent.com/95225089/183372040-c6add209-3e0e-4548-8ae7-5bf79e02ae39.png)
 
 ### MongoDB
 * MongoDB is an open-source document-oriented database that is designed to store a large scale of data and also allows you to work with that data very      efficiently. 
 * It is categorized under the NoSQL (Not only SQL) database because the storage and retrieval of data in the MongoDB are not in the form of tables. 
 * It also provides official driver support for all the popular languages like C, C++, C#, and .Net, Go, Java, Node.js, Perl, PHP, Python, Motor, Ruby,      Scala, Swift, Mongoid.
 * ![image](https://user-images.githubusercontent.com/95225089/183375002-e7268c01-57da-4252-bd38-f56aaacdd3fb.png)

 ### Noe4j
 * Neo4j is a graph database. A graph database, instead of having rows and columns has nodes edges and properties.
 * It is more suitable for certain big data and analytics applications than row and column databases or free-form JSON document databases for many use      cases.
 * The circles are nodes. The lines, called edges, indicate relationships. And the any comments inside the circles are properties of that node.
 * Neo4j delivers the lightning-fast read and write performance you need, while still protecting your data integrity.
 * It is the only enterprise-strength graph database that combines native graph storage, scalable architecture optimized for speed, and ACID compliance      to ensure predictability of relationship-based queries.
 * ![image](https://user-images.githubusercontent.com/95225089/183375938-5050b4eb-dbbd-4efc-9450-deebe8606b32.png)
 
 ### Riak
 * Riak is a distributed NoSQL key-value data store that offers high availability, fault tolerance, operational simplicity, and      scalability.
 * Riak is an open-source, Web scalable distributed database based on the NoSQL and Dynamo database system. It is developed by Basho Technologies.
 * ![image](https://user-images.githubusercontent.com/95225089/183377724-57da86d2-bfce-40ac-9805-af6628a0d9b9.png)
### References
* [Difference Between RDBMS and NoSQL](https://www.geeksforgeeks.org/difference-between-relational-database-and-nosql/)
* [Use Of NoSQL](https://www.couchbase.com/resources/why-nosql)
* [Types of Databases](https://dzone.com/articles/nosql-database-types-1)
* [Apache Cassandra](https://www.tutorialspoint.com/cassandra/cassandra_introduction.htm)
* [Apache Hbase](https://hbase.apache.org/)
* [MongoDB](https://www.geeksforgeeks.org/what-is-mongodb-working-and-features/)
* [Neo4j](https://www.bmc.com/blogs/neo4j-graph-database/)
* [Riak](https://en.wikipedia.org/wiki/Riak)
