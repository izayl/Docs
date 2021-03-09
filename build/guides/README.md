---
description: This section contains helpful guides for interacting with Zapper APIs.
---

# Guides

If you'd like to contribute a guide, please reach out to us on [Discord](https://discord.com/invite/5C4wxPr) or [Twitter](https://twitter.com/zapper_fi)

## Transactions API

Assembling a Zap transaction is simple to do with the Transactions API. Simply provide basic details like the token to sell, pool or vault to interact with, and token quantities to send and the API will assemble and return an easy to consume Zap transaction for you to use in apps or smart contracts. The same patterns shown in these guides can be applied to all of the [Zaps](../smart-contracts.md) offered by Zapper

* The [Yearn Zap In guide](yearn-zap-in.md) demonstrates how to create an easy to consume transaction object for interacting with Zaps with web3 or in your smart contracts directly.

## Data API

The same patterns shown here can be used for any of Zapper's [supported platforms](https://zapper.fi/protocols).

* The Yearn [Vault Stats guide](yearn-vault-stats.md) shows you how to pull data from the Zapper Data API. Vault stats includes platforms whose deposits are used for automated farming strategies \(e.g. Yearn, Harvest, Pickle, etc.\)
* The [Sushiswap Pool Stats guide ](sushiswap-pool-stats.md)shows you how to get pool data from the Zapper Data API. Pool stats includes platforms whose deposits are pooled as liquidity for exchanges \(e.g. Sushiswap, Uniswap, Balancer, etc.\)
* Fetching user balances for Zapper's supported platforms is also possible. Check out the [Curve User Balances Guide](curve-user-balances.md) for an example.


