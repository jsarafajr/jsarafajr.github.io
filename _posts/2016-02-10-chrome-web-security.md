---
layout: post
title: Remove all Docker Images from host OS
published: true
---
Delete all containers:  
```bash
docker rm $(docker ps -a -q)
```  

Delete all images:    
```bash
docker rmi $(docker images -q)
```