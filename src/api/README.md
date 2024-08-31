# Overview

This page explains everything you need to know about the DogSwap Subgraph. The DogSwap Subgraph listens for events from one or more data sources \(Smart Contracts\) on the MintMe Blockchain. It handles indexing and caching of data which can later be queried using an exposed GraphQL API, providing an excellent developer experience.

### The Graph

The DogSwap Subgraph is powered by [The Graph](https://thegraph.com).

> The Graph is a protocol for building decentralized applications \(dApps\) quickly on smartBCH and IPFS using GraphQL.

### Data Sources

MasterChef - 0x4f79af8335d41A98386f09d79D19Ab1552d0b925

Factory - 0x86818c666b90f6f4706560afc72c2c2fa7b9c74a

### Resources

[DogSwap Subgraph Explorer](https://thegraph.mistswap.fi/subgraphs/name/mistswap/exchange/graphql?query=%7B%0A%20%20pairs%20(orderBy%3AreserveUSD%2C%20orderDirection%3Adesc)%20%7B%0A%20%20%20%20id%0A%20%20%20%20token0%20%7B%0A%20%20%20%20%20%20id%0A%20%20%20%20%7D%0A%20%20%20%20token1%20%7B%0A%20%20%20%20%20%20id%0A%20%20%20%20%7D%0A%20%20%20%20token0Price%0A%20%20%20%20token1Price%0A%20%20%20%20volumeUSD%0A%20%20%20%20untrackedVolumeUSD%0A%20%20%20%20reserve0%0A%20%20%20%20reserve1%0A%20%20%20%20reserveUSD%0A%20%20%20%20reserveETH%0A%20%20%20%20trackedReserveETH%0A%20%20%7D%0A%7D)

[DogSwap Subgraph Source](https://github.com/dogtoken/dogswap-subgraph)

[The Graph](https://thegraph.com/docs)

[GraphQL](https://graphql.org)

### Caveats

::: warning
The DogSwap Subgraph is not intended to be used as a data source for structuring transactions \(contracts should be referenced directly for the most reliable live data\).
:::

