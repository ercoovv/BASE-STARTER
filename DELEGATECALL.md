# Solidity Delegatecall

## What is Delegatecall?

Delegatecall is a low-level Solidity feature that allows one contract to execute code from another contract while keeping the original contract's storage and context.

## Common Uses

- Proxy contracts
- Upgradeable contract systems
- Reusable contract logic
- Modular smart contract architectures

## Why It Matters

Delegatecall is powerful but must be used carefully because it can modify the calling contract's storage.

## Base

Delegatecall works on Base just like on other Ethereum-compatible networks.

## Learning Goal

Understand how contracts can reuse external logic while preserving their own execution context.
