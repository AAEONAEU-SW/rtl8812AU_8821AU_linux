# rtl8812au

Realtek 8812AU/8821AU USB WiFi driver.

This code is base on version 4.3.14 from https://github.com/diederikdehaas/rtl8812AU

This code was forked from https://github.com/abperiasamy/rtl8812AU_8821AU_linux

## Validated supported device on this release:

```
* Fangtec 802.11a/b/g/n/ac USB Wireless Adapter(Model: GWF-5M02)
```

## Compiling with DKMS

Clean the system from previous drivers if any and clone current repository

```sh
# sudo apt purge rtl8812au-dkms
# sudo apt install git build-essential dkms
# git clone https://github.com/AAEONAEU-SW/rtl8812AU_8821AU_linux.git
# cd rtl8812AU_8821AU_linux
```

Install kernel headers 

```sh
# sudo apt install linux-headers-$(uname -r)
```

Install support for WiFi adapter

```sh
# sudo make -f Makefile.dkms install
# sudo modprobe rtl8812au
```

## Contributors
<!-- DO NOT EDIT - CONTRIBUTORS.md is autogenerated from git commit log by contributors.sh script. -->

- Anand Babu (AB) Periasamy
- Andreas Hofmann
- Andrew Mann
- AndyPi
- Anton
- archshift
- bits3rpent
- Chen Minqiang
- Daiki Tamada
- Fjodor42
- gremsto
- HackDefendr
- Harshavardhana
- jjones-jr
- Joe
- Joe Acosta
- John Lenz
- Jos Dehaes
- Karl-Philipp Richter
- Marco Milanesi
- Mauro Ribeiro
- Maximilian Schwerin
- mpoly
- Nick Bartos
- Peter H. Li
- pgroenbech
- scrivy
- Taehan Stott
- Vicent Llongo
- Victor Azizi
- 赵迤晨 (Zhao, Yichen)
