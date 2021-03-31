---
layout: post
title: Android Tips-Part 2
date: 2021-03-30 09:50:00 -0800

---

# Accessing android files from PC via SSH
----

## Table of Contents
---

1. [Requirements](#requirements)
2. [Android Setup](#android-setup)
3. [PC setup](#pc-setup)

----

## Requirements
----

1. [SS Helper app](https://play.google.com/store/apps/details?id=com.arachnoid.sshelper&hl=en_IN&gl=US)
- SSHelper is a secure server for the Android platform developed by **Paul Lutus**. It works with a normal, unrooted Android device and offers special features on rooted devices. Have a look at [this website](https://arachnoid.com/android/SSHelper/index.html) by the author for all the information in detail. Here in this guide, I will show steps to just get it working. It is a simple process which can be done within minutes. 

2. You should have SSH setup in your system( It works in Windows via PuTTY)

----

## Android Setup
----

Once we have the app installed we can go ahead and start the application. It works right out of the box without making much configuration changes, although we will change the password for security purposes. 

The moment you will start the application, it will ask for your permission to access your storage. Provide the permission. 

![SS-1](https://user-images.githubusercontent.com/81288438/113170590-51b2f680-9264-11eb-84b5-0c4eb536a4f9.jpg)

Once done, it will start the server. Head over to the **configuration** which has all the necessary details. Note down the assigned **Server address** which is of the form 192.168.xx.xxx and **SSH server port number** which is 2222 . Now click on the text field of **Server Password** and put your own password. Now restart the server with new values.

![SS-2](https://user-images.githubusercontent.com/81288438/113171179-db62c400-9264-11eb-83d2-ba0c726be07d.jpg)

----





