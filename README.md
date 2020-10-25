# template-docker-laravel
Template untuk deploy project laravel

````
1. perhatikan docker-compose.yml lalu ganti database dan password yang di butuhkan
2. taruh project mu pada directory ../src
3. pada directory src perhatikan file .env sesuaikan password dan data base yang di butuhkan
3. untuk menjalankan gunakan command
````
docker-compose up -d
````
4. masuk pada container app
````
docker exec -ti nama_container /bin/bash
````
5. install composer
````
composer install
````
6. migrate
````
php artisan migrate
````
