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

## gunakan req.body dan req.params

| Verb    | Path          | Keterangan           |
| ------- | ------------- | -------------------- |
| GET     | /students     | Listing students     |
| POST    | /students     | Create new student   |
| GET     | /students/:id | Get certain student  |
| PUT     | /students/:id | Edit student         |
| DELETE  | /students/:id | Delete Student       |

### Hint:
- put: const i = findindex(untuk id), lalu data[i].name = req.body.name
- delete: pakai built in function .splice

### rules:
- duedate: Minggu
- cara pengumpulan: biasa di drive, di folder masing2, buat folder challenge-2, baru masukin project nya, zip workspace/projectnya (jangan lupa di zip/rar ya). lalu node_module nya tidak perlu dikumpulkan.
