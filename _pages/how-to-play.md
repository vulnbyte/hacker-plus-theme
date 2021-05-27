---
layout: default
---

Want to give **./vulnbyte** boxes a try but dont know how? This section includes everything you need to set up an environiment and start working on it.

## Installing VirtualBox
The OS being used through this set-up walkthrough is Kali Linux since you will most likely need a penetration testing distribution to play the boxes.

```sh
┌──(vulnbyte㉿kali)-[~]
└─$ sudo apt update
┌──(vulnbyte㉿kali)-[~]
└─$ sudo apt install virtualbox
```

Afterwards make sure your kernel headers are installed and set up :
```sh
┌──(vulnbyte㉿kali)-[~]
└─$ sudo apt install linux-headers-5.10.0-kali7-amd64
```
>* Note : Your kernel version could be different from the one we have shown above so always make sure to check it using : **uname -r**
