# H1 1. What is Normalisation in DBMS?
Normalisation is a process in which the data redundancy is reduced which leads to improved data integrity. Normalised schemas are efficient in write operations. 
In Normalised schemas, each table stores data related to single entity. Tables are narrow with limited columns. So we will have many discrete tables and primary 
and foreign keys are used to establish connections between these tables. This leads to slower queries in OLAP operations.

# H1 2. What is Star Schema?
Star schema have one Central Table(Fact table) and multiple connected tables(Dimension tables).
