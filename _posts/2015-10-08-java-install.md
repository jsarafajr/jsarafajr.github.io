---
layout: post
title: Installing Java 8 on Ubuntu based Linux
published: true
---

Setup repository and install java8:

```bash
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java7-installer
```  

Enter the following at the bottom of the **/etc/environment** file:

```bash
JAVA_HOME="/usr/lib/jvm/java-7-oracle"
```    

Type the following to execute **environment** file
 
```bash
source /etc/environment
```    
  
