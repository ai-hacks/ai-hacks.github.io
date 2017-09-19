---
layout: post
title: Vorbereitungen laufen
date: 2017-09-19 16:06:00 +0002
categories: 24h-sprint raspberry docker
published: false
---
# Docker auf Raspberry
* mit [Etcher](https://etcher.io/) [lite image](https://www.raspberrypi.org/downloads/raspbian/) flashen
* am pc direkt auf die sdcard ein leeres file names 'ssh' hinterlegen um ssh zu aktivieren
* am mac Thunderbold Ethernet using dhcp
* am mac internet sharing aktivieren
* ssh pi@raspberrypi.local
* /boot/config.txt gpu_mem=16
* curl -sSL https://get.docker.com | sh
* sudo systemctl enable docker
* sudo systemctl start docker
* sudo usermod -aG docker pi

https://blog.alexellis.io/getting-started-with-docker-on-raspberry-pi/

https://docs.docker.com/engine/swarm/swarm-tutorial/create-swarm/