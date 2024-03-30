
# Docker compose 

Run a container of gogs and postgres with docker compose

![image](https://github.com/Abhay956/gogs-docker-compose/assets/132220412/151fca9c-fb6e-4e0b-ae3a-591b05c56b2a)


## Run Locally


Install Docker-compose on ubuntu

```bash
sudo apt-get update
sudo apt-get install docker-compose-plugin
```

Install Docker compose on RPM-based distros

```bash
sudo yum update
sudo yum install docker-compose-plugin
```

Clone the project

```bash
git clone git clone https://github.com/Abhay956/gogs-docker-compose.git
cd gogs-docker-compose/
```

Now run container with docker compose

```bash
sudo docker compose up -d  
```


### Access gogs

http://localhost:3000

![image](https://github.com/Abhay956/gogs-docker-compose/assets/132220412/f73ff266-1ac7-4103-acdd-bd550afa474d)

- User=abhay

- Password=redhat

host in enter your postgres ip address. using this command check your ip address

```bash
docker inspect gogs-docker-compose_postgres_1 | grep IPAddress
```
