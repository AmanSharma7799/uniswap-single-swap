# 🦄 Uniswap Single Swap Contract

This Solidity smart contract enables single-token swaps using the [Uniswap V3 SwapRouter](https://docs.uniswap.org/contracts/v3/reference/periphery/interfaces/ISwapRouter). It allows swapping a fixed amount of LINK tokens to WETH (and vice versa) on Ethereum testnet or mainnet, depending on deployment.

---

## 📜 Contract Overview

The `SingleSwap` contract provides two main functions:

- `swapExactInputSingle`: Swap a fixed amount of input token (LINK) for as much output token (WETH) as possible.
- `swapExactOutputSingle`: Swap the minimum required amount of input token (LINK) to receive an exact amount of output token (WETH).
