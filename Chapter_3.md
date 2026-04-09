# Chapter 3 
----------------
## 1.1 Abstract Data Models 
- A **Data model** is a representation of some data 
- **Abstraction** is a process of simplification, it removes deteail and replaces them with concepts. 
- An abstract vs regular data model differ in amount of detail provided and scope. Scope increases in abstract data models because they often have more than one relationship.
----------------
## 1.2 - What is a UML Object Diagram 
- **UML** is Unified Modeling Language that is used to represent, design, and implement complex software systems 
- UML diagrams use standardized models to divide the software system into components and subcomponents 
- An **Object Diagram** is similar to a class diagram, except it refers to the objects (instances of classes) in the system.
- A ** class diagram** shows abstraction, an **object diagram** shows an instance at a given point in time. 
- Object Diagrams are excellent tools when we want to build a prototype of a system 
----------------
## 1.3 - What is a UML Class Diagram 
- A class diagram shows the **associations** between classes 
- **aggregation** indicates a parent/child relationship, where child survives if the parent class is destroyed. Similar to how a page can exist without a book, but a book cannot exist without a page. 
- **Composition** is aggregation, but the parent dies and so will the child. This is usually due to inheritance. 
----------------
## 1.4 - What is a database schema
- A **Database Schema** contains the design or list of attributes and instructions that tells the database engine how the data is organized and how the components are related
- In **Schema Theory** knowledge is organized into units
- **Schemata** or units of knowledge contain or store information 
- A schema is a conceptual system for understanding knowledge or a generalized description of such knowledge. 
- A **sort key** allows the database engine to quickly sort the table into a specific order
- A **linked key** is used to link entries in one table with the associated entries in another table 
----------------
## 1.5 How to Design a Database Schema 
- A **physical schema** displays the hardware, servers, and connection that need to be set up to install the database. 
- A **logical schema** is the structure of the data itself. This is what programmers, DB admins, and end users will be working with. 
- **Normalizing** data is when you reduce redundancies among the tables in a database 