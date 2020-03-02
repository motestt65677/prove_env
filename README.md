# Pre-install
+ Docker version 17.11.0-ce
+ Docker-compose version 1.13.0
+ Git

# Start
1. docker-compose up -d
2. docker container exec -it petty_cash bash
3. composer install
4. php artisan migrate
5. php artisan db:seed --class=DatabaseSeeder
6. php artisan key:generate
7. service apache2 restart

# Change branch
1. vim ./update.sh


