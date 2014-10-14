PostgreSQL -- Simple PostgreSQL wrapper with prepared statements
<hr>
### Table of Contents
**[Initialization](#initialization)**  

### Initialization
To utilize this class, first import MysqliDb.php into your project, and require it.

```php
require_once ('MysqliDb.php');
```

After that, create a new instance of the class.

```php
$db = new MysqliDb ('host', 'username', 'password', 'databaseName');
```

Its also possible to set a table prefix:
```php
$db->setPrefix ('my_');
```

Next, prepare your data, and call the necessary methods. 
