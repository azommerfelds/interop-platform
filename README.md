# Crosschain messaging protocol

## Overview

In the evolving crypto market, blockchain interoperability is crucial for enabling asset swaps and cross-chain communication. This project aims to develop a cross-chain messaging protocol that ensures seamless communication and asset transfer between blockchains.

## Objective

The objective is to build and launch a secure, scalable cross-chain messaging protocol. The protocol will focus initially on EVM-based blockchains and later expand to other networks. The approach prioritizes a permissioned network of attesters and relayers, with plans for gradual decentralization post-mainnet launch.

## Key components

- **Sender contract**: Integrates with smart contracts to securely emit and store messages on the source chain.
- **Attester**: Generates and signs Merkle proofs to verify message validity.
- **Relayer**: Transmits the message package, ensuring reliable delivery and modular design.
- **Receiver contract**: Verifies Merkle proofs and block headers on the destination chain.
- **Block header oracle**: Provides secure and timely block headers.
- **Block header storage contract**: Stores and provides trusted block headers for validation.

![Architecture Diagram](architecture.svg)

## Feedback

azommerfelds@gmail.com
