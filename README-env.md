# Laravel API with Angular
This is not a business project, just for fun !

## Requirements

Please visit:
- [bitnami/laravel: docker based](https://hub.docker.com/r/bitnami/laravel)
- [angular: official documentation](https://angular.io/guide/quickstart)

## Installation
- `mkdir ~/myapp && cd ~/myapp`
- `curl -LO https://raw.githubusercontent.com/bitnami/bitnami-docker-laravel/master/docker-compose.yml`
- edit database const in your docker-compose.yml
- edit .env to make const equals to connect database
- `docker-compose up -d`
- `docker-compose exec myapp php artisan serve`
- now go to [http://localhost:3000](http://localhost:3000)
- laravel works ✌️
