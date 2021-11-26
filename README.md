# Laravel

### Comandos para Laravel

_Para crear un nuevo proyecto:_
```
composer create-project laravel/laravel projectname
```

_Para poder ver tu pagina:_
```
 php artisan serve
```

_Crear un nuevo modelo:_
```
 php artisan serve make:model Author -mcr
```
- m: crea la migracion
- c: crea el controlador
- r: crea la relación entre todo eso

_Ejecutar las migraciones:_
```
 php artisan migrate
```

_Guarda la fecha de migracion de una tabla:_
```
$table->date('created_at');
```
