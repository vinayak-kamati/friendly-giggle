### What is ORM?

The term **ORM** stands for **Object-relational mapping**, it is a technique that helps us to query and manipulate data from a database. The database is nothing but it is a location where the collection of information is Organized so that it can be easily accessed, manage, update the data.

> Some common ORMs and related OOPs languages are:

OOPs | ORMs
-----|------
Hibernate|JAVA
SQL Alchemy|Flask
Microsoft Entity Framework:|.NET framework
Django ORM|Django
JAVA Persistence API|JAVA
NHibernate|.NET framework
Dapper ORM|C#
Doctrine|PHP
JOOQ ORM|JAVA

> #### Hibernate:

***Hibernate** ORM* is one of the best ORM frameworks available for java. It is an object–relational mapping tool for the Java programming language

![Image of hibernate](https://www.tutorialspoint.com/hibernate/images/hibernate_position.jpg)

From the above figure, we come to know Hibernate is acting as a bridge between java objects and RDBMS. For all the **CRUD** operations we hand over the java object to Hibernate and Hibernate internally uses *JDBC* to talk to the RDBMS.

Hibernate uses HQL to execute the queries, then maps the results to java objects. which helps in saving and retrieving the object. Hibernate is a good fit for most applications because they make it very easy to implement CRUD operations. Hibernate can be used both in standalone Java applications and in Java EE applications.

> ###### Hibernate Features:

  - Hibernate is used in the data layer of applications.
  - It implements JPI (Java persistence API)

> ###### Technologies that are supported for Hibernate is listed below:

- HSQL Database Engine.
- Informix Dynamic Server.
- PostgreSQL.
- DB2/NT.
- FrontBase.
- Microsoft SQL Server Database.
- Oracle.
- Sybase SQL Server.
  
> ###### Mapping in Hibernate:
- mapping is the mechanism of placing an object's properties into column’s of a table. hibernate application can contain any number of  mapping files.
- Mapping can be given to an ORM tool either in the form of an XML or in the form of annotations.
  
  ##### Collection mapping: 
  If an entity or class has a collection of values for a particular variable, then we can map those values using any one of the collection interfaces available in java.

  ##### Association Mappings:
  Association Mappings is used to model the relationship between two database tables as attributes in our domain model.

  ##### Component Mappings:
  A Component mapping is a mapping for a class having a reference to another class as a member variable.

> ###### configuration object in Hibernate:

The Configuration object is the first Hibernate object created in any Hibernate application and is usually created only once during application initialization.

The configuration file contains 3 types of information.

   - Connection Properties
   - Hibernate Properties
   - Mapping file name(s)

>##### References:

- [Tutorialspoint](https://www.tutorialspoint.com/hibernate/hibernate_batch_processing.htm)

- [Hibernate Tutorial- Telusko](https://youtu.be/JR7-EdxDSf0)
