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

## Instalar dependencia para los factories
```
    composer require zenstruck/foundry --dev
```

## Creamos factories de todas las entidades
```
    php bin/console make:factory
```

## Creación del archivo base para generar los datos falsos
```
    php bin/console make:fixtures
```
Instalamos la dependencia para los fixtures
```
     composer require orm-fixtures --dev
```

## Generamos los datos falsos
```
    php bin/console doctrine:fixtures:load
```

## Detallar las rutas
```
    php bin/console debug:router
```

## 
```
```

## 
```
```

## 
```
```