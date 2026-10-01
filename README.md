# Decomplex

Embedded Solana wallets and account infrastructure for Web3 applications.

## Overview

Getting a new user into a Solana app usually means asking them to install a wallet extension, store a seed phrase, and buy SOL for fees before they can do anything. Decomplex is infrastructure for applications that want to remove those steps: the wallet lives inside the app, and the account behind it is managed for the user.

## Concepts

- **Embedded wallet** — a wallet created and used inside an application, tied to a familiar sign-in such as email, social login, or a passkey, instead of a separate extension and seed phrase.
- **Account infrastructure** — the layer around the key: the onchain accounts users transact from and what is built on top of them, such as fee sponsorship (Solana lets one account pay transaction fees for another), scoped permissions, and recovery.

## Status

Early stage. No code has been published in this repository yet.

## License

[Apache License 2.0](LICENSE)
