Database , DBMS and RDBMS
1. What is data base and where it's used and why it's used.

A database is an organized collection of data stored and managed on a computer system. It is designed to allow efficient storage, retrieval, and manipulation of data. Databases are commonly used in many applications such as customer relationship management systems, financial transactions, inventory management, and online shopping websites.

________________________________________________________________________________________________________________________________________________________________________________________________________
2. Explain about DBMS and RDBMS,

A Database Management System (DBMS) is a software system that allows users to create, store, retrieve, update, and manage data in a database. It provides a way to organize and manage large amounts of data in a structured way, allowing users to access the data quickly and efficiently.

    Database management system is a software which is used to manage the database. For example: MySQL, Oracle, etc are a very popular commercial database which is used in different applications.
    DBMS provides an interface to perform various operations like database creation, storing data in it, updating data, creating a table in the database and a lot more.
    It provides protection and security to the database. In the case of multiple users, it also maintains data consistency.


Relational Database Management System (RDBMS) is a type of DBMS that stores data in the form of related tables. RDBMS is based on the relational model, which organizes data into one or more tables, with each table consisting of a set of rows and columns. Each row in a table represents a unique record, while each column represents a particular attribute or field. The data in an RDBMS is stored in a way that ensures consistency and accuracy, as well as ease of maintenance and scalability.

    Support for SQL (Structured Query Language) for creating, querying, and manipulating the data in the database.
    Ability to enforce data integrity constraints, such as primary keys, foreign keys, and unique constraints.
    ACID (Atomicity, Consistency, Isolation, Durability) compliance to ensure data consistency and reliability.
    Support for transactions, which allow users to group multiple database operations together and execute them as a single unit.

Examples of RDBMS include Oracle, MySQL, Microsoft SQL Server, PostgreSQL, and SQLite.

________________________________________________________________________________________________________________________________________________________________________________________________________
 Different between DBMS and RDBMS.
 ________________________________________________________________________________________________________________________________________________________________________________________________________
 	DBMS											|		RDBMS
_________________________________________________________________________________________________________________________________________________________________________________________________________
DBMS stores data as file.									|	RDBMS stores data in tabular form.

Data elements need to access individually.							|	Multiple data elements can be accessed at the same time.

no relationship between data.									|	Data is stored in the form of tables which are related to each other.

Normalization is not present.									|	Normalization is present.

DBMS does not support distributed database.							|	RDBMS supports distributed database.

It stores data in either a navigational or hierarchical form.				|	It uses a tabular structure where the headers are the column names, and the rows contain
 corresponding values.										|
It deals with small quantity of data.								|	It deals with large amount of data.

Data redundancy is common in this model.							|	Keys and indexes do not allow Data redundancy.

It is used for small organization and deal with small data.					|	It is used to handle large amount of data.

Not all Codd rules are satisfied.								|	All 12 Codd rules are satisfied.

Security is less										|	More security measures provided.

It supports single user.									|	It supports multiple users.

Data fetching is slower for the large amount of data.					|	Data fetching is fast because of relational approach.

The data in a DBMS is subject to low security levels with regards to data manipulation.	|	There exists multiple levels of data security in a RDBMS.

Low software and hardware necessities.							|	Higher software and hardware necessities.

Examples: XML, Window Registry, Forxpro, dbaseIIIplus etc.					|	Examples: MySQL, PostgreSQL, SQL Server, Oracle, Microsoft Access etc.
______________________________________________________________________________________________________________________________________________________________________________________________________________
3. List the applications of the RDBMS.

    Universities: It is an undeniable application of the database
    Banking: It is one of the major applications of databases. 
    Railway Reservation System: 
    Social Media Sites: 
    Library Management System: 
    E-commerce Websites: 
    Medical: 
    Accounting and Finance:
________________________________________________________________________________________________________________________________________________________________________________________________________    

Data Model
1. What is data model and it's uses.

A data model is a conceptual representation of data that defines how data is organized, stored, and accessed. It is essentially a blueprint or a plan that outlines the structure and relationships of the data. Data models can be used to help users understand the organization of data, to facilitate communication between stakeholders, and to ensure consistency and accuracy of data across different systems and applications.
   
    Designing databases: Data models are used to design the structure of databases, including the tables, fields, and relationships between them.

    Ensuring data consistency: By providing a consistent and structured representation of data, data models help to ensure that data is accurate and consistent across different systems and applications.

    Facilitating communication: Data models provide a common language and framework for discussing and understanding data, which helps to facilitate communication between different stakeholders.

    Supporting software development: Data models can be used to guide the development of software applications that rely on data, helping to ensure that the software works with the data correctly.
________________________________________________________________________________________________________________________________________________________________________________________________________
2. Types of data model in RDBMS.

    Conceptual data model: This is the highest level of abstraction and is used to describe the overall structure and organization of data within an organization. It identifies the main entities, their attributes, and the relationships between them. The conceptual data model is typically used by business analysts and high-level management to get a bird's eye view of the data.

    Logical data model: This is a more detailed model that defines the specific details of the data structures, including tables, columns, primary and foreign keys, and relationships between tables. The logical data model is used by database designers and developers to translate the conceptual model into a database schema.

    Physical data model: This is the lowest level of abstraction and is used to define the specific implementation details of the database on a particular hardware and software platform. It specifies the data types, indexing, storage, and other implementation details. The physical data model is used by database administrators and IT professionals to create, configure, and manage the physical database.
________________________________________________________________________________________________________________________________________________________________________________________________________
3. Advantages and disadvantage of data model.
Advantages:

    Consistency: Data models provide a consistent and standardized representation of data, which makes it easier to manage and maintain the data across different applications and systems.
    Communication: Data models serve as a common language and framework for discussing and understanding data, which facilitates communication between different stakeholders.
    Accuracy: By defining the structure and relationships of data, data models help to ensure that data is accurate and consistent across different applications and systems.
    Scalability: Data models can be designed to support scalability, allowing for the management and analysis of large amounts of data.
    
    
    Disadvantages:

    Complexity: Data models can be complex and difficult to understand, particularly for non-technical stakeholders.
    Rigidity: Data models can be rigid and inflexible, making it difficult to accommodate changes in the data structure or the requirements of the applications that use the data.
    Cost: Developing and maintaining data models can be expensive, particularly for large and complex datasets.
    Technical expertise: Creating and maintaining data models requires technical expertise, which may not be available within an organization.
    
________________________________________________________________________________________________________________________________________________________________________________________________________
ER Model
1. What is er model and it's uses.

An Entity-Relationship (ER) model is a type of data model that represents entities and the relationships between them. It is a graphical representation of entities and their relationships to other entities within a system or application. The ER model uses entities to represent objects or concepts in the real world, and relationships to represent the associations between those objects or concepts.

The ER model has several uses, including:

    Database design: The ER model is used to design databases by identifying the entities and relationships that make up the data. This allows designers to create a database schema that accurately represents the data and its relationships.

    Communication: The ER model provides a visual representation of the data and its relationships, which can be used to communicate with stakeholders, such as business users and developers.

    Analysis: The ER model can be used to analyze the data and its relationships, which can help identify patterns, trends, and relationships that are not immediately apparent.

    Documentation: The ER model can be used as a form of documentation to describe the structure and relationships of the data.
    
________________________________________________________________________________________________________________________________________________________________________________________________________    
2. What is entity, attributes and relationship, list it's types and explain about that.

In an Entity-Relationship (ER) model, an entity is an object or concept in the real world that has properties or attributes and is represented in the database as a table. An attribute is a characteristic or property of an entity, and a relationship is an association between two or more entities.

Types of entities:

    Strong entity: A strong entity is an entity that can exist independently and has its own unique identifier. For example, a customer or an employee in a company can be considered as a strong entity.
    Weak entity: A weak entity is an entity that cannot exist independently and depends on the existence of a strong entity. For example, an order in a company cannot exist without a customer or an employee, so it is considered as a weak entity.

Types of attributes:

    Simple attribute: A simple attribute is an attribute that cannot be further divided or decomposed into smaller attributes. For example, a customer's name or an employee's age can be considered as simple attributes.
    Composite attribute: A composite attribute is an attribute that can be divided or decomposed into smaller attributes. For example, a customer's address can be divided into street, city, and state attributes.
    Derived attribute: A derived attribute is an attribute that is calculated or derived from other attributes. For example, a customer's age can be derived from their date of birth.

Types of relationships:

    One-to-one relationship: A one-to-one relationship is a relationship where each instance of one entity is associated with only one instance of another entity. For example, an employee can have only one office, and an office can be assigned to only one employee.
    One-to-many relationship: A one-to-many relationship is a relationship where an instance of one entity is associated with multiple instances of another entity. For example, a customer can have multiple orders, but an order can be assigned to only one customer.
    Many-to-many relationship: A many-to-many relationship is a relationship where multiple instances of one entity are associated with multiple instances of another entity. For example, a student can enroll in multiple courses, and a course can have multiple students enrolled.

________________________________________________________________________________________________________________________________________________________________________________________________________
3. Advantages of er model

SIMPLE :  It is simple to draw an ER diagram when we know entities and relationships. 
EFFECTIVE : It is an effective communication tool.
EASY TO UNDERSTAND : The design of ER is very logical and hence they are easy  to design and understand.They show database capabilities like how tables, keys and columns are used to find a solution to the given question.
INTEGRATED :  The ER Model can be easily integrated with relational model.
USEFUL IN DECISION MAKING : Since some of the entities in the database are analyzed by an ER-Diagram, So by drawing an ER-Diagram we come to know what kind of attributes and relationship exist between them.
________________________________________________________________________________________________________________________________________________________________________________________________________
4. ER Diagrams Symbols and it's uses


    Rectangles: This Entity Relationship Diagram symbol represents entity types
    Ellipses: This symbol represents attributes
    Diamonds: This symbol represents relationship types
    Lines: It links attributes to entity types and entity types with other relationship types
    Primary key: Here, it underlines the attributes 
    Double Ellipses: Represents multi-valued attributes

________________________________________________________________________________________________________________________________________________________________________________________________________
Relational Model
1. What is relational model.

The relational model in DBMS is an abstract model used to organize and manage the data stored in a database. It stores data in two-dimensional inter-related tables, also known as relations in which each row represents an entity and each column represents the properties of the entity.

________________________________________________________________________________________________________________________________________________________________________________________________________

2. Relational Model components and it's uses.

    Relation : Two-dimensional table used to store a collection of data elements.
    Tuple : Row of the relation, depicting a real-world entity.
    Attribute/Field : Column of the relation, depicting properties that define the relation.
    Attribute Domain : Set of pre-defined atomic values that an attribute can take i.e., it describes the legal values that an attribute can take.
    Degree : It is the total number of attributes present in the relation.
    Cardinality : It specifies the number of entities involved in the relation i.e., it is the total number of rows present in the relation. Read more about Cardinality in DBMS.
    Relational Schema : It is the logical blueprint of the relation i.e., it describes the design and the structure of the relation. It contains the table name, its attributes, and their types:
________________________________________________________________________________________________________________________________________________________________________________________________________
3. Advantages and disadvantages of relational model.

Advantages of Relational Database Model

    Simplicity: A Relational data model in DBMS is simpler than the hierarchical and network model.
    Structural Independence: The relational database is only concerned with data and not with a structure. This can improve the performance of the model.
    Easy to use: The Relational model in DBMS is easy as tables consisting of rows and columns are quite natural and simple to understand
    Query capability: It makes possible for a high-level query language like SQL to avoid complex database navigation.
    Data independence: The Structure of Relational database can be changed without having to change any application.
    Scalable: Regarding a number of records, or rows, and the number of fields, a database should be enlarged to enhance its usability.

Disadvantages of Relational Model

    Few relational databases have limits on field lengths which can’t be exceeded.
    Relational databases can sometimes become complex as the amount of data grows, and the relations between pieces of data become more complicated.
    Complex relational database systems may lead to isolated databases where the information cannot be shared from one system to another.

________________________________________________________________________________________________________________________________________________________________________________________________________
Relational Algebra

1. relational algebra and it's types
Relational algebra is a procedural query language, which takes instances of relations as input and yields instances of relations as output. It uses operators to perform queries. An operator can be either unary or binary. They accept relations as their input and yield relations as their output. Relational algebra is performed recursively on a relation and intermediate results are also considered relations.

The fundamental operations of relational algebra are as follows −

    Select
    Project
    Union
    Set different
    Cartesian product
    Rename

________________________________________________________________________________________________________________________________________________________________________________________________________
2. Explain about joins and it's types
OIN operation is used to combine rows from two or more tables based on a related column between them. The JOIN operation is one of the most powerful features of SQL, and it allows you to retrieve data from multiple tables and display them as a single result set.

There are several types of JOIN operations in SQL, including:

    Inner Join: This is the most common type of join in SQL. It returns only the rows from both tables that have matching values in the join column(s).

    Left Join: This type of join returns all the rows from the left table, and the matched rows from the right table. If there are no matching rows in the right table, the result will contain NULL values for all the right table columns.

    Right Join: This type of join is similar to the left join, but it returns all the rows from the right table and the matched rows from the left table. If there are no matching rows in the left table, the result will contain NULL values for all the left table columns.

    Full Outer Join: This type of join returns all the rows from both tables, and NULL values are used for any unmatched rows in either table.

    Cross Join: This type of join returns the Cartesian product of the two tables, i.e., all possible combinations of rows from both tables. This type of join does not require a join condition.

    Self Join: This type of join is used to join a table with itself. It is useful when you have a table that contains hierarchical data, such as an employee table that has a manager column that references the same table.


________________________________________________________________________________________________________________________________________________________________________________________________________
Relational Calculus
1. Explain about Relational Calculus and it's types.

It is based on Predicate calculus, a name derived from branch of symbolic language. A predicate is a truth-valued function with arguments. On substituting values for the arguments, the function result in an expression called a proposition. It can be either true or false. It is a tailored version of a subset of the Predicate Calculus to communicate with the relational database.

Tuple Relational Calculus (TRC)

It is a non-procedural query language which is based on finding a number of tuple variables also known as range variable for which predicate holds true. It describes the desired information without giving a specific procedure for obtaining that information. The tuple relational calculus is specified to select the tuples in a relation. In TRC, filtering variable uses the tuples of a relation. The result of the relation can have one or more tuples.


2. Domain Relational Calculus (DRC)

The second form of relation is known as Domain relational calculus. In domain relational calculus, filtering variable uses the domain of attributes. Domain relational calculus uses the same operators as tuple calculus. It uses logical connectives ∧ (and), ∨ (or) and ┓ (not). It uses Existential (∃) and Universal Quantifiers (∀) to bind the variable. The QBE or Query by example is a query language related to domain relational calculus.
________________________________________________________________________________________________________________________________________________________________________________________________________


Constraints
1. List out the constraints and explain about them.

Constraints in DBMS are the restrictions that are applied to data or operations on the data. This means that constraints allow only a particular kind of data to be inserted in the database or only some particular kind of operations to be performed on the data in the database.

Types of Constraints in DBMS

In relational databases, there are mainly 5 types of constraints in DBMS called relational constraints. They are as follows:

    Domain Constraints
    Key Constraints
    Entity Integrity Constraints
    Referential Integrity Constraints
    Tuple Uniqueness Constraints
    
    Key Constraint in DBMS

    As the name suggests, this is a constraint applied on an attribute that we consider to be a primary key. So, the conditions for a primary key in a table is in fact this constraint.
    So, we know that a primary key cannot be null.
    Also, a primary key must be unique.

Entity Integrity Constraint in DBMS

    This is the same as the Key constraint. In fact, it is just a subset of the Key constraint.
    The key constraint states that the Primary Key attributes should be unique and must not contain null values.
    However, Entity Integrity Constraint states that any attribute of a Primary key must not be null.
    The perspective that this constraint holds is that if null values are allowed in the Primary key attributes, then there can be multiple null values. Hence, the constraint of a Primary Key being unique for every tuple will be violate
    
    
    
    Referential Integrity Constraint in DBMS

    Referential integrity is a database concept that ensures the consistency and accuracy of data between related tables. It is maintained through the use of primary and foreign key.
    Referential integrity constraint is applied when a foreign key references the primary key of our table.
    This constraint can be summarized in one line i.e. the referencing attribute must be the subset of referred attribute.
    This means that a record or a tuple cannot be inserted in the referencing relation if it is not present in the referenced relation.
    Also, any record that is present in the referencing relation cannot be updated or deleted from the referenced relation.



Domain Constraints in DBMS

    The domain means a range of values. In mathematics, the concept of Domain means the allowed values for a function.

    Similarly, in DBMS, the Domain Constraint specifies the domain or set of values.

    This is a constraint applied to attributes, not tuples. This means that it defines what values are allowed to be kept inside a particular column (attribute) for a table.

    The domain constraint specifies that the value of an attribute must be an atomic value in its own domain.


________________________________________________________________________________________________________________________________________________________________________________________________________



2. Why constraints is required in RDBMS.

Constraints are required in RDBMS (Relational Database Management Systems) to maintain the accuracy, consistency, and integrity of the data in a database. Constraints enforce rules on the data that is being entered or updated, and prevent the insertion of invalid data into a table. Here are some reasons why constraints are essential in RDBMS:

    Data Integrity: Constraints ensure that the data being entered into a database is valid and accurate. For example, a primary key constraint ensures that each record in a table is unique, while a not null constraint ensures that a column(s) cannot contain null values. Constraints prevent the insertion of invalid or incomplete data, which helps to maintain the integrity of the database.

    Data Consistency: Constraints enforce rules on the data being entered or updated, which helps to ensure that the data is consistent across different tables. For example, a foreign key constraint links two tables together and ensures that the values in the referencing column(s) match the values in the referenced primary key column(s). This maintains consistency between the two tables, which helps to prevent data anomalies and inconsistencies.

    Data Security: Constraints can be used to enforce security rules on the data being entered or updated. For example, a check constraint can be used to ensure that a user enters a valid password when creating an account. Constraints help to prevent unauthorized access to the data, and protect the integrity of the database.
    
    
    ________________________________________________________________________________________________________________________________________________________________________________________________________


Functional Dependency ( Including Normalization forms )

1. What is Functional Dependency
The functional dependency is a relationship that exists between two attributes. It typically exists between the primary key and non-key attribute within a table.

    X   →   Y  

The left side of FD is known as a determinant, the right side of the production is known as a dependent. 

________________________________________________________________________________________________________________________________________________________________________________________________________
2. Rules of Functional Dependencies

    Reflexivity: If Y is a subset of X, then X→Y holds by reflexivity rule
    For example, {roll_no, name} → name is valid.
    Augmentation: If X → Y is a valid dependency, then XZ → YZ is also valid by the augmentation rule.
    For example, If {roll_no, name} → dept_building is valid, hence {roll_no, name, dept_name} → {dept_building, dept_name} is also valid.→
    Transitivity: If X → Y and Y → Z are both valid dependencies, then X→Z is also valid by the Transitivity rule.
    For example, roll_no → dept_name & dept_name → dept_building, then roll_no → dept_building is also valid.
    
    
    ________________________________________________________________________________________________________________________________________________________________________________________________________
    
3. Types of Functional Dependencies and explain those

    Trivial functional dependency
    Non-Trivial functional dependency
    Multivalued functional dependency
    Transitive functional dependency

1. Trivial Functional Dependency

In Trivial Functional Dependency, a dependent is always a subset of the determinant.
i.e. If X → Y and Y is the subset of X, then it is called trivial functional dependency


2. Non-trivial Functional Dependency

In Non-trivial functional dependency, the dependent is strictly not a subset of the determinant.
i.e. If X → Y and Y is not a subset of X, then it is called Non-trivial functional dependency.

3.Multivalued Functional Dependency

In Multivalued functional dependency, entities of the dependent set are not dependent on each other.
i.e. If a → {b, c} and there exists no functional dependency between b and c, then it is called a multivalued functional dependency.

4. Transitive Functional Dependency

In transitive functional dependency, dependent is indirectly dependent on determinant.
i.e. If a → b & b → c, then according to axiom of transitivity, a → c. This is a transitive functional dependency  

________________________________________________________________________________________________________________________________________________________________________________________________________
4. What is Normalization


    Normalization is the process of organizing the data in the database.
    Normalization is used to minimize the redundancy from a relation or set of relations. It is also used to eliminate undesirable characteristics like Insertion, Update, and Deletion Anomalies.
    Normalization divides the larger table into smaller and links them using relationships.
    The normal form is used to reduce redundancy from the database table.
    
    ________________________________________________________________________________________________________________________________________________________________________________________________________
   


5. What is Anomalies.

The term anomaly is used to describe a discrepancy between two parts of a database. In a retail database, for example, you may have a customer and an invoice table. If you are no longer selling to customers, you may want to purge them from your database periodically.
.
________________________________________________________________________________________________________________________________________________________________________________________________________
6. How are Anomalies Caused in DBMS

Poorly constructed tables in a database are often the reason behind anomalies. How do you define "poor construction"? A poorly designed table becomes apparent if, when a designer is creating the database, he fails to identify the entities which are interdependent, such as rooms of a hostel and the hostel, and then minimizes the chances of an entity being independent of another.

________________________________________________________________________________________________________________________________________________________________________________________________________

7. Type of Anomalies  and explain those.

Type of Anomalies in DBMS

There are different types of anomalies that can occur in a database. Redundancy anomalies, for instance, can cause problems during tests if you are a student, and during job interviews, if you are looking for work. However, they are easily spotted and fixed. These are the ones we need to pay attention to:

    Update
    Insert
    Delete

1. Update anomaly:

Consider a college database that keeps student information in a table called student, which contains four columns: stu_id for the student's id, stu_name for the student's name, stu_address for the student's address, and stu_club for the student's club. Eventually, the table will appear as follows:

2. Insert anomaly.
If there is a new row inserted in the table and it creates the inconsistency in the table then it is called the insertion anomaly. For example, if in the above table, we create a new row of a worker, and if it is not allocated to any department then we cannot insert it in the table so, it will create an insertion anomaly.

3.Deletion Anomaly

If we delete some rows from the table and if any other information or data which is required is also deleted from the database, this is called the deletion anomaly in the database. For example, in the above table, if we want to delete the department number ECT669 then the details of Rajesh will also be deleted since Rajesh's details are dependent on the row of ECT669. So, there will be deletion anomalies in the table.
________________________________________________________________________________________________________________________________________________________________________________________________________
8. How to prevent Anomalies.

To prevent anomalies you need to normalise the database by efficiently organising the data in a database. According to Edgar F Codd, the inventor of relational databases, the goals of normalisation include: removing all redundant (or repeated) data from the database.

________________________________________________________________________________________________________________________________________________________________________________________________________
9. List the types of Normalization and explain those.

 Normal Form 	Description
1NF 	A relation is in 1NF if it contains an atomic value.
2NF 	A relation will be in 2NF if it is in 1NF and all non-key attributes are fully functional dependent on the primary key.
3NF 	A relation will be in 3NF if it is in 2NF and no transition dependency exists.
BCNF 	A stronger definition of 3NF is known as Boyce Codd's normal form.
4NF 	A relation will be in 4NF if it is in Boyce Codd's normal form and has no multi-valued dependency.
5NF 	A relation is in 5NF. If it is in 4NF and does not contain any join dependency, joining should be lossless.

________________________________________________________________________________________________________________________________________________________________________________________________________

10. What is the use of Normalization in RDBMS.

The main reason for normalizing the relations is removing these anomalies. Failure to eliminate anomalies leads to data redundancy and can cause data integrity and other problems as the database grows. Normalization consists of a series of guidelines that helps to guide you in creating a good database structure.
________________________________________________________________________________________________________________________________________________________________________________________________________
Decomposition and its types
1. What is decomposition

   Decomposition is the process of breaking an original relation into multiple sub relations. Decomposition helps to remove anomalies, redundancy, and other problems in a DBMS. Decomposition can be lossy or lossless. An ideal decomposition should be lossless join decomposition and dependency preserving..
   ________________________________________________________________________________________________________________________________________________________________________________________________________
2. Rules of decomposition



    The union of attributes of both the sub relations R1 and R2 must contain all the attributes of original relation R.

    R1 ∪ R2 = R

    The intersection of attributes of both the sub relations R1 and R2 must not be null, i.e., there should be some attributes that are present in both R1 and R2.

    R1 ∩ R2 ≠ ∅

    The intersection of attributes of both the sub relations R1 and R2 must be the superkey of R1 or R2, or both R1 and R2.

    R1 ∩ R2 = Super key of R1 or R23
    
    Lossless Join Decomposition Rule: If a relation R is decomposed into two relations R1 and R2, then the join of R1 and R2 should produce the original relation R. This rule ensures that there is no loss of information during the decomposition process.

    Dependency Preservation Rule: If a functional dependency F holds in a relation R, then it should hold in every relation resulting from the decomposition of R. This rule ensures that the functional dependencies are preserved even after decomposition.

    Boyce-Codd Normal Form (BCNF) Decomposition Rule: If a relation R contains a non-trivial functional dependency A → B, then R should be decomposed into two relations R1(A, B) and R2(A, C) where C is the set of all attributes in R that are not functionally dependent on A. This rule ensures that every non-trivial functional dependency in R is reflected in the decomposition.

    Third Normal Form (3NF) Decomposition Rule: If a relation R contains a non-trivial functional dependency A → B and B is not a candidate key, then R should be decomposed into two relations R1(A, B) and R2(A, C) where C is the set of all attributes in R that are not functionally dependent on A. This rule ensures that all non-key attributes are functionally dependent on the primary key.
________________________________________________________________________________________________________________________________________________________________________________________________________
3. Explain the types of decomposition 
Lossless Decomposition

    If the information is not lost from the relation that is decomposed, then the decomposition will be lossless.
    The lossless decomposition guarantees that the join of relations will result in the same relation as it was decomposed.
    The relation is said to be lossless decomposition if natural joins of all the decomposition give the original relation.


Dependency Preserving

    It is an important constraint of the database.
    In the dependency preservation, at least one decomposed table must satisfy every dependency.
    If a relation R is decomposed into relation R1 and R2, then the dependencies of R either must be a part of R1 or R2 or must be derivable from the combination of functional dependencies of R1 and R2.
    For example, suppose there is a relation R (A, B, C, D) with functional dependency set (A->BC). The relational R is decomposed into R1(ABC) and R2(AD) which is dependency preserving because FD A->BC is a part of relation R1(ABC).
________________________________________________________________________________________________________________________________________________________________________________________________________

