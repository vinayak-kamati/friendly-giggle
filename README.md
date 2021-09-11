# What is ORM?

The term **ORM** stands for **Object-relational mapping**, it is a technique that helps us to query and manipulate data from a database. The database is nothing but it is a location where the collection of information is Organized so that it can be easily accessed, manage, update the data.

## Some common ORMs and related OOPs languages are

ORMs | OOPs
-----|------
Hibernate|JAVA
SQL Alchemy|Flask
Microsoft Entity Framework|.NET framework
Django ORM|Django
JAVA Persistence API|JAVA
NHibernate|.NET framework
Dapper ORM|C#
Doctrine|PHP
JOOQ ORM|JAVA

# Hibernate

***Hibernate** ORM* is one of the best ORM frameworks available for java. It is an object–relational mapping tool for the Java programming language

![Image of hibernate](https://www.tutorialspoint.com/hibernate/images/hibernate_position.jpg)

From the above figure, we come to know Hibernate is acting as a bridge between java objects and RDBMS. For all the **CRUD** operations we hand over the java object to Hibernate and Hibernate internally uses *JDBC* to talk to the RDBMS.

Hibernate uses HQL to execute the queries, then maps the results to java objects. which helps in saving and retrieving the object. Hibernate is a good fit for most applications because they make it very easy to implement CRUD operations. Hibernate can be used both in standalone Java applications and in Java EE applications.

## Hibernate Features

- Hibernate is used in the data layer of applications.
- It implements JPI (Java persistence API)

## Technologies that are supported for Hibernate is listed below

- HSQL Database Engine.
- Informix Dynamic Server.
- PostgreSQL.
- DB2/NT.
- FrontBase.
- Microsoft SQL Server Database.
- Oracle.
- Sybase SQL Server.
  
## Mapping in Hibernate

- mapping is the mechanism of placing an object's properties into column’s of a table. hibernate application can contain any number of  mapping files.
- Mapping can be given to an ORM tool either in the form of an XML or in the form of annotations.
  
> ### Collection mapping

  Hibernate supports collection mapping as value type. In this mapping, the collection are mapped into a separate table. If an entity or class has a collection of values for a particular variable, then we can map those values using any one of the collection interfaces available in java.

  We can map collection elements of Persistent class in Hibernate. we need to declare the type of collection in Persistent class from one of the following types:

    java.util.List
    java.util.Set
    java.util.SortedSet
    java.util.Map
    java.util.SortedMap
    java.util.Collection 

  ![Image of hibernate](https://www.javatpoint.com/jpa/images/jpa-collection-mapping.png)

> ### Association Mappings

  Association between two or more things is refers to the state of being associated i.e. how the things are related to each other. Association Mappings is used to model the relationship between two database tables as attributes in our domain model. Association relationship can be unidirectional or bidirectional.

  Ways of implementing association in hibernate using xml:

- Hibernate One-to-One Mapping
- Hibernate One-to-Many mapping
- Hibernate Many-to-One mapping
- Hibernate Many-to-Many mapping

  ![Image of hibernate](https://i.stack.imgur.com/HY0gc.png)

> ### Component Mappings

  A Component mapping is a mapping for a class having a reference to another class as a member variable.  When one class object is stored in another class, then that object is called a Hibernate Component Mapping objects.

  Component Mapping represents the has-a relationship, the composition is stronger association where the contained object has no existence of its own.
  
  For example, Employee has an Address, an address cannot exist separately without Employee. Since the Employee and Address entities are strongly related, it is better to store them in a single table.

  ![Image of hibernate](https://cdn.splessons.com/wp-content/uploads/2015/12/Hybernet-SPLessons-5.png)

## configuration object in Hibernate

The Configuration object is the first Hibernate object created in any Hibernate application and is usually created only once during application initialization.

The configuration file contains 3 types of information.

- Connection Properties
- Hibernate Properties
- Mapping file name(s)

## References

- [Tutorialspoint](https://www.tutorialspoint.com/hibernate/hibernate_batch_processing.htm)

- [Hibernate Tutorial- Telusko](https://youtu.be/JR7-EdxDSf0)

- [Hibernate](https://hibernate.org/)
