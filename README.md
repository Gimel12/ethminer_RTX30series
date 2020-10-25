# About:
This is a project based on the Original Ethminer project, we just added support for the new Nvidia RTX 30 series

## Ethminer support for RTX 3080-3090 and CUDA 11.1

Original repo - https://github.com/ethereum-mining

# Requirements 
-Nvidia driver and CUDA need to be installed

# Support added 
- Nvidia driver 455
- CUDA 11.1 


# How to use it

- 1- Download the latest release, unzip it and navigate to the folder. 
- 2- Copy the commands below and replace the options for your wallet and pools that you want to connect. 


# Ethminer commands

```bash
ethminer -h # list of commands
```

# Example to start mining
```bash 
sudo ethminer -U -P stratum://0x385E6bA2F90E581f7BF37a103932F920eea70400@us1.ethermine.org:4444 -v 3
```

- Where 0x385E6bA2F90E581f7BF37a103932F920eea70400 - is the wallet 
- Where us1.ethermine.org:4444 - is the pool 

# You Dont know about Linux, is simple !!! Watch our Video !!!

[YOUTUBE VIDEO]()

# Reference Original repo
Ethminer - https://github.com/ethereum-mining/ethminer
