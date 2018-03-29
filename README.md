# docker-yiimp-stratum
Dockerfile for Yiimp stratum based on linux alpine 3.7 and tpruvot/yiimp original repository

# Usage
Before launching this container make sure the mysql database is up and running with default values 

```
docker run -itd jsminet/docker-yiimp-stratum
```

You can use you own git repository by changing the ARG value at build time

```
git clone https://github.com/jsminet/docker-yiimp-stratum.git
docker build --build-arg REPOSITORY=https://github.com/YOUR_FORKED_REPOSITORY_NAME . -t IMAGE_NAME
```

# TODO
- Load dynamic parameters for database purpose