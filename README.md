# DeFiLens

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/node-%3E%3D18.0.0-green.svg)](https://nodejs.org/)
[![TypeScript](https://img.shields.io/badge/typescript-%5E5.5.3-blue.svg)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/react-%5E18.3.1-blue.svg)](https://reactjs.org/)

**Real-time cross-chain oracle monitoring and security analysis dashboard for DeFi protocols and financial institutions.**

## 🎯 Overview

DeFiLens provides comprehensive monitoring of oracle networks across Ethereum, BSC, Polygon, and Avalanche. Track price feeds, detect security threats, and identify arbitrage opportunities with professional-grade analytics.

## ✨ Key Features

### 🔍 **Multi-Chain Oracle Monitoring**
- Real-time price feeds from Chainlink, Band Protocol, and Tellor
- Cross-chain price comparison and arbitrage detection
- Interactive candlestick charts with technical indicators
- Live Bitcoin trading charts with volume analysis

### 🛡️ **Advanced Security Analysis**
- **6-Category Security Scoring**: MEV Protection (85%), Consensus Mechanism (72%), Cryptographic Security (95%), Flash Loan Resistance (88%), Front-Running Protection (78%), Price Manipulation Detection (65%)
- **Attack Detection**: Sandwich attacks, front-running, and MEV exploit monitoring
- **Cryptographic Verification**: ECDSA signatures, Merkle proofs, ZK-proof validation
- **Real-time Threat Alerts**: Automated security notifications

### 📊 **Professional Dashboard**
- Modern UI with shadcn/ui and Tailwind CSS
- Dark/Light mode support
- Responsive design for all devices
- Real-time data streaming (2.5s updates)

## 🚀 Quick Start

### Prerequisites
- **Node.js 18+** ([Install with nvm](https://github.com/nvm-sh/nvm))
- **npm** or **bun**
- **Git**

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/defilens.git
cd defilens

# Install dependencies
npm install
# or
bun install

# Start development server
npm run dev
# or
bun run dev
```

**Access the dashboard at: http://localhost:8080**

### Environment Setup (Optional)
Create `.env` file for custom RPC endpoints:
```env
VITE_ETHEREUM_RPC_URL=https://eth.llamarpc.com
VITE_BSC_RPC_URL=https://bsc-dataseed1.binance.org
VITE_POLYGON_RPC_URL=https://polygon-rpc.com
VITE_AVALANCHE_RPC_URL=https://api.avax.network/ext/bc/C/rpc
```

## 📖 Usage

1. **Select Chains**: Choose source and target blockchains from dropdowns
2. **Pick Oracle Provider**: Switch between Chainlink, Band Protocol, or Tellor
3. **Monitor Security**: View real-time security scores and threat alerts
4. **Analyze Trading**: Use Bitcoin charts for market analysis and arbitrage opportunities

### Key Components
- **Oracle Controls**: Chain selection, provider switching, refresh controls
- **Real-Time Charts**: Live price feeds with customizable timeframes
- **Security Dashboard**: Comprehensive security analysis with threat monitoring
- **Performance Metrics**: Oracle uptime, response times, reliability scores

## 🔧 Technical Stack

- **Frontend**: React 18 + TypeScript + Vite
- **UI**: shadcn/ui + Radix UI + Tailwind CSS
- **Charts**: Recharts for data visualization
- **Blockchain**: Web3.js + Ethers.js
- **Data Sources**: Chainlink contracts, Band Protocol API, RPC endpoints
