# mysql8.0-php7.2-apache2.4-docker

- Docker example with Apache, MySql 8.0, PhpMyAdmin and Php7
- docker-compose orchestrator

- Get docker
```bash
git clone https://github.com/nu11secur1ty/mysql8.0-php7.2-apache2.4-docker.git
```
- Compose
```
docker-compose up -d
```

- Open phpmyadmin at [http://localhost:8000](http://localhost:8000)

=====================================================================

- Open web browser to look php7 at [http://localhost:8001](http://localhost:8001)

=====================================================================

- Open app.php to look at [http://localhost:8001/app.php](http://localhost:8001/app.php)

Run mysql client:

- `docker-compose exec db mysql -u root -p` 

Enjoy !
