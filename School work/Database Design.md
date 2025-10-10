10/09/2025
**Enhanced Entity Relationship Model**
This includes all modelling concepts that the ER model may not have captured. i.e.;
Specialization
Generalization
Relationships(Disjoint, Overlap, total and partial participation)
Categorization
Inheritance

Focus on the Business rules, min value, max value and the grammar

**Specialization**-Process of defining a set of subclass of an entity type. Top-down process of conceptual refinement.
Super class- entity type that represents a general concept at a high level.
Sub class-represents specific concepts at lower level
Subclass inherits from a superclass. When a subclass inherits from one or more super classes, it inherits all attributes. It can also define its own specific attributes.
Inheritance-Sub class gains attributes from superclass.

Relationships
O=disjoint-Entity from superclass can belong to only one subclass.
D=overlapping-Same entity may be a member of more than one subclass.

**Generalization**- Reverse process of specialization. Bottom-up process.
**Categorization**- A category is a subclass that has several possible super classes.
Inheritance- Sub class inherits from the parent all its attributes. 

18/9/2025
SQL-Structured Query Language
DDL- define, create, modify(alter)
DML(Data Manipulation Language)- insert, update, delete, merge
DCL-Authentication, Priviledges (Grant, Revoke, Roles(Clustered priviledges to users))

Creating a table
Need to have create table priviledge and storage space
Specify data types, attributes, constraints
