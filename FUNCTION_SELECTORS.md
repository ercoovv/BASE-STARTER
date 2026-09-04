# Function Selectors

## What is a Function Selector?

A function selector is the first four bytes of the hash of a Solidity function signature.

## Common Uses

- Identify which contract function should run
- Build low-level contract calls
- Decode transaction calldata
- Work with proxies
- Understand ABI-based interactions

## Why It Matters

Function selectors help the EVM determine which smart contract function a transaction is trying to call.

## Base

Base uses the same Ethereum-compatible function selector rules.

## Learning Goal

Understand how smart contract function calls are identified at the byte level.
