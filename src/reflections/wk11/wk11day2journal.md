What is the difference between a primary key and a foreign key?

Primary key is used to identify data uniquely. It can't be null. Foreign key is used to maintain relationship between two tables

What is an Alias?

SQL aliases are used to give a table, or a column in a table, a temporary name.


Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

I'm honestly not sure how to do this at the moment...

https://github.com/KalebMcElyea/contractor