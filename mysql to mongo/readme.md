
##use


```
    python script.py --sql-host hostname --sql-user username --sql-password password --sql-db databasename --mongo-url mongodb+srv://username:password@cluster-url/database --mongo-db mongodatabasename 
 ```
```
   python script.py --sql-host=sql.example.com --sql-user=user --sql-password=secret --sql-db=database --mongo-url=mongodb://mongodb.example.com:27017/ --mongo-db=mongo_database_name
```

##use with limit
<pre>
  <code id="code">
python script3.py --sql-host=sql.example.com --sql-user=user --sql-password=secret --sql-db=database --mongo-url=mongodb://mongodb.example.com:27017/ --mongo-db=mongo_database_name --timeout=60 --limit=1000

  </code>
</pre>

This would run the script with sql.example.com as the hostname for the SQL database, user as the username for the SQL database, secret as the password for the SQL database, database as the name of the SQL database, mongodb://mongodb.example.com:27017/ as the URL for the MongoDB database, and mongo_database_name as the name of the MongoDB database. The script would also have a timeout of 60 seconds and a limit of 1000 rows per table. Note: you will need to add the --timeout and --limit argument parsing to the code for it to work.