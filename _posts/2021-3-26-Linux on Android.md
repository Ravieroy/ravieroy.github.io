---
layout: post
title: Android Tips
date: 2021-03-26 20:15:00 -0800

---

# 1. Installing Linux OS on Android platform
----

## Why use Linux in Android OS?

* Well, you could be just tinkering around and learning stuffs.
* You love terminal functionality of Linux.
* You want to remotely access your device
* You might want to learn linux but don't have access to laptop or computer.

For whatever reason you might want to do this, this guide will help you do that. This will let you use the full power of **Linux** on your Android device, and not just terminal(for which **Termux** is the best) . Needless to say that, the best experience of using this will be on Android Tablets due to their larg screen size.

----

## Requirements

1. [Termux](https://play.google.com/store/apps/details?id=com.termux&hl=en_IN&gl=US)
- It is an android terminal emulator app which works directly with no rooting or setup required. It is quite handy tool to have in android smartphones. 
3. [Andronix](https://play.google.com/store/apps/details?id=studio.com.techriz.andronix&hl=en_IN&gl=US)
- This app lets you install Linux system on your android device without root. There are several distros you can install easily and for free, although there are modded paid versions of distros as well. You can install Ubuntu, Kali, Debian, Arch, Manjaro, Fedora, Void and Alpine. 
5. [VNC Viewer](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android&hl=en_IN&gl=US)
- This turns your phone into a remote desktop, giving instant access to your system.
----

## Setting things up

Once you have installed all the three apps, we can begin.

This is how Termux looks when first started. It uses ```pkg``` as its package manager. 

![Termux-1](https://user-images.githubusercontent.com/81288438/112806651-a56ee580-9094-11eb-97c3-35ea40ad03ce.jpg)

Run ```pkg upgrade ``` to update the system. At one point you would be asked about configuration files. I would recommend to go with the default options here. This will take around 2 minutes to complete.

![Termux-2](https://user-images.githubusercontent.com/81288438/112806657-a7d13f80-9094-11eb-8454-00f9baf2a597.jpg)

Once the update is finished, go ahead and open **Andronix**. You will be able to choose your preffered distro here. For this guide I am choosing Manjaro XFCE. 

![Andronix-1](https://user-images.githubusercontent.com/81288438/112807790-e87d8880-9095-11eb-8fde-1ffa38a8268e.jpg)

Click on install

![Andronix-2](https://user-images.githubusercontent.com/81288438/112808027-30041480-9096-11eb-98d3-a803dbc73aa2.jpg)

Choose what version or distro you want to install. When you click on the version, a text will be copied in your clipboard. 

![Andronix-3](https://user-images.githubusercontent.com/81288438/112808261-6e99cf00-9096-11eb-94d0-08bd8cd97293.jpg)

Open Termux and paste it there and press ENTER.

![Installation-1](https://user-images.githubusercontent.com/81288438/112808370-8cffca80-9096-11eb-955b-079f726594ea.jpg)

Now you have to wait. Everything is automated from here and it can take upto 20 - 25 minutes to complete the setup. You should be connected to internet and this whole process will take around 500MB of your internet data.

***Important: You might have to allow Termux for access to storage while the setup. If it asks for it, just press allow. ***
---

## Post-installation










