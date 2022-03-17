---
cover: .gitbook/assets/phantom-background.jpeg
coverY: -50.54759898904802
---

# Introduction

**Phantom** is a crypto wallet that can be used to manage digital assets and access decentralized applications on the [Solana](https://solana.com) blockchain.&#x20;

Phantom is currently available as:

* A [browser extension](https://phantom.app/download)
* An [iOS app](https://apps.apple.com/us/app/phantom-solana-wallet/id1598432977)
* An [Android app](https://play.google.com/store/apps/details?id=app.phantom) (in beta!)

At its core, Phantom works by creating and managing private keys on behalf of its users. These keys can then be used within Phantom to store funds and sign transactions.&#x20;

To interact with web applications, Phantom injects a `solana` object into the javascript context of every site the user visits. A given application may then interact with Phantom, and ask for the user's permission to perform transactions, through this injected object.

This documentation is intended for developers who are building applications with Phantom. To get help with using Phantom, please visit our [User Support Site](https://help.phantom.app).

