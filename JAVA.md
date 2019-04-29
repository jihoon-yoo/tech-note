# All about Java

## Learning

- <http://www.precisejava.com>
- <http://bigocheatsheet.com>
- <https://javapapers.com>

## Things to review

### Annotation

- known as metadata
- a form of syntactic metadata that can be added to Java source code
- Why important?

### JDO (Java Data Objects)

- https://bre.is/58oapqUb4
- [JPA (Java Persistence API)](https://bre.is/zBmTIpNl9)
  - describes the management of relational data in applications using Java Platform, SE and Java Platform, EE.

### DAO (Data Access Object)

- https://bre.is/PSpUOJNdu
- an object that provides an abstract interface to some type of database or other persistence mechanism

### ORM (Object Relation Mapping)

- https://bre.is/3qZ5pUQwT
- [Hibernate](https://bre.is/uTPBJFHfy)

  - an object-relational mapping library for the Java language, providing a framework for mapping an object-oriented domain model to a traditional relational database.

### Apache Maven

- [Wiki](https://bre.is/tOAQfNord)
- a build automation tool used primarily for Java projects. Maven addresses two aspects of building software: it describes how software is built, and it describes its dependencies.

## Scala

- __Full support for functional programming__
- very strong static type system
- source code is intended to be compiled to Java bytecode, so that the resulting executable code runs on a Java virtual machine.
- __Cloud computing__: Two significant open source cluster computing solutions are based on Scala: Apache Spark and Apache Ignite (adapted from the commercial GridGain product). Additionally, Apache Kafka, the publish-subscribe message queue popular with Spark and other stream processing technologies, is written in Scala.

## Java Data Structures

### HashTable / HashMap

- Key-Value pair
- Hashing: rehash()
- Collision Resolution: HashTable = a list of LinkedList

### Vector vs ArrayList

- Synchronized (Vector) vs Not-Synchronized(ArrayList)
- Initialize both of them with enough capacity: resizing is expensive.