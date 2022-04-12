## MongoDB

```t
- Physical Database             --> contain several Logical/Virtual Databases --> Collections --> Documents/record 
- Logical/Virtual Databases     --> contain several Collections
- Collections/Table             --> Conntains Several Documents/Records
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
## MongoDB Driver

From Application (java,c#,Python Etc) we want to communicate with Datebase,some special software must be required, Which is nothing but Driver Software.