This is simple database orm for sqlite3

```
db = Sqlite3View("path/to/db.sqlite3")

table = db.table_name

#filtering datas

datas = table(key=value)


#getting datas by id
data = table[id]


#update data value
data.update(key=value)


#delete value
data.delete()
del table[id]

#create data

table.create(key=value, key2 = value2, key3 = value3)

#clear table data

table.clear()



#delete table
table.delete()
del db.table_name```


for bugs report me

komiljonovshukurullox@gmail.com

https://t.me/komiljonov1109
