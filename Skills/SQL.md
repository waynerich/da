Structured Query Language
Installing MySQL - https://dev.mysql.com/downloads/installer/
    General Availability (GA) Releases - Select Version - Select Operating System - mysql-installer-community-x.x.xx.{pkg}


|                      |                                  |
| -------------------- | -------------------------------- |
| CREATE DATABASE      |                                  |
| CREATE TABLE         |                                  |
| INSERT INTO - VALUES |                                  |
| SELECT               | output columns                   |
| SELECT DISTINCT      | output unique values in a column |


**Data Definition Language (DDL)**
CREATE DATABASE db_name;
USE db_name;
CREATE TABLE table_name (
    field_name data_type constraint(s)
);
INSERT INTO table_name (field_name(s))
VALUES (value1);

**Data Query Language (DQL)**
SELECT