# Setup

1. Install apache, mysql, and php 
2. Create mysql database and user

```
CREATE DATABASE database;
CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON database . * TO 'username'@'localhost';
FLUSH PRIVILEGES;
```

