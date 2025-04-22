[![Download latest](https://img.shields.io/badge/🡇-Download_latest-green)](https://github.com/openwrt-xiaomi/xmir-patcher/archive/refs/heads/main.zip)
[![ViewCount](https://views.whatilearened.today/views/github/openwrt-xiaomi/xmir-patcher.svg)](https://github.com/openwrt-xiaomi/xmir-patcher/archive/refs/heads/main.zip)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fopenwrt-xiaomi%2Fxmir-patcher&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://github.com/openwrt-xiaomi/xmir-patcher/archive/refs/heads/main.zip)
[![Donations Page](https://github.com/andry81-cache/gh-content-static-cache/raw/master/common/badges/donate/donate.svg)](https://github.com/remittor/donate)

# XMiR-Patcher
Firmware patcher for Xiaomi routers


## Usage

### Windows

* Run `run.bat`

### Linux / Mac OS

* Install python 3.8+ and openssl
* Run `./run.sh`

## Donations

[![Donations Page](https://github.com/andry81-cache/gh-content-static-cache/raw/master/common/badges/donate/donate.svg)](https://github.com/remittor/donate)
## how to use this to connect ssh
After `run.sh` you will see the following
```bash
==========================================================

Xiaomi MiR Patcher  


 1 - Set IP-address (current value: 192.168.31.1)
 2 - Connect to device (install exploit)
 3 - Read full device info
 4 - Create full backup
 5 - Install EN/RU languages
 6 - Install permanent SSH
 7 - Install firmware (from directory "firmware")
 8 - {{{ Other functions }}}
 9 - [[ Reboot device ]]
 0 - Exit

Select: 
```

Then enter `2` and open another terminal. In the new terminal enter
```bash
ssh root@192.168.31.1
```
If the following error occurs 
```bash
Unable to negotiate with 192.168.31.1 port 22: no matching host key type found. Their offer: ssh-rsa
```

Try to enter 
```bash
mac$ ssh -o HostKeyAlgorithms=+ssh-rsa root@192.168.31.1
```

Last but not least, the default password for Xiaomi Router is Usually `root`.

