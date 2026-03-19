<div align="center">

# DAILY-CHECKIN - Stacks Smart Contract

**Daily check-in rewards system on Stacks (Bitcoin L2)**

[![npm version](https://img.shields.io/npm/v/@giwaov/stacks-daily-checkin?style=for-the-badge)](https://www.npmjs.com/package/@giwaov/stacks-daily-checkin)
[![Build Status](https://github.com/giwaov/stacks-daily-checkin/actions/workflows/ci.yml/badge.svg)](https://github.com/giwaov/stacks-daily-checkin/actions/workflows/ci.yml)
[![Live on Mainnet](https://img.shields.io/badge/Stacks-Mainnet-brightgreen?style=for-the-badge&logo=bitcoin)](https://explorer.hiro.so/address/SP33C21DH86NQ56RYYY69CGD1146H4E5NHNM32W5P.daily-checkin-v1?chain=mainnet)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

</div>

## Overview

Daily check-in rewards system built with Clarity smart contracts on the Stacks blockchain.

## Contract

- **Contract Address**: `SP33C21DH86NQ56RYYY69CGD1146H4E5NHNM32W5P.daily-checkin-v1`
- **Network**: Stacks Mainnet

## Installation

```bash
npm install @giwaov/stacks-daily-checkin
```

## Usage

```typescript
import { openContractCall } from '@stacks/connect';
import { StacksMainnet } from '@stacks/network';

const network = new StacksMainnet();
const contractAddress = 'SP33C21DH86NQ56RYYY69CGD1146H4E5NHNM32W5P';
const contractName = 'daily-checkin-v1';
```

## License

MIT
