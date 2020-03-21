# Class 03 Reading

#### 1. Why would a developer choose to make data models?

Developers should choose to make data models because they ensure that the data being saved is valid and consistent.

#### 2. What purpose do CRUD operations serve?

CRUD operations serve the purpose of Creating, Reading, Updating, and Deleting data.

#### 3. What kind of database is Postgres? What kind of database is MongoDB?

PostgreSQL database is a Relational Database Management System (RDBMS) with rows and columns where as MongoDB is a NoSQL Database that uses documents to represent records.

#### 4. What is Mongoose and why do we need it?

Mongoose is an ODM (Object Document Mapper) which maps our objects to document records in the database. Sequelize is the PostgreSQL ORM (Object Relational Mapper).

#### 5. Define three related pieces of data in a possible application. An example for a store application might be Product, Category and Department. Describe the contraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.

Objects: Students, Teachers School;
- School to Teachers would be a one to many relationship related by the id of the school the teacher works at.
- Students to Teachers would again be a one to many relationshop related by the id of the teacher whos class the student was in.
- Finaly, School to Students would also be a one to many relationshop related by the id of the school.