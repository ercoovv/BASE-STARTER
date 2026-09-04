# Call vs Delegatecall

## What is call?

call executes code in another contract using that contract's own storage and context.

## What is delegatecall?

delegatecall executes another contract's code while keeping the caller's storage and context.

## Key Difference

- call uses the target contract's storage
- delegatecall uses the calling contract's storage
- msg.sender behavior can differ
- delegatecall is commonly used in proxy systems

## Why It Matters

Understanding the difference is important for secure smart contract architecture.

## Base

Both call and delegatecall work on Base according to Ethereum-compatible EVM rules.

## Learning Goal

Understand when contract calls use external context and when they preserve the caller's context.
