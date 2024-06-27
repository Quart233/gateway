# Requirements
- OS: Alpine Linux 3.9
- Packages: linux-firmware-rtl_nic linux-lts v2ray

## Realtek NIC
### 1. Install packages
```shell
apk add linux-firmware-rtl_nic linux-lts
```

### 2. Output shows NIC reconigzed
```shell
ip a
```
Shell output:
```
eth1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP qlen 1000
    link/ether a0:36:9f:50:be:fa brd ff:ff:ff:ff:ff:ff
    inet 192.168.25.111/24 scope global eth1
       valid_lft forever preferred_lft forever
    inet6 fe80::a236:9fff:fe50:befa/64 scope link 
       valid_lft forever preferred_lft forever

```
