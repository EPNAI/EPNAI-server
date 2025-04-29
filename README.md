# EPNAI
![EPNAI](https://github.com/user-attachments/assets/24955be0-6c7c-456e-b8b2-7312701896b0)

## Overview
Reference server implementation for the Machine-Centric Protocol (EPNAI) on Solana. This server handles context metadata, wallet integration, and bridges between agents and off-chain services.

## Features
- **Context Metadata**: Loading and caching of context definitions
- **Wallet Integration**: Support for Solana wallets (Phantom, Backpack, etc.)
- **Agent Bridge**: Connection layer between agents and off-chain services
- **API Endpoints**: RESTful and WebSocket interfaces for agent communication

## Development Setup
```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Run tests
npm test
```

## Repository Structure
- `/src` - Server implementation including API routes and service integrations
- `/tests` - Unit and integration tests
- `/.github` - CI/CD workflows

## Links
- [Documentation](../EPNAI-docs)
- [Core Protocol](../EPNAI-core)
- [Agents](../EPNAI-agents)
- [Examples](../EPNAI-examples)
