## Real World Project: Database Shard Github
```
The project is done on lubuntu-20.10-desktop
```


## Requirements:
```
Linux os installed on the VM
Install clone 
Install docker-compose
Install mariadb-client
```

## Install Docker:
```
Run the below command:

sudo apt update
sudo apt upgrade
sudo apt install docker.io
sudo systemctl enable --now docker
sudo systemctl status docker
```


## Install Docker-Compose:
```
sudo apt install docker-compose
```

 ## To Install Mariadb:
```
Run the command:

sudo apt install mariadb-client
```


## Clone the maxscale-docker repository
```
The command:

sudo apt install githttps://github.com/Zohan/maxscale-docker
```


## The maxscale directory:
```
The command:

cd maxscale-docker/maxscale/
```


## Seting the containers up/down:
```
The command:

sudo docker-compose up -d
sudo docker-compose down -v
```


## chek the containers:
```
the command:

docker-compose ps -a
```


## check the servers: 
```
The  command:

sudo docker-compose exec maxscale maxctrl list servers
```


## To connect to mariadb
```
mariadb -umaxuser -pmaxpwd -h 127.0.0.1 -P 4000
```

### The result:

Welcome to the MariaDB monitor.  Commands end with ; or \g.
Your MariaDB connection id is 1
Server version: 10.5.9-MariaDB-1:10.5.9+maria~focal-log mariadb.org binary distribution

Copyright (c) 2000, 2018, Oracle, MariaDB Corporation Ab and others.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.
```
