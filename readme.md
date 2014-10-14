PostgreSQL -- Simple framework para PostgreSQL con funciones preparadas.
<hr>
### Tabla de Contenidos
**[Instalación](#instatalación)**  

### Instalación
Para utilizar esta clase debe cargarla -si no tiene definido un autoload- con la sintáxis correspondiente.

```php
require_once ('PostgreSQLdb.class.php');
```

Posterior a eso, debe crear una nueva instancia y configurar los datos de acceso a la misma.

```php
$db = new MysqliDb ('host', 'username', 'password', 'databaseName');
```

También es posible configurar un prefix para sus tablas,
```php
$db->setPrefix ('my_');
```

Luego, prepara tus datos, y llama a los métodos necesarios.
