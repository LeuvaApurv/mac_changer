# Mac_changer
mac_changer - Change your MAC Address - Change the network identity of your device (EASIER and FASTER than EVER).

## Desclaimer
mac_changer is intented ONLY for EDUCATIONAL PURPOSES.

## Requirements
Python3

## Installation
Instructions on how to install *mac_changer*
```bash
sudo git clone https://github.com/LeuvaApurv/mac_changer.git
cd mac_changer
sudo python3 mac_changer.py -i eth0 -m 00:11:22:33:44:55

```

## Help
```bash
sudo python3 mac_change.py -h

Usage: mac_change.py [options]

Options:
  -h, --help            show this help message and exit
  -i INTERFACE, --interface=INTERFACE
                        Interface to change its MAC Address
  -m NEW_MAC, --mac=NEW_MAC
                        New MAC Address

```

## Sample output:
```bash
sudo python3 mac_change.py -i eth0 -m 00:11:22:33:44:55

[+] Changing MAC address for eth0 to 00:11:22:33:44:55

```
