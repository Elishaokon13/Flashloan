# Large Tether Transfer Agent

## Description

This agent detects transactions with large Tether transfers

## Supported Chains

- Ethereum
- List any other chains this agent can support e.g. BSC

## Alerts

Describe each of the type of alerts fired by this agent

- Mev-1
  - Fired when a transaction contains a Tether transfer over 10,000 USDT
  - Severity is always set to "low" (mention any conditions where it could be something else)
  - Type is always set to "info" (mention any conditions where it could be something else)
  - Mention any other type of metadata fields included with this alert

## Test Data

The agent behaviour can be verified with the following transactions:

- 0x9996e780416829879b703f5d05ea1177ee6229cf408f18a4778df343a06a2c88 (141,000 USDT)
