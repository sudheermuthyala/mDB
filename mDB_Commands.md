## Commands
## How to show DB
- show dbs
## To switch the DB
- use DB-name
## To Create Collections 
- db.createCollection("employes")
- db.createCollection("sudheer")
## How to show the collections 
- show collections
## How to drop/delete collection/table
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
## How to drop Database ?
- db.dropDatabase() 
- no need to give DB name, Current Database will be deleted 
- **Example :**  db.dropDatabase()
