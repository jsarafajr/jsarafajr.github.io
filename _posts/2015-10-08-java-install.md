---
layout: post
title: Installing Java 8 on Ubuntu based Linux
published: true
---


Every time I got stuck when trying install Java and add JAVA_HOME variable on a new machine. So I save steps here.  

Setup repository and install java8:

```bash
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer
```  

Enter the following at the bottom of the **/etc/environment** file:

```bash
JAVA_HOME="/usr/lib/jvm/java-8-oracle"
```    

Type the following to execute **environment** file
 
```bash
source /etc/environment
```
  
    
    