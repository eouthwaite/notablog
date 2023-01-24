# bunsen-kodi

A place for me to keep notes whilst setting up an elderly Compaq CQ1000 PC as a Linux media server.

PC Specs:
AMD E-450 CPU with 6GB RAM

![image of Compaq CQ1000 PC](images/CompaqCP1000.jpg "Compaq CQ1000 PC")

## Install Linux

Installation of [BunsenLabs Linux](https://www.bunsenlabs.org/) has already been covered [here](bunsen-retrogaming.md)

## Install Kodi

   * Used to be called [XBMC](https://github.com/xbmc/xbmc) - installation on Linux documented [here](https://kodi.wiki/view/HOW-TO:Install_Kodi_for_Linux#Debian)
   
```
sudo apt-get install kodi
```

## Access shared Multimedia drive (NAS)

```
sudo apt-get install cifs-utils
```

## TODO

Check:

* DVD - can see, but doesn't appear to have a way to play the DVD
* Stream from NAS - partially working using cifs
* Stream from Netflix, Disney+, Prime
