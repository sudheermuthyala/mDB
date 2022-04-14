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
## MongoDB Drivers
From Application (java,c#,Python Etc) we want to communicate with Datebase,some special software must be required, Which is nothing but Driver Software.

## session-3

## Default Databases in MongoDB
1. **admin : **  
   - Admin Data base is used to store user authentication and Authorization information like username,password,role etc
   - This Database isused by administrators while `creating,deleting,and updating` the users and while assigning roles
2. **config : ** 
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
2. BSON required less memory **If Json-->10KB, But BSON-->5KB**

    






