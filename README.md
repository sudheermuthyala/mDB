## MongoDB

```t
- Physical Database contain several Logical/Virtual Databases --> Collections --> Documents/record 
- Logical/Virtual Databases contain several Collections
- Collections/Table Conntains Several Documents/Records
```
## MongoDb Shell VS MongoDB sever
- once we install mongoDB we will get  MongoDB shell & MongoDB Server this are JAVA scripted based Applications.

## What is the Role for MongoDb Server
- MongoDB Server is responsible for Store/Manage our Data in Database.

## What is the Role for MongoDb Shell
- MongoDB Shell is responsible to manage Server. 
- By using  this shell  we can perform All requried CRUD Operations 
## What is a CRUD
```t
    C ---> CREATE
    R ---> RETRIEVE
    U ---> UPDATE
    D ---> DELETE
```
## What is Remote/Local server
- MongoDB server can be either Local or remote.
- Using MongoDB shell we can connect mongoDB server(Local or Remote) and perform required operations 

## MongoDB Commands
```t
1. To Start/Launch  MongoDB Server ------>  **mongod** Command
2. To Start/Launch  MongoDB Shell  ------>  **mongo** Command


```
## Creating Data Directory
- cretate a directory in c:\\data\\db\\
- mongod --dbpath "c:\data\db"
## MongoDB Drivers
From Application (java,c#,Python Etc) we want to communicate with Datebase,some special software must be required, Which is nothing but Driver Software.

## session-3

## Default Databases in MongoDB
1. **admin :**  
   - Admin Data base is used to store user authentication and Authorization information like username,password,role etc
   - This Database isused by administrators while `creating,deleting,and updating` the users and while assigning roles
2. **config :** 
   - To Store the Configuration information of MongoDb server.
3. **Local :** 
   - Local Database can be used by Admini while performing replication process

## Data Formates in MongoDB

1. **json :** {"Nmae" : "Muthyala Sudheer Naidu"} This Json will be Converted in to BSON Befor storing. And that BSON will be stored
2. **BSON :** Binary Json 
    - End user/Developer will provide the data in Json form.
    - In MongoDb it will Stored in BSON form. 
**NOTE :** 
1. In javascript only 6 data Types are avillable **`String,Number,Object,Array,Boolean,Null`**. but BSON provides some extra types also like **`32-Bit integer NumberInt,Object,Date,etc`**
2.  Efficent storage and Extra data types are  speciality of BSON over JSON
3. BSON required less memory **If Json-->10KB, But BSON-->5KB**
## Retriving The Data
1. AT the time of retriv operation if i show **BSON** Directley then it is the probleam, If i show **JSON** then again it is the probleam. BSON have some extra DataTypes those Data Types are not supported by Json for example **`32-Bit integer NumberInt,Object,Date,etc`**
2. At the Time of retrivel some support must be required, some Human understandable form is required for the BSON
3. That HumanUnderstandable Form is **EJSON**(EXTENDED JSON)
4. At the time of Retrival BSON will converted to EJSON Form Understanding Purpose
5. Insertion of Docment/Creation---> **JSOM** to **BSON**
6. Read Operation/Retrieval Operation **BSON** to **EJSON**

## What are the data formats used in MongoDB ?
1. JSON
2. BSON
3. EJSON

## Creation of Database and Collection
1. Database won't be created at the beginning and it will be created Dynamically.
2. When ever we are creating collection or inserting Document Then database will be created Dynamically

## How to create Collection/table ?
- db.createCollection("NAME_OF_THE_COLLECTION/table")
- db.createCollection("sudheer")
- db.createCollection("student")

## How to show the collections ?
- show collections
- [Command](https://github.com/sudheermuthyala/mDB/blob/main/mDB_Commands.md)

## How to use DB 
- use sudheer (Hear sudheer is a database name and use command will swithch to sudheer DB)
- it's always going to talk with current Database 

## NOTE: 
- when we need to create a db first we need to use command `use` command `EX: use sudheer` this will not not create any DB visually, When ever we are creating collection or inserting Document Then database will be created Dynamically


## Basic CRED operations


    






