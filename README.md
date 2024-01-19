create database hrapp;
use hrapp;

CREATE TABLE employee (
    Id int NOT NULL AUTO_INCREMENT,
    FirstName varchar(255),
    LastName varchar(255),
    Email varchar(255),
    Address varchar(255),
    PRIMARY KEY (Id)
);

INSERT INTO employee (Id, FirstName, LastName, Email, Address)
VALUES 
    (101, 'John', 'Doe', 'john.doe@email.com', '123 Main St'),
    (102, 'Jane', 'Smith', 'jane.smith@email.com', '456 Oak Ave'),
    (103, 'Bob', 'Johnson', 'bob.johnson@email.com', '789 Pine Rd'),
    (104, 'Alice', 'Williams', 'alice@email.com', '101 Maple Ln'),
    (105, 'Charlie', 'Brown', 'charlie.brown@email.com', '555 Elm St'),
    (106, 'Eva', 'Martinez', 'eva.martinez@email.com', '909 Cedar Blvd');
