# Mac_changer
mac_changer - Change your MAC Address - Change the network identity of your device (EASIER and FASTER than EVER). Please visit my website [post](https://leuvaapurv.github.io/mac_changer/).

## Desclaimer
mac_changer is intented ONLY for EDUCATIONAL PURPOSES.

## Requirements
Python3

## Install
```
# git clone https://github.com/LeuvaApurv/mac_changer
# cd mac_changer
```

## Usage
Run the python script and change new mac address.

## Help
```
# python3 mac_change.py -h
Usage: mac_change.py [options]

Options:
  -h, --help            show this help message and exit
  -i INTERFACE, --interface=INTERFACE
                        Interface to change its MAC Address
  -m NEW_MAC, --mac=NEW_MAC
                        New MAC Address

```

## Sample output:
```
# python3 mac_change.py -i eth0 -m 00:11:22:33:44:55
[+] Changing MAC address for eth0 to 00:11:22:33:44:55
```
