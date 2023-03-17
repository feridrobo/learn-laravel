## El primer paso fue instalar composer

composer install

## Después cambiar el nombre del .env.example por .env

mv .env.example .env

## limpiar cache

php artisan cache:clear

composer dump-autoload

## y por último generar el key

php artisan key:generate
