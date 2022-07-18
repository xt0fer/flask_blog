# flask blog

Wow!

To seed the database...

```
python init_db.py
```

To get it running...

```
export FLASK_APP=app
flask run
```

### Dump sqlite3

```
sqlite> .output kristofer.sql
sqlite> .dump
sqlite> .exit
```

### Load db

```
.read kristofer.sql
```

