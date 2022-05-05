# HackMoney 2021 Compound Protocol Workshop Demo

This repository contains a very basic UI that uses the Compound Protocol. The app enables users to earn interest on their crypto assets by supplying them to the protocol. Users can also redeem their cTokens.

Youtube Livestream: https://youtu.be/49aDBZjK0uk

The app currently supports ETH, and during the workshop, I will walk through adding support for USDC. See the `support_usdc` branch for those code changes.

To run the web app locally, use npm to install [http-server](https://www.npmjs.com/package/http-server), and run it from the project root directory.

To grab the script for seeding USDC in your localhost test account, check out the [compound-supply-examples repository](https://github.com/compound-developers/compound-supply-examples/tree/master/seed-account-with-erc20) and also the [Supplying Assets to the Compound Protocol](https://medium.com/compound-finance/supplying-assets-to-the-compound-protocol-ec2cf5df5aa) quick start guide.

![Interest Rate App Screenshot](https://raw.githubusercontent.com/ajb413/compound-hackmoney-2021/master/screenshot.png)
