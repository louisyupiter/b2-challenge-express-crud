# Let's make CRUD (Create Read Update Delete) application! :)
 
```json
[
	{
		"id": 1,
		"name": "Alpha",
		"score": 100,
		"class": "satu"
	},
	{
		"id": 2,
		"name": "Beta",
		"score": 76,
		"class": "dua"
	},
	{
		"id": 3,
		"name": "Charlie",
		"score": 92,
		"class": "tiga"
	},
	{
		"id": 4,
		"name": "Delta",
		"score": 71,
		"class": "satu"
	},
	{
		"id": 5,
		"name": "Echo",
		"score": 80,
		"class": "tiga"
	}
]
```

data json diatas contoh datanya aja.
jadi nanti pas kalian input bentuk di databasenya seperti itu.
hiraukan id, karena id terbuat otomatis.
buat aja schema student punya name, score, class.

## gunakan req.body dan req.params

| Verb    | Path          | Keterangan           | Hint                 |
| ------- | ------------- | -------------------- | -------------------- |
| GET     | /students     | Listing students     | find()               |
| POST    | /students     | Create new student   | create()             |
| GET     | /students/:id | Get certain student  | findbyid()           |
| PUT     | /students/:id | Edit student         | findbyidandupdate()  |
| DELETE  | /students/:id | Delete Student       | findbyidanddelete()  |

### Hint:
pake mongoose aja karena udah belajar mongoosejs hari ini
get, find()
post, create()
get, findbyid()
put, findbyidandupdate()
delete, findbyidanddelete()

### rules:
- cara pengumpulan: zip workspace/projectnya (jangan lupa di zip/rar ya). lalu node_module nya tidak perlu dikumpulkan.
