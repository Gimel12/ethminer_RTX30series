# About:
This is a project based on the Original Ethminer project, we just added support for the new Nvidia RTX 30 series

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

## Best wallets, Pools to use  

You want to have a good wallet for mining since exchanges are not recommended and then once you receive the funds you can transfer to your exchange like Coinbase. 
Using a trustworthy POOL is important, for ethereum we recommend ethermine.org 

### Best wallet for mining 

[EXODUS](https://www.exodus.io/)

### Best POOL for Ethereum 

[ETHERMINER](https://ethermine.org/)

### Best Exchanges Platform 

[COINBASE](https://www.coinbase.com/)
[GEMINI](https://gemini.com/)
[BINANCE](https://www.binance.com/en)



# Reference Original repo
Ethminer - https://github.com/ethereum-mining/ethminer
