# Commands used in this practice

## Commands to be included in Launch script
```BASH
sudo apt update
sudo apt-get install mysql-client-core-8.0 -y
```

## SSH into Database Instance
```BASH
mysql -h DATABASE_URL -u dbmaster -pHello2World
```

## MySQL Database commands 
```BASH
SHOW DATABASES;
CREATE DATABASE secondDB;
```
## Give privileges to your user
```BASH
GRANT ALL PRIVILEGES ON secondDB.* TO 'dbmaster'@'%';
```
