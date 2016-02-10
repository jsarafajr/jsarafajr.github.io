---
layout: post
title: Disable Web Security in Chrome
published: true
---
  
_'No 'Access-Control-Allow-Origin' header is present on the requested resource.'_  
To prevent this error run chrome without web security:  

For OSX:  
```bash
$ open -a Google\ Chrome --args --disable-web-security
```  
  
For Linux:  
```bash
$ google-chrome --disable-web-security
```
