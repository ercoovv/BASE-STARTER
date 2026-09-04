# Solidity selfdestruct

## What is selfdestruct?

selfdestruct is a Solidity-related EVM operation historically used to remove contract code and send its remaining ETH to another address.

## Important Note

Its behavior has changed over time and modern Ethereum-compatible networks have restricted how it works.

## Why It Matters

- It is a low-level EVM concept
- Its behavior depends on protocol rules
- Developers should not rely on it for ordinary contract lifecycle management
- Understanding it helps with legacy smart contracts
- It is relevant when studying EVM behavior

## Base

Base follows Ethereum-compatible EVM rules, including modern selfdestruct behavior.

## Learning Goal

Understand why selfdestruct is considered a legacy feature and should be used with caution.
