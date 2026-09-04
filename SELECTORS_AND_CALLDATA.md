# Selectors and Calldata

## How Do They Work Together?

A function selector identifies which smart contract function should run, while calldata contains the encoded inputs for that function.

## Transaction Structure

- The first four bytes identify the function
- The remaining bytes contain encoded arguments
- The contract reads this data during execution
- Wallets and applications generate calldata automatically

## Why It Matters

Understanding selectors and calldata helps explain how wallets communicate with smart contracts at a low level.

## Base

Base uses the same Ethereum-compatible calldata and function selector rules.

## Learning Goal

Understand how smart contract function calls are encoded and interpreted.
