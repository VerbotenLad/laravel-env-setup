# laravel-env-setup
COPY AND PASTE THE COMMANDS BELOW INTO YOUR LARAVEL REPOSITORY'S DIR

composer install 
mv .env.example .env 
php artisan cache:clear 
composer dump-autoload 
php artisan key:generate

IF YOU ARE ON WINDOWS TERMINAL, USE "move" INSTEAD OF "mv"
