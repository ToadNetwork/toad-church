# TOAD.Network Church?

## Introduction

TOAD.Network is an ecosystem of utilities and a community-driven organization built to solve common problems of Decentralized Finance. You can find more details about the project at [ToadNetwork DOCS](https://docs.toad.network)

## About this repository

This is the **Toad.Network Church** repository

Contains the code related to the toadnetwork church webpage, which allows you to interact with the church contract to both make TOAD donations to the church AND praise to the Toad to diseminate some Toad tokens among several lucky BSC holders.

When donating  (via the "Offerings" link and input control), an approval for the amount stated on the input control will be requested to your ERC20 wallet (hence it has to be connected to the site) and delivered to the church contract so that it is used on future praises.

When praising, a small amount of TOAD is spread between several random BSC Wallets.

TOAD BSC contract can be checked at The DOCS [here](https://docs.toad.network/reference/contract-addresses#usdtoad-contracts).

The church contract can be checked [here](https://docs.toad.network/reference/contract-addresses#toad-church-contract)

## ToDo tasks

1. Review current disemination code to change the checks from PCS contracts into something more interesting for current BSC SOTA (i.e. pick 10 random non-contract addresses from the latest block)
2. Include other chains into the praising facility
3. Prepare the chuch for community competitions that could enhance participation and show leaderboard on it