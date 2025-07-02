# DeFiLens

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/node-%3E%3D18.0.0-green.svg)](https://nodejs.org/)
[![TypeScript](https://img.shields.io/badge/typescript-%5E5.5.3-blue.svg)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/react-%5E18.3.1-blue.svg)](https://reactjs.org/)

**A professional benchmarking framework for cross-chain oracle performance in DeFi. The "Bloomberg Terminal" for oracle data.**

## 🎯 Overview

DeFiLens addresses the critical **Oracle Problem** in decentralized finance by providing standardized performance metrics and real-time analytics across multiple blockchain ecosystems. Built for financial institutions, DeFi protocols, and researchers who need data-driven oracle integration decisions.

**Why DeFiLens?** Traditional finance enjoys seamless market data access, but blockchains remain isolated from external information. DeFiLens bridges this gap with systematic oracle assessment across Ethereum, BSC, Polygon, and Avalanche.

## ✨ Core Features

### 🔍 **Cross-Chain Oracle Monitoring**
- **Multi-Provider Support**: Chainlink, Band Protocol, Tellor integration
- **Real-Time Price Feeds**: Live data from multiple blockchain networks
- **Arbitrage Detection**: Identify price discrepancies across chains
- **Professional Charts**: Candlestick, line, and volume analysis for market dynamics

### 🛡️ **Advanced Security Framework**
- **Cryptographic Verification**: ECDSA signatures, Merkle proofs, ZK-proof validation
- **Attack Detection**: Sandwich attacks, flash loans, front-running, MEV exploits
- **Network Health**: Node distribution, consensus participation, validator uptime
- **6-Layer Security Scoring**: MEV Protection (85%), Consensus (72%), Cryptographic (95%), Flash Loan Resistance (88%), Front-Running Protection (78%), Price Manipulation (65%)

### 📊 **Institutional-Grade Analytics**
- **Performance Benchmarking**: Response times, reliability scores, uptime statistics
- **Risk Assessment**: Automated scoring for oracle provider selection
- **Compliance Ready**: Transparency metrics for auditors and regulators
- **Data Integrity**: SHA-256 verification, AES encryption monitoring

## 🚀 Quick Start

### Prerequisites
- **Node.js 18+** ([Install guide](https://nodejs.org/))
- **npm/yarn/bun**

### Installation & Setup

```bash
# Clone and setup
git clone https://github.com/BipinRajC/DeFiLens.git
cd DeFiLens
npm install

# Start development server
npm run dev
```

**Access at: http://localhost:8080**

### Configuration (Optional)
```env
# .env file for custom RPC endpoints
VITE_ETHEREUM_RPC_URL=https://eth.llamarpc.com
VITE_BSC_RPC_URL=https://bsc-dataseed1.binance.org
VITE_POLYGON_RPC_URL=https://polygon-rpc.com
VITE_AVALANCHE_RPC_URL=https://api.avax.network/ext/bc/C/rpc
```

## 📖 Usage

### Getting Started
1. **Select Networks**: Choose source/target blockchains
2. **Pick Oracle Provider**: Chainlink, Band Protocol, or Tellor
3. **Monitor Metrics**: Real-time security scores and performance data
4. **Analyze Opportunities**: Detect arbitrage and assess risk

### Key Components
- **Oracle Controls**: Network selection, provider switching, refresh management
- **Security Dashboard**: Multi-layer threat monitoring and cryptographic verification
- **Market Analysis**: Bitcoin trading charts with volume indicators
- **Performance Metrics**: Latency, uptime, and reliability tracking

## 🏗️ Technical Architecture

**Frontend**: React 18 + TypeScript + Vite  
**UI Framework**: shadcn/ui + Tailwind CSS  
**Blockchain**: Web3.js + Ethers.js  
**Data Sources**: Chainlink contracts, Band Protocol API, RPC endpoints  
**Security**: Multi-layer cryptographic verification and attack detection


### Key Oracle Contracts
- **BTC/USD (Ethereum)**: `0xF4030086522a5bEEa4988F8cA5B36dbC97BeE88c`
- **ETH/USD (Ethereum)**: `0x5f4eC3Df9cbd43714FE2740f5E3616155c5b8419`
- **BNB/USD (BSC)**: `0x0567F2323251f0Aab15c8dFb1967E4e8A7D42aeE`


## 🎯 Use Cases

**Financial Institutions**: Risk management, compliance monitoring, operational efficiency  
**DeFi Protocols**: Oracle provider selection, security assessment, cost optimization  
**Trading Firms**: Arbitrage detection, cross-chain opportunities, market analysis  
**Researchers**: Performance benchmarking, academic analysis, protocol comparison  
**Auditors**: Transparency metrics, security verification, regulatory compliance

## 🐛 Troubleshooting

**Port conflicts**: Modify `vite.config.ts` or kill process on port 8080  
**RPC failures**: Check network connection, try alternative providers  
**Chart issues**: Clear browser cache, verify JavaScript console

