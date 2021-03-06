# Installation
## Check your environment
Prior to installing Embark, you should have the following prerequisites installed on your machine:
#### NodeJS 8.10+
```
node version
> 8.10+
```
If you need to update Node, please [install `nvm`](https://github.com/creationix/nvm#installation) and install/use the LTS version. macOS/Linux commands provided for you below for convenience:
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
nvm install --lts
nvm use lts
```
#### IPFS 0.4.15+
```
ipfs version
> 0.4.15+
```
[IPFS installation instructions](https://ipfs.io/docs/install/#installing-from-a-prebuilt-package), macOS/Linux command provided for you below:
```
tar xvfz go-ipfs.tar.gz
cd go-ipfs
sudo ./install.sh
ipfs init
```

#### Install ganache-cli
```
npm install -g ganache-cli
```

#### Installing Embark 3.1.7
If you already have Embark installed, please run: 
```
embark version
```

Make sure the version is `3.1.7`. If it’s not, re-install Embark by running:
```
npm install -g embark@3.1.7
```
> Do not use **sudo** when installing Embark

Re-run `embark version` to ensure we have `3.1.7`.