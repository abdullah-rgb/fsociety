# fsociety
__WARNING: do not actually execute this. You will not be able to recover the files.__

This is intended to encrypt every bit of data in a unix filesystem using 256-bit AES with 
a self-destructing, randomly generated key.

The fuxsocy.py script is based on Darlene's malware shown in Mr Robot

## S2E1:

![alt text](https://i.imgur.com/6RIogYa.jpg)

### Dependencies:

* python3
* wheel
* base
* rng
* AES
* crypto
* crypto-utils
* pycrypto
* pycryptodome

```shell
sudo su
```
```shell
pacman -S python python-pip
```
```shell
pip3 install wheel
```
```sheel
pip3 install base
```
```sheel
pip3 install rng
```
```shell
pip3 install AES
```
```sheel
pip3 install crypto
```
```sheel
pip3 install crypto-utils
```
```sheel
pip3 install pycrypto
```
```sheel
pip3 install pycryptodome && rm -rf ~/.cache/* && pip3 uninstall pycryptodome && pip3 install pycryptodome==3.5 && rm -rf ~/.cache/* && pip3 uninstall pycryptodome && pip3 install pycryptodome && rm -rf ~/.cache/*
```

### Install dependencies with one command:
```shell
sudo su && pacman -Sy python-pip && clear && pip3 install wheel && clear && pip3 install base && clear && pip3 install rng && clear && pip3 install AES && clear && pip3 install crypto && clear && pip3 install crypto-utils && clear && pip3 install pycrypto && clear && pip3 install pycryptodome && rm -rf ~/.cache/* && clear && pip3 uninstall pycryptodome && clear && pip3 install pycryptodome==3.5 && rm -rf ~/.cache/* && clear && pip3 uninstall pycryptodome && clear && pip3 install pycryptodome
```

### Usage:

```shell
git clone https://github.com/abdullah-rgb/fsociety
```
```shell
chmod +x fuxsocy.py
```
```shell
./fuxsocy.py
```

### Or:
```shell
python3 fuxsocy.py
```
