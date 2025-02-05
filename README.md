# Stellar Explorer

[Stellar Explorer](https://steexp.com/)

[Build Status Soroban](https://nownodes.io/nodes)

A ledger Public explorer for [Pinetwork & Stellar Assets](https://stellar.expert/explorer/public/account/GCL2DTNZF6YTZAF2PUYT4M3L7AVB4ZGJHACGK2PUPLGCDX5QJKNJC7M3)


Closed Mainnet: [Pi Account](https://blockexplorer.minepi.com/mainnet/account/GBNTRPVIV5XF7W3QC6SSPJBE3KO5KOBFNNAFQVQLP54JUXMWABBPKNN4)

Open Mainnet: [Pi Account](https://steexp.com/account/GBNTRPVIV5XF7W3QC6SSPJBE3KO5KOBFNNAFQVQLP54JUXMWABBPKNN4)

Soroban Explorer: [Soroban Account](https://www.sorobanexp.com/blockchain/ac/account/GBNTRPVIV5XF7W3QC6SSPJBE3KO5KOBFNNAFQVQLP54JUXMWABBPKNN4)

## Resources

### Lists

| Resource     | URI                                          |
| ------------ | -------------------------------------------- |
| Operations   | [/operations](https://steexp.com/operations) |
| Transactions | [/txs](https://steexp.com/txs)               |
| Ledgers      | [/ledgers](https://steexp.com/ledgers)       |
| Payments     | [/payments](https://steexp.com/payments)     |
| Trades       | [/trades](https://steexp.com/trades)         |
| Effects      | [/effects](https://steexp.com/effects)       |

### Directory

| Resource  | URI                                        |
| --------- | ------------------------------------------ |
| Assets    | [/assets](https://steexp.com/assets)       |
| Anchors   | [/anchors](https://steexp.com/anchors)     |
| Exchanges | [/exchanges](https://steexp.com/exchanges) |

### Accounts

| Resource             | URI |
| -------------------- | --- |
| by Federated address | [/account/stellar\s2pdo*lobstr.co](https://steexp.com/account/s2pdo*lobstr.co) |
| by Public address    | [/account/GCL2DTNZF6YTZAF2PUYT4M3L7AVB4ZGJHACGK2PUPLGCDX5QJKNJC7M3](https://steexp.com/account/GCL2DTNZF6YTZAF2PUYT4M3L7AVB4ZGJHACGK2PUPLGCDX5QJKNJC7M3) |


#### Tabs

| Resource         | URI                                                                                                       |
| ---------------- | --------------------------------------------------------------------------------------------------------- |
| Balances Tab     | [/account/stellar\s2pdo*lobstr.co#balances](https://steexp.com/account/s2pdo*lobstr.co#balances)         |
| Payments Tab     | [/account/stellar\s2pdo*lobstr.co#payments](https://steexp.com/account/s2pdo*lobstr.co#payments)         |
| Offers Tab       | [/account/stellar\s2pdo*lobstr.co#offers](https://steexp.com/account/s2pdo*lobstr.co#offers)             |
| Trades Tab       | [/account/stellar\s2pdo*lobstr.co#trades](https://steexp.com/account/s2pdo*lobstr.co#trades)             |
| Effects Tab      | [/account/stellar\s2pdo*lobstr.co#effects](https://steexp.com/account/s2pdo*lobstr.co#effects)           |
| Operations Tab   | [/account/stellar\s2pdo*lobstr.co#operations](https://steexp.com/account/s2pdo*lobstr.co#operations)     |
| Transactions Tab | [/account/stellar\s2pdo*lobstr.co#transactions](https://steexp.com/account/s2pdo*lobstr.co#transactions) |
| Signing Tab      | [/account/stellar\s2pdo*lobstr.co#signing](https://steexp.com/accounts2pdo*lobstr.co#signing)           |
| Flags Tab        | [/account/stellar\s2pdo*lobstr.co#flags](https://steexp.com/account/s2pdo*lobstr.co#flags)               |
| Data Tab         | [/account/stellar\s2pdo*lobstr.co#data](https://steexpcom/account/s2pdo*lobstr.co#data)                  |

### Search

| Resource              | URI |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Federated address     | [/search/steexp\s2pdo*lobstr.co](https://steexp.com/search/s2pdo*lobstr.co) |
| Public address        | [/search/GCL2DTNZF6YTZAF2PUYT4M3L7AVB4ZGJHACGK2PUPLGCDX5QJKNJC7M3](https://steexp.com/search/GCL2DTNZF6YTZAF2PUYT4M3L7AVB4ZGJHACGK2PUPLGCDX5QJKNJC7M3) |
| Ledger                | [/search/10000000](https://steexp.com/search/10000000) |
| Transaction           | [/search/26a568681712a44a515b2c90dcfaadb3ed2c40dc60254638407937bee4767071](https://steexp.com/search/26a568681712a44a515b2c90dcfaadb3ed2c40dc60254638407937bee4767071) |
| Asset Code            | [/search/NGN](https://steexp.com/search/s2pdo) |
| Anchor Name           | [/search/ripplefox](https://steexp.com/search/s2pdo) |
| Anchor Name (Partial) | [/search/fox](https://steexp.com/search/s2pdo) |

### Misc

| Resource    | URI |
| ----------- | --- |
| Transaction | [/tx/26a568681712a44a515b2c90dcfaadb3ed2c40dc60254638407937bee4767071](https://steexp.com/tx/26a568681712a44a515b2c90dcfaadb3ed2c40dc60254638407937bee4767071) |
| Ledger      | [/ledger/10000000](https://steexp.com/ledger/10000000) |
| Anchor      | [/anchor/apay.io](https://steexp.com/anchor/apay.io) |
| Asset       | [/asset/NGN](https://steexp.com/asset/NGN) |

## Exploring Private / Local Development Networks<a name="private-networks"></a>

steexp will connect to a local horizon instance at http://localhost:8000 by default. If your running a local private network for development this is quite handy for browsing your changes to the ledger.

Alternatively you can run locally connecting to the testnet or public network horizon instances. To do this define these aliases to localhost:

```
127.0.1.1  testnet.local     # for steexp use testnet horizon
127.0.1.1  publicnet.local   # for steexp use mainnet horizon
```

Navigate to http://testnet.local:3000 or http://publicnet.local:3000 to select the network your interesting in exploring.

## Development

See the section [Exploring Private / Local Development Networks](#private-networks) for connecting to different backend networks. By default steexp will look for a local instance of horizon.

Start:

```
npm i && npm start
```

Test:

```
npm i && npm test
```

Build:

```
npm i && npm run build
```

## Languages

Use the language selector in the top right corner to change the language.

Translation files are here:
https://github.com/chatch/stellarexplorer/tree/master/src/languages

Submit pull requests with new languages or languages fixes there.
