## 🚀 Instalación

# Instalar Composer
composer install

# Cambiar el nombre del archivo .env.example por .env
mv .env.example .env

## ⚙️ Configuración

# Asegúrate de que el archivo .env tenga los valores correctos para tu entorno de desarrollo.

## 🗑️ Limpieza de caché

# Limpia la caché
php artisan cache:clear

# Regenera los archivos de autoloading
composer dump-autoload

## 🔑 Generar la clave de la aplicación

# Genera la clave de la aplicación
php artisan key:generate
