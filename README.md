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

To show `src` dir (It's your document root!), access to http://localhost.

And to show [phpMyAdmin](https://www.phpmyadmin.net/), access to http://localhost:8080.

### stop
```
$ docker-compose stop
```

### connect to MySQL
Use your favorite tool for connect to mysql with below information.

- Host: `localhost`
- Port: `3306`
- UserName: `root`
- Password: `password`

or use below command

```
$ docker-compose exec mysql mysql -u root -ppassword
```

### reset MySQL data
Delete `./mysql` dir to initialize db.