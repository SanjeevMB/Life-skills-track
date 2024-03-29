# NoSQL Database

## What is NoSQL Database?

1. `NoSQL database` typically use to refer to any non-relational database.
2. It was introduced in the late 2000s.
3.  Cloud computing become popular after NoSQL and cloud hosting started for applications.
4. It's used to store data without a structured mechanism. 
5. Which can be linked together from one table to another table.
6. NoSQL needs low-cost hardware.
7. NoSQL database is faster than a relational database.
8. Autoscaling and Horizontal scaling are possible in the NoSQL database.
9. It never provides the table with a flat-fixed column style means no schema tree.
10. It's best and suitable for online analytical processing.
11. NoSQL database provides the facility to distribute data over multiple servers and multiple regions.
12. eg : MongoDB, Cassandra, DynamoDB, Postegra, Raven, Redius.

## Types of NoSQL?

#### 1. Columnar database
#### 2. Document database
#### 3. Key-value database
#### 4. Graphical database


### Columnar database :

1. A columnar database is a database that stores the data in columns instead of rows.
2. All the columns in the columnar database are self-indexed.
3. Operations like calculating min max or average on the numerical columns are easy to perform.
4. eg: Apache Cassandra, DataStax, Microsoft Azure Cosmos DB, and ScyllaDB,

### Document database :

1. Document database store data in documents similar to JSON objects.
2. This database is used to store descriptions of an image on Facebook or used to store blogs.
3. eg: Amazon DynamoDB, Google Cloud Firestore, Couchbase.


### Key-value database :

1. Key value databases store data as associative arrays where a single value is associated together with a key.
2. Two keys can not be the same every key should be unique.
3. Key value databases can also be used for cache memory on web applications like a shopping cart of e-commerce websites and the session stored in apps like Facebook and Twitter.
4. It allows horizontal scaling.
5. It improves application performance by storing critical pieces of data in memory and low latency access.
6. eg: Amazon DynamoDB, Amazon ElastiCache, ScyllaDB, Couchbase, Redis.


### Graphical database :

1. Instead of tables and documents graphical database store node and relationships in graphical format.
2. Data is stored like a sketch on a whiteboard and it creates a tree according to the node.
3. There is no pre-defined model to store data in the graphical database.
4. Whether it’s a social network, payment network, or road network you’ll find that everything is an interconnected graph of relationships.
5. Relationships always have a direction, a type, a start node, and an end node, and they can have properties, just like nodes.
6. eg: Amazon Neptune, Dgraph, OrientDB, Stardog.

![img](./images/Graphical.png)

###  How NoSQL is different from Relational database


1. Relational databases store data by using an explicit schema. A schema describes how to write data in the database, particularly describing the structure, types, and structures of tables and records. Where there is no predefined schema in NoSQL. 
2. There was some memory loss in the relational database due to the predefined structure of the table but it's resolved in the NoSQL database.


### Conclusion :

##### Therefore, we need to understand the difference between SQL and NoSQL and why it is necessary to use a specific database system for certain tasks

###  References :

1. https://www.simplilearn.com/difference-between-nosql-and-relational-database-systems-article#:~:text=Relational%20databases%20store%20data%20according,data%20when%20changing%20that%20structure.
2. https://neo4j.com/developer/graph-database/
3. https://www.mongodb.com/nosql-explained