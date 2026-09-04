# Reentrancy Basics

## What is Reentrancy?

Reentrancy is a smart contract vulnerability where an external contract calls back into the original contract before the first operation has finished.

## Why It Matters

- Can lead to repeated withdrawals
- May break expected contract logic
- Can put funds at risk
- Is a well-known smart contract security issue
- Requires careful state management

## Common Protection

A common defense is to update internal state before making external calls and use reentrancy guards when appropriate.

## Base

Smart contracts on Base can face the same reentrancy risks as contracts on other Ethereum-compatible networks.

## Learning Goal

Understand why external calls must be handled carefully in Solidity.
