- docker-compose build app
- docker-compose up -d

- docker-compose exec app composer create-project laravel/laravel .
- docker-compose exec app php artisan migrate

- docker-compose run npm install
- docker-compose run npm run dev