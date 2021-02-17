# Sync your wallet faster with the bootstrap.dat 

Fresh wallets can take a while to download and sync the blockchain. This process can be sped up by using the bootstrap.dat file in the Lunarium data directory.

To take advantage of this:

* First download and unzip the most recent *bootstrap.dat.zip* file: https://github.com/LunariumCoin/lunarium-wallet-bootstrap/releases
* Then, with the Lunarium wallet closed, drop the *bootstrap.dat* file into the Lunarium data directory respective to your operating system.

Linux:

`~/.lunarium/`

MacOS:

`$HOME/Library/Application Support/Lunarium/`

or

`/Users/username/Library/Application Support/Lunarium/`

Windows:

`%APPDATA%\Lunarium`

Finally start your wallet and it should start to index blocks shortly after, saving you hours of waiting.

## Extra hint

To be sure to connect to valid Lunarium nodes upon sync completion (and avoid staking invalid coins), please visit [Lunarium Discord](https://discord.gg/KSNdgvsW) server and copy the content of the `addnodes` channel to your own *lunarium.conf* file (you will find this file in Lunarium data directory).
