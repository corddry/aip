---
title: Add Frax to Aave V3
status: WIP
author: Jack Corddry (@corddry)
shortDescription: Add Frax Stablecoin to Aave V3 on Polygon, Fantom, and Avalanche, Optimism, and Arbitrum
discussions: https://governance.aave.com/t/add-frax-as-asset-to-aave-v3-markets/7860
created: 2022-06-24
---

## Simple Summary

Add Frax Stablecoin to Aave V3 on Polygon, Fantom, and Avalanche, Optimism, and Arbitrum in Efficiency and Isolation mode.

## Abstract

FRAX is the inventor and first fractional stablecoin that uses a hybrid of algorithmic and collateralized mechanisms to stay on price target. FRAX is currently the #5 largest stablecoin by market cap and has never lost peg in its existence (defined as more than 1 cent price deviation on each side).

FRAX currently has the largest Curve pool on Ethereum mainnet and is a Uniswap top 10 token. Additionally, FRAX has already been successfully lent out on Aave v2 on ETH mainnet for many months and is a popular borrowable stablecoin with no issues of unpegging or economic problems.

FRAX is also already deployed natively on Polygon, Fantom, Avalanche, Optimism, and Arbitrum where Aave V3 resides (as well as 11 other chains making FRAX the most cross chain native stablecoin on the market).

## Motivation

Frax being a decentralized stablecoin is a good fit to be used as borrow assets as an alternative to currently existing stablecoins supported by the Aave Protocol.
With V3 emode, FRAX is great fit to join a stablecoin emode that will both have potential to increase Aave & FRAX volume while contributing to the stability of the FRAX asset. Additionally, FRAX can use its Lending AMO (similar to Maker’s DAI Direct Deposit Module) to mint protocol controlled FRAX to be lent out on Aave markets. FRAX already does this with an Aave Lending AMO on ETH mainnet to great success. We can commit to deploying similar Aave Lending AMOs to Aave v3 after FRAX is listed.

## Specification

V3 Efficiency mode stablecoins: 97% LTV, 98% Liquidation threshold, 5% reserve factor
V3 Isolation mode: 75% LTV, 80% liquidation threshold, 5% reserve factor, $50M initial debt ceiling

## Rationale

Expanding FRAX to Aave V3 has the potential to benefit both Aave & FRAX, increasing volume of both protocols, increasing FRAX stability, and bringing tons of usage to Aave V3 through the use of a FRAX lending AMO.

## Implementation

Add payload, oracle, etc addresses here

The implementations must be completed before any AIP is given status "Implemented", but it need not be completed before the AIP is "Approved". While there is merit to the approach of reaching consensus on the specification and rationale before writing code, the principle of "rough consensus and running code" is still useful when it comes to resolving many discussions of API details.

Also potentially add a references section

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).