# Solidity tx.origin

## What is tx.origin?

tx.origin is a Solidity global variable that refers to the original externally owned account that started a transaction.

## Why It Matters

- It identifies the original transaction initiator
- It can differ from msg.sender
- It should not normally be used for authorization
- It can introduce security risks in contract logic
- Understanding it helps prevent phishing-style contract vulnerabilities

## Base

tx.origin behaves on Base just like on other Ethereum-compatible networks.

## Learning Goal

Understand the difference between tx.origin and msg.sender and why msg.sender is usually safer for access control.
