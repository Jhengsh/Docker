# Docker

## Basic Python3.6 Dockerfile
+ [Ubuntu](./Python3_Dockerfile/Ubuntu_python3/Dockerfile)
+ [Centos](./Python3_Dockerfile/CentOS_python3/Dockerfile)

## Command Note
```
# Remove none TAG images
docker rmi $(docker images -f "dangling=true" -q)
docker-compose config --service

```

## Docker-compose with Static IP
+ [Set specific IP addresses to docker containers created with docker-compose](https://blog.alejandrocelaya.com/2017/04/21/set-specific-ip-addresses-to-docker-containers-created-with-docker-compose/)
