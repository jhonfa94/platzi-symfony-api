## Instalar Api Platform
```
    symfony composer require api
```

## Instalar el sistema de conexión a la base de datos
```
    composer require symfony/orm-pack
```

## Paquetes de Desarrollo
```
    composer require symfony/maker-bundle --dev
```

## Crear entidad
```
    php bin/console make:entity Category
    php bin/console make:entity Post
```

## Crear base de datos
```
    php bin/console doctrine:database:create
```

## Creación de migración
```
    php bin/console make:migration
```

## Realizar migración
```
    php bin/console doctrine:migrations:migrate
```


```
```