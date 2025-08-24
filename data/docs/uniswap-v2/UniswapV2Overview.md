# Uniswap V2 Overview

Uniswap V2 is an automated market maker (AMM) protocol that facilitates token swaps on Ethereum.

## Key Components

- **UniswapV2Factory**: Creates and manages Uniswap pairs
- **UniswapV2Pair**: Implements the core AMM logic and holds reserves
- **UniswapV2Router02**: Provides user-friendly functions for interacting with pairs

## Core Concepts

### Constant Product Formula

Uniswap V2 uses the constant product formula: x * y = k

Where:
- x is the reserve of token A
- y is the reserve of token B
- k is a constant value

This formula ensures that the product of the reserves remains constant after trades.

### Liquidity Provision

Users can provide liquidity by depositing both tokens in the correct ratio.
In return, they receive LP tokens representing their share of the pool.

### Swapping

When users swap tokens, they pay a 0.3% fee that goes to liquidity providers.
The price impact depends on the size of the swap relative to the pool reserves.

### Price Oracle

Uniswap V2 includes a time-weighted average price (TWAP) oracle that can be used
to determine the average price of a token over time.
