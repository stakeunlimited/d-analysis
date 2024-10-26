
# D'Analysis

## Overview
Welcome to D’analysis—the first DeFi security analyzer tailored specifically for web3 newcomers! DeFi’s high returns are often overshadowed by concerns about complexity and risk, especially after events like the FTX crash. D’analysis changes this narrative by making DeFi a safer, more transparent alternative to traditional finance. Focusing on DEX stablecoin pools, we provide high returns without the worry of impermanent loss.

D’analysis assesses risk across four key dimensions: chain, protocol, pool, and stablecoins. Using Gen AI, our tool scans hundreds of pages of security audits in seconds, offering insights that are deep, precise, and actionable. Try it out: [D'Analysis Web App](https://danalysis.vercel.app/)

![D'Analysis Screenshot](https://i.imgur.com/5OWa4kA.png)

---

## Repositories
D'Analysis includes three main modules, organized as submodules in this repository:

1. **Backend**: Manages API and risk analysis algorithms.
2. **Frontend**: Provides the user interface for risk analysis.
3. **Stablecoin Volatility Analyzer (Python)**: Analyzes stablecoin volatility, providing insights into stablecoin stability.

---

## Getting Started

### Prerequisites
- Ensure you have [Node.js](https://nodejs.org/), [Yarn](https://yarnpkg.com/), and [Python 3](https://www.python.org/) installed on your system.

### Cloning with Submodules
Clone the repository with all submodules using:
```bash
git clone --recurse-submodules <repository-url>
```

Or, if you've already cloned without submodules, initialize them with:
```bash
git submodule update --init --recursive
```

---

## Build and Run

### Backend (API)

1. Create your environment file from the example:
   ```bash
   cp .env.example .env
   ```
2. Install dependencies and start the development server:
   ```bash
   yarn
   yarn start:dev
   ```

### Frontend

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the frontend:
   ```bash
   npm start
   ```

### Stablecoin Volatility Analyzer (Python)
For instructions on setting up the volatility analyzer, see the [README here](https://github.com/stakeunlimited/risk-analysis-volatility/blob/main/README.md).

---

## Contributing
We welcome contributions to enhance D'Analysis! Feel free to submit pull requests or open issues for any improvements or fixes.
