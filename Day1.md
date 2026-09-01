GCP Engineering Sql Day 1
====================================

what is the importance of the database for cloud data engineer?

As a Cloud Data engineer every day we are going to deal with "DATA"

Where this Data will present ? --> database / servers

.txt files
.xml files
.json files
.csv files 
.parquet files
.avro files
.sequence files 

All about files will act as source files and target files 
but most of the times these files will act as source files


.csv files (source) --> .parquest files (staging area) --> database system/dwh system/big table (no sql database)

if we are going to have data in file format --> it would be difficult to perform analytics on this data
-->

in tabular format difficult analysis data   

so by the top of the tabular format we can easily converting the report format in this report format easily convert the analysis dashboard 

*********************************************************
.file ----> Tabular format (Database/dwh/nosqldb) ---> report ---> Analysis (end users)

Reporting tools 
===========================
Congno
Tableua
qqickview/powerbi --> All these reporting tools will work very  efficiently when we are giving data in tabular format (views)


retrieve the data from the tables --> SQl queries 
***************************************************
In Real  time 
1.Might be you need to build SQL queries from Scratch
2.Migh be you need to change exiting sql queries based on business requirement ?

*******************************************************************

Database? **
Database is nothing collection of different database which we are using for the purpose of storing and maintaining the data.


type database objects?
1.Tables [store the data]
2.Views [ not store the data, virtual table]
3.Triggers
4.Stored procedures 

------------------------------------------------------------
What is table ? **
  --> Table is thing but collecting of rows and columns
----------------------------------------------------------------

Row : it is a [record] --> which contain actual information
   ---> This is instance of the object 

object is kind of a real time value [person, customer, employ ,products
----------------------------------------------------------------

Column: it nothing but value of the row and characteristic or features of the object
To know the meaning of the Rows --> we need to define the columns



_____________________________________________________________________

in the real time project who is going to create these tables ?
1.DBA
2.Cloud data engineer

if you want to create the table what kind of input we need to get?

schema --> structure --> 

Table name 
Column names
Datatypes of the columns
Datatype length of the columns 
Constraints of the table


From where we will get all above details ?
In physical data model document (PDM document) --- > .pdf

who will give the PDM document in real time 
Data modeler


what all are the prerequisite to create PDM document as a datamodeller?

Understand business requirements 

from where will get the business reequipments?

in BRS document (Business Requirement specification document) --> .word /.pdf

who will create BRS document ?
BA --> Business analyst
DA --> data analyst




after the loading the data we ill get he DIS 
