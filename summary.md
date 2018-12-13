Test assignment
===============

Requirements
-------------

- Docker https://docs.docker.com/engine/installation

Spin up containers:
-------------------

```bash
$ docker-compose up -d --build
```

Run composer:
-------------
```
php composer.phar install  
```

Run simulator command
------------------

```sh
$ docker exec -it mvp sh 
$ php import.php report
