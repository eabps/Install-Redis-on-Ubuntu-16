# Install Redis on Ubuntu 16
This document describes step by step to install [**Redis**](https://redis.io/) on SO Ubuntu 16

## Install Dependencies ##
```sh
$ sudo apt-get update && sudo apt-get upgrade
```
```sh
$ sudo apt-get install build-essential tcl
```

## Install Redis ##
```sh
$ sudo apt-get install redis-server
```
## Config Redis: ##
```sh
$ sudo nano /etc/redis/redis.conf
```

## Start Redis: ##
After install, reboot computer for redis start with OS.
```sh
$ service redis-server status
```
OR
```sh
$ sudo systemctl status redis
```
Check if Redis is working
```sh
$ redis-cli ping
```
