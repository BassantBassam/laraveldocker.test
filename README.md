# Laravel Project environment

- This is a project to config the laravel project to work

## Dependencies

- Docker
- Docker compose
- Make CLI

## Services

- Nginx: with port: `8088` => `http://loclhost:8088`
- PHP: with version `8.2`
- MySql: with version `5.7.22`
- phpmyadmin: with port: `8081` => `http://localhost:8081`

## How to use
- `docker-compose up -d`: run all services
- `docker-compose down`: exit all services
- `docker-compose exec php bash`: enter to `php` service
- `docker-compose exec mysql bash`: enter to `mysql` service

## Advanced settings [TODO]

