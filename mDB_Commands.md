## Commands
## 1. How to show DB
- show dbs
## 2. To switch the DB
- use DB-name
## 3. To Create Collections 
- db.createCollection("employes")
- db.createCollection("sudheer")
## 4. How to show the collections 
- show collections
## 5. How to drop/delete collection/table
- db.collection-name.drop()
- **Example :** db.sudheer.drop() 
## Example of CLI How to drop/delete collection/table
```t
> show dbs
admin    0.000GB
config   0.000GB
local    0.000GB
sudheer  0.000GB

> use sudheer
switched to db sudheer
> show collections
pay
students

> db.pay.drop()
true
> show collections
students
> db.student.drop()
false
> db.students.drop()
true
>

```
## 6. How to drop Database ?
- db.dropDatabase() 
- no need to give DB name, Current Database will be deleted 
- when you need to drop a DB you need to switch that DB first then only you can drop the current DB
- **Example :**  db.dropDatabase()
```t
> show dbs
admin   0.000GB
config  0.000GB
local   0.000GB
> db.dropDatabase()
{ "dropped" : "sudheer", "ok" : 1 }
>
```

