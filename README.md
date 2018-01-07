# Docker

## Basic Python3.6 Dockerfile
+ [Ubuntu](./Python3_Dockerfile/Ubuntu_python3)
+ [Centos](./Python3_Dockerfile/CentOS_python3)

```
# Remove none TAG images
docker rmi $(docker images -f "dangling=true" -q)
```