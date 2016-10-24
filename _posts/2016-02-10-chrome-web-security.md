---
layout: post
title: Remove all Docker Images from host OS
published: true
---
Delete all containers:  
```
docker rm $(docker ps -a -q)
```  

Delete all images:    
```
docker rmi $(docker images -q)
```
