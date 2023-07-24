# forensicVM-repo
Forensic VM Debian repository

Install on debian 11

## Edit sources.list

nano /etc/atp/sources.list

```
deb http://deb.debian.org/debian/ bullseye-backports main

deb https://raw.githubusercontent.com/nunomourinho/forensicVM-repo/master/ buster main
```

## Get repository key and update sources

```
apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 5CDA5BD90CE92DC854110684D4EC173065693394
apt update
```

## Install or update forensic-vm server:

### Install:
```
apt install forensic-vm
```

### Update:
```
apt update forensic-vm
```




