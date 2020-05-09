#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [MongoDB & Mongoose](https://JoelMWatson.github.io/reading-notes/class-03-reading)

#

## Class 03 Reading: MongoDB & Mongoose

#### Why would a developer choose to make data models?

Developers should choose to make data models because they ensure that the data being saved is valid and consistent.

#### What purpose do CRUD operations serve?

CRUD operations serve the purpose of Creating, Reading, Updating, and Deleting data.

#### What kind of database is Postgres? What kind of database is MongoDB?

PostgreSQL database is a Relational Database Management System (RDBMS) with rows and columns where as MongoDB is a NoSQL Database that uses documents to represent records.

#### What is Mongoose and why do we need it?

Mongoose is an ODM (Object Document Mapper) which maps our objects to document records in the database. Sequelize is the PostgreSQL ORM (Object Relational Mapper).

#### Define three related pieces of data in a possible application. An example for a store application might be Product, Category and Department. Describe the contraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.

Objects: Students, Teachers School;

- School to Teachers would be a one to many relationship related by the id of the school the teacher works at.
- Students to Teachers would again be a one to many relationshop related by the id of the teacher whos class the student was in.
- Finaly, School to Students would also be a one to many relationshop related by the id of the school.
