# Introduction to DBMS (Database Management System)
---

## Database 

### <b>What is Data ? </b> 
Data is a collection of a distinct small unit of information. It can be used in a variety of forms like text, numbers, media, bytes, etc. it can be stored in pieces of paper or electronic memory, etc.

Word 'Data' is originated from the word 'datum' that means 'single piece of information.' It is plural of the word datum.

### <b>What is Database ? </b> 
- A <b>database</b> is an organized collection of data, so that it can be easily accessed and managed.

- You can organize data into tables, rows, columns, and index it to make it easier to find relevant information.

- <b>Database handlers</b> create a database in such a way that only one set of software program provides access of data to all the users.

- The <b>main</b> purpose of the database is to operate a large amount of information by storing, retrieving, and managing data.


## Types of Database ?  
- ### 1. <b>Centralized Database</b>

It is the type of database that stores data at a centralized database system. It comforts the users to access the stored data from different locations through several applications.

These applications contain the authentication process to let users access data securely. An example of a Centralized database can be Central Library that carries a central database of each library in a college/university.

- ### 2. <b>Distributed Database</b>

Unlike a centralized database system, in distributed systems, data is distributed among different database systems of an organization. 

These database systems are connected via communication links. Such links help the end-users to access the data easily. Examples of the Distributed database are Apache Cassandra, HBase, Ignite, etc.

We can further divide a distributed database system into:

<img src="https://images.javatpoint.com/dbms/images/types-of-databases2.png" />

- <b>Homogeneous DDB : </b> 

    Those database systems which execute on the same operating system and use the same application process and carry the same hardware devices.

- <b>Homogeneous DDB : </b> 

    Those database systems which execute on different operating systems under different application procedures, and carries different hardware devices.

- ### 3. <b> Relational Database</b>    

    This database is based on the relational data model, which stores data in the form of rows(tuple) and columns(attributes), and together forms a table(relation). 

    A relational database uses SQL for storing, manipulating, as well as maintaining the data. E.F. Codd invented the database in 1970.

    Each table in the database carries a key that makes the data unique from others. <b> Examples </b> of Relational databases are MySQL, Microsoft SQL Server, Oracle, etc.

    <b>It have a `ACID` </b> 
    - `A` ---> ACID 
    - `C` -> Consistenct 
    - `I` -> Isolation 
    - `D` -> Durability
     


- ### 4. <b> NoSQL Database</b> 

    Non-SQL/Not Only SQL is a type of database that is used for storing a wide range of data sets. It is not a relational database as it stores data not only in tabular form but in several different ways. 

    It came into existence when the demand for building modern applications increased.

    Thus, NoSQL presented a wide variety of database technologies in response to the demands.
    
    We can further divide a NoSQL database into the following four types:

    - Key Value storage 
    - Document-oriented Database
    - Graph Database
    - Wide-column stores 

- ### 5. <b> Cloud Database </b>

    A type of database where data is stored in a virtual environment and executes over the cloud computing platform. 
    
    It provides users with various cloud computing services (SaaS, PaaS, IaaS, etc.) for accessing the database. 
    
    There are numerous cloud platforms, but the best options are:

    - Amazon Web Services (AWS)
    - Microsoft Azure 
    - Kamatera 
    - PhonixNAP 
    - Google Cloud SQL, etc

- ### 6. <b>Object-oriented Database. </b>

    The type of database that uses the object-based data model approach for storing data in the database system. The data is represented and stored as objects which are similar to the objects used in the object-oriented programming language.

- ### 7. <b> Hierarchical Database </b>

    It is the type of database that stores data in the form of parent-children relationship nodes. Here, it organizes data in a tree-like structure.

    <img src="https://images.javatpoint.com/dbms/images/types-of-databases4.png" />


- ### 8. <b> Network Database </b>

    It is the database that typically follows the network data model. Here, the representation of data is in the form of nodes connected via links between them.
    
    Unlike the hierarchical database, it allows each record to have multiple children and parent nodes to form a generalized graph structure.

- ### 9. <b> Personel Database </b>

    Collecting and storing data on the user's system defines a Personal Database. This database is basically designed for a single user.

- ### 10. <b> Operational Database </b>

    The type of database which creates and updates the database in real-time. It is basically designed for executing and handling the daily data operations in several businesses. 
    
    For example, An organization uses operational databases for managing per day transactions.


- ### 11. <b> Enterprise Database </b>

    Large organizations or enterprises use this database for managing a massive amount of data. It helps organizations to increase and improve their efficiency. Such a database allows simultaneous access to users



 