# Uniswap V2

[![Actions Status](https://github.com/Uniswap/uniswap-v2-periphery/workflows/CI/badge.svg)](https://github.com/Uniswap/uniswap-v2-periphery/actions)
[![npm](https://img.shields.io/npm/v/@uniswap/v2-periphery?style=flat-square)](https://npmjs.com/package/@uniswap/v2-periphery)

===================

Morpheus Labs forked this the source code from UniSwap as a reference protocol based on smart contract for providing Decentralized Swap functions like UniSwap. Users can explore, modify and test the protocol on Morpheus Labs SEED platform.

Since this is a GNU License, for SEED platform users or any users who need to fork or clone this UniSwap protocol need to explicitly fork from this repo.

===================

In-depth documentation on Uniswap V2 is available at [uniswap.org](https://uniswap.org/docs).

The built contract artifacts can be browsed via [unpkg.com](https://unpkg.com/browse/@uniswap/v2-periphery@latest/).

# Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`

The test suite includes testing the following smart contracts

1. ComputeLiquidityValue

Test cases include getLiquidityValue, getReservesAfterArbitrage and etc

2. FlashSwap

This contract implements methods for token swap
Test cases include token swap situations

3. OracleSimple

This contract implements methods for token pair governance and swap.
Test cases include mint, getInputPrice, swap, burn and etc

4. Others

  - SlidingWindowOracle
  - SwapToPrice
  - UniswapV2Migrator
  - UniswapV2Router