# Tables-creation-and-Data-insertion


CREATE DATABASE Company;
USE Company;

CREATE TABLE Employees (
    Emp_ID INT PRIMARY KEY,
    Emp_Name VARCHAR(50),
    Department VARCHAR(30),
    Salary INT,
    City VARCHAR(30)
);

INSERT INTO Employees VALUES
(101, 'Shahrukh', 'IT', 65000, 'Lucknow'),
(102, 'Aman', 'HR', 45000, 'Delhi'),
(103, 'Rahul', 'IT', 80000, 'Noida'),
(104, 'Priya', 'Finance', 70000, 'Mumbai'),
(105, 'Tanya', 'HR', 55000, 'Delhi'),
(106, 'Arjun', 'IT', 90000, 'Bangalore'),
(107, 'Neha', 'Finance', 60000, 'Pune'),
(108, 'Vikas', 'Sales', 50000, 'Lucknow'),
(109, 'Simran', 'Sales', 75000, 'Delhi'),
(110, 'Karan', 'IT', 72000, 'Noida');


CREATE TABLE Projects (
    Project_ID INT PRIMARY KEY,
    Project_Name VARCHAR(50),
    Emp_ID INT,
    Project_Budget INT,
    Status VARCHAR(20)
);

INSERT INTO Projects VALUES
(201, 'Cloud Migration', 101, 150000, 'Completed'),
(202, 'Recruitment Portal', 102, 80000, 'Completed'),
(203, 'Data Analytics', 103, 200000, 'Ongoing'),
(204, 'Financial Dashboard', 104, 120000, 'Ongoing'),
(205, 'HR Automation', 105, 90000, 'Ongoing'),
(206, 'AI Platform', 106, 300000, 'Ongoing'),
(207, 'Sales Dashboard', 108, 70000, 'Completed'),
(208, 'Customer Analytics', 109, 180000, 'Ongoing'),
(209, 'Database Upgrade', 110, 160000, 'Completed');
