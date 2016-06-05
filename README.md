# Setup

1. Install apache, mysql, and php 
2. Create mysql database and user

```
CREATE DATABASE database;
CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON database . * TO 'username'@'localhost';
FLUSH PRIVILEGES;
```

wp core install --url=http://bol.dev:8080 --title="Breath of Life" --admin_user=admin --admin_password=G@NdLGsN*J1 --admin_email=car.mar.kuba@gmail.com


