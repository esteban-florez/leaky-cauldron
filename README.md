# App de Acreditable

Apicación web de ejemplo con Laravel.

## Requerimientos

- PHP v8.1
- Node.js v18
- MySQL o MariaDB

## Instalación

1. Clonar el proyecto:

```bash
  git clone https://github.com/esteban-florez/sistema-vehiculos
```

2. Instalar dependencias:

```bash
  composer install
  npm install
```

3. Compilar para producción:

```bash
  npm run build
```

4. Renombrar ".env.example" a ".env" y configurar conexión a la base de datos

```.env
  DB_CONNECTION=mysql
  DB_HOST=127.0.0.1
  DB_PORT=3306
  DB_DATABASE=nombre_db
  DB_USERNAME=root
  DB_PASSWORD=
```

5. Ejecutar migraciones:

```bash
  php artisan migrate --seed
```

6. Ejecutar servidor local:

```bash
  php artisan serve
```
