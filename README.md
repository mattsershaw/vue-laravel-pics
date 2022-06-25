docker-compose exec vue-laravel-pics_web bash
php artisan serve --host 0.0.0.0 --port 8081

docker-compose exec vue-laravel-pics_web php artisan serve --host 0.0.0.0 --port 8081

docker-compose exec vue-laravel-pics_web npm install
docker-compose exec vue-laravel-pics_web npm run watch