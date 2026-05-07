# Security Policy

## Trading safety

This repository is research/simulation only until explicitly promoted.

Do not commit:

- private keys
- exchange API credentials
- wallet seed phrases
- `.env` files
- funded account tokens
- live trading configs

## Required live-trading gates

Before any real-money execution:

- paper-trade only for at least 24-48h
- enforce max spend outside the LLM
- require human approval for first live order
- log all model inputs/outputs and tool calls
- use read-only credentials until execution is deliberately enabled
- never let an LLM directly control wallet/private-key material

## Reporting issues

Open a private issue or contact Jeff/Null directly for security concerns.
