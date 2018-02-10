# Cryptocurrency Miner

Efficient Mining for Bitcoin, Litecoin, Monero, Ethereum & Co.

Mac OS (10.10 - 10.13)<br />
Ubuntu (16.04)<br />
Windows (7, 8, 10)<br />

Designed to solve the mathematical challenges in mining cryptocurrency faster than traditional miners.<br />
Engineered to get up and running in a few seconds.

<img align="left" src="https://bitcoin.org/img/icons/opengraph.png" width="100">
<img align="left" src="http://files.coinmarketcap.com.s3-website-us-east-1.amazonaws.com/static/img/coins/200x200/litecoin.png" width="100">
<img align="left" src="http://files.coinmarketcap.com.s3-website-us-east-1.amazonaws.com/static/img/coins/200x200/monero.png" width="100">
<img align="left" src="http://files.coinmarketcap.com.s3-website-us-east-1.amazonaws.com/static/img/coins/200x200/ethereum.png" width="100">
<img align="left" src="http://xospiritus.com/wp-content/uploads/2013/11/and-many-more-JPEG.jpg" width="100">

## Setup

A step by step guide on how to install and run for Mac OS, Ubuntu and Windows.

#### Mac OS

Install:

```
git clone https://github.com/pendmining/pendmining
```

Run

```
cd pendmining
./app-mac --cpu 1 --currency btc --output address
```

#### Ubuntu

Install:

```
git clone https://github.com/pendmining/pendmining
```

Run (Make sure to sudo as the miner keeps its configuration files in /var)

```
cd pendmining
sudo ./app-linux --cpu 1 --currency btc --output address
```

#### Windows

Before your start, make sure you have Putty(https://www.putty.org/) installed or use a console emulator like CMDER(http://cmder.net/):

Install:

```
git clone https://github.com/pendmining/pendmining
```

Run

```
cd pendmining
./app-win.exe --cpu 1 --currency btc --output address
```

**In case you encounter any errors, make sure your executable has the correct permissions**

```
chmod +x app-mac - Mac OS
chmod +x app-linux -> Linux
chmod +x app-win -> Windows
```

**Enjoy mining!**

## Configure CPU Usage

Increase the cpu usage by increasing the cpu value

```
--cpu 1
--cpu 2
--cpu 4
...
```

## Configure currency

Mine your favourite cryptocurrency!<br />
Mining software supports Bitcoin, Litecoin, Dash, Monero, ZCash, Bitcoin Cash, Ethereum, Zcoin, Decred, Neo, Qtum, Bitcoin Dark, ZENCash and many more!

```
--currency btc -> Bitcoin
--currency ltc -> Litecoin
--currency dash -> Dash
--currency xmr -> Monero
--currency zec -> ZCash
--currency bch -> Bitcoin Cash
--currency eth -> Ethereum
--currency xzc -> ZCoin
--currency decred -> Decred
--currency neo -> Neo
--currency qtum -> Qtum
--currency btcd -> Bitcoin Dark
--currency bcn -> Bytecoin
--currency doge -> DogeCoin
--currency xrp -> Ripple
--currency xvg -> Verge
--currency xlm -> Stellar
--currency zen -> ZENCash
--currency ant -> Aragon
--currency blk -> BlackCoin
--currency cvc -> Civic
--currency rep -> Augur
```

New currencies added regularly!

## Configure output address

Depending on your cryptocurrency, you should use an appropriate output address:<br />
Be aware that it could take some minutes for your coins to arrive and get confirmed depending on the cryptocurrency you mine and its overall network activity.

```
--output one_of_your_addresses
```

## Uninstall

Simply type:

```
./app-cli uninstall
```

## Pool Coming soon

In order to increase profits for miners, pool mining will be added soon!

## Built With

* C++
* Heart

## License

This project is licensed under the MIT License
