# Laravel Docker Compose Template

This is a very simple template to start developing a laravel project with docker-compose.

## Usage

```bash
docker-compose up
docker exec -it <DOCKER_APP_CONTAINER_NAME> /bin/bash
composer global require laravel/installer
export PATH=$PATH:$HOME/.composer/vendor/bin
laravel new
php artisan serve
```

Open your app at `http://localhost` and start developing :).

I know that I could have just packed all this into a shell file - but i want you to understand what is actually happening and it's not a giant problem to execute this few lines...

## Why are you doing it this way - are you stupid?
If you know better ways to use laravel with docker-compose, please feel free to create a pull request, an issue or fork your own version and write me, so i can link it.