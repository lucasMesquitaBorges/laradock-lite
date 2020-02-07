# Laradock Lite
Inspired by [laradock](https://github.com/laradock/laradock)!

A light development docker environment containing the minimum dependencies to run a PHP application.

## Setup
```no-highlight
Click at the button "Use this Template" and then clone your repository.

Copy your laravel project to this project folder.
Merge laravel .env with docker .env

Inside your project folder run:
docker-compose up -d
docker-compose exec workspace bash
composer install
```
## Access PHP container shell
```no-highlight
docker-compose exec workspace bash
```
## More workspace releases
If you need changing workspace release, see all available releases at [laradock-lite-builder](https://github.com/lucasMesquitaBorges/laradock-lite-builder) or [builds](https://hub.docker.com/r/lucasmesquitaborges/laravel/builds).
