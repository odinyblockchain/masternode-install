# MasternodeSetup

### Required:

1. ODC Coins for Collateral <br>

2. Download your Local Wallet: https://github.com/odinyblockchain/odinycoin/releases

3. You will need also VPS with Ubuntu 16.04, 18.04 , 19.04

### Usage

1. After you longin on your VPS , with this command you will download masternode-installer.   
`wget -q https://raw.githubusercontent.com/odinyblockchain/masternode-install/master/masternode-install.sh`  
- For Ubuntu 18.04 + use this one command   
`wget -q https://raw.githubusercontent.com/odinyblockchain/masternode-install/master/masternode-install-ubuntu-0.18.sh` 

2. With this command you will make masternode-install.sh executable.  
`sudo chmod +x masternode-install.sh` <br>

- For Ubuntu 18.04+ use this: <br>
`sudo chmod +x masternode-install-ubuntu-0.18.sh` <br>

3. Now install your masternode.  
`./masternode-install.sh`

- For Ubuntu 18.04+ use this to install masternode: <br>
`./masternode-install-ubuntu-0.18.sh`
