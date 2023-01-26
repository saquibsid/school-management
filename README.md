To Install
create new file .env and copy env.example content
create the db in phpmyadmin
composer update
php artisan key:generate
php artisan config:cache
php artisan migrate:fresh --seed