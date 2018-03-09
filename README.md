# lamp-docker-compose
Quick start LAMP environment using docker-compose!

## Requirement
- Docker
- docker-compose

## Usage
### start
```
$ https://github.com/uutarou10/lamp-docker-compose.git
$ cd lamp-docker-compose
$ docker-compose up -d
```

It's all!

To show `src` dir, access to http://localhost.

And to show (phpMyAdmin)[https://www.phpmyadmin.net/], access to http://localhost:8080.

### stop
```
$ docker-compose stop
```

### use MySQL terminal
```
$ docker-compose exec mysql mysql -u root -p password
```