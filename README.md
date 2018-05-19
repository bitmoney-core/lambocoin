# Lambocoin Core

## What is Lambocoin?
Lambocoin is a cryptocurrency forked off of Dogecoin. It aims to build upon the foundation created by the popular meme coin, improving upon its surprisingly strong fundamentals to create a stronger, memeier coin for all.

## License
Lambocoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions
Any volunteers are free to contribute their own work on separate branches. Lambocoin is, and always will be, a completely open-source project built by the community.

## Branches
There are 2 types of branches in this repository:

- **master:** Stable, contains the latest version for the "average user"
- **development:** Unstable, contains new code which may bring bugs and glitches. Not recommended for most users.

## Lambocoin Supply
There will be approximately 1,000,000,000 coins at launch (Summer 2018). Each subsequent block will grant a number of coins determined by how many blocks have previously been mined. This is to encourage miners to continue to secure the network and make up for lost wallets on hard drives/phones/lost encryption passwords/etc.

## Block Rewards
Blocks 1–99,999: 0–10,000 Lambocoin 

Blocks 100,000–144,999: 0–5,000 Lambocoin

Blocks 145,000–199,999: 2,500 Lambocoin

Blocks 200,000–299,999: 1,250 Lambocoin

Blocks 300,000–399,999: 625 Lambocoin

Blocks 400,000–499,999: 300 Lambocoin

Blocks 500,000+: 100 Lambocoin

## Building lambocoin
Documents will be added later to guide you through building lambocoin's executables.



Development tips and tricks
---------------------------

**Compiling for debugging**

Run configure with the --enable-debug option, then make.

**debug.log**

If the code is behaving strangely, take a look in the debug.log file in the data directory;
error and debugging messages are written there.

The -debug=... command-line option controls debugging; running with just -debug will turn
on all categories (and give you a very large debug.log file).

The Qt code routes qDebug() output to debug.log under category "qt": run with -debug=qt
to see it.

**testnet and regtest modes**

If your tests require multi-machine/internet usage, run with the -testnet option to use fake lambocoins on the test network.

If you are testing something that can run on one machine, run with the -regtest option.
