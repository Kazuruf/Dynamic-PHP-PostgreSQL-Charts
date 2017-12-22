Dynamic Charts with PHP and PostgreSQL Database
===

Steps to run the sample:
---

* Import` database dump to your PostgreSQL database.
+ Update connection string variables for database host, database port, database name, postgres database username and password in `index.php`.
	+ Please make sure you have enabled `extension=php_pdo_pgsql.dll` and `extension=php_pgsql.dll` in your `php.ini` configuration file.

```
$host= "host="; // database host name
$port= "port="; // postgres database port
$dbname="dbname="; // name of database
$dbuser="user="; // postgres database user
$dbpwd="password="; // postgres database user password
```
+ Run `index.php`.
