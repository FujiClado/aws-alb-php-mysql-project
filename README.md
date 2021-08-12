#### Database Setup

```sh

########################################################################
Example Databse
########################################################################

create database college;
use college;

########################################################################
Example table
########################################################################

CREATE TABLE students(
name VARCHAR(20) NOT NULL,
age INT(3) NOT NULL,
email VARCHAR(30) NOT NULL
);

########################################################################
Example table content
########################################################################
INSERT INTO students(name,age,email) VALUES('kevin',20,'kevin@gmail.com');
INSERT INTO students(name,age,email) VALUES('sam',24,'sam@gmail.com');
INSERT INTO students(name,age,email) VALUES('john',23,'john@gmail.com');
INSERT INTO students(name,age,email) VALUES('jane',25,'jane@gmail.com');
INSERT INTO students(name,age,email) VALUES('devon',23,'devon@gmail.com');
INSERT INTO students(name,age,email) VALUES('nelson',22,'nelson@gmail.com');
INSERT INTO students(name,age,email) VALUES('ron',26,'ron@gmail.com');
INSERT INTO students(name,age,email) VALUES('jenna',23,'jenna@gmail.com');
INSERT INTO students(name,age,email) VALUES('julia',22,'julia@gmail.com');
INSERT INTO students(name,age,email) VALUES('emma',21,'emma@gmail.com');

```
#### Changing Database Connection Variables

```sh

# vim index.php

<?php
  
// Database Connection

$user = 'root';         
$password = 'mysqlroot123'; 
$database = 'college'; 
$servername='localhost:3306';

```






```sh

# vim index.html

<head>
    <meta charset="UTF-8">
    <title>This Version 1</title>
    <!-- CSS FOR STYLING THE PAGE -->
```
#### Changing Version
#
#


```sh

# vim index.php

<head>
    <meta charset="UTF-8">

    <title>This Version 1</title>  <<==========
    <style>
        table {
            margin: 0 auto;
            font-size: large;
            border: 1px solid black;
        }
```
