# Back-end-s-paration

 Symfony 4.4 application inside containers

```

#Lunch the docker-compose
cd docker && docker-compose -p sym4-boilerplate up -d && cd ..

#Se connecter au container PHP 
docker exec -it meg_php /bin/bash

#first lunch
composer install
sh command.sh

#Open browser : 
            
    - URL : http://localhost:8085/
    - PhpMyAdmin : http://localhost:8081    user = root / pass = root

#Close the docker compose
cd docker && docker-compose -p sym4-boilerplate down && cd ..


```

## Compose

### Database (Mysql)

### PHP (PHP-FPM)

### Webserver (Apache)

### Local

cd src/
php -S 127.0.0.1:8000 -t public

# Lunch Docker Compose




