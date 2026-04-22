# 🔁 Binox Swap

**Binox Swap** is a decentralized exchange (DEX) built on **BNB Smart Chain (BSC)**, part of the **BNB Chain ecosystem**.

It enables users to **swap any BEP-20 tokens instantly**, with **ultra-low fees**, deep liquidity routing, and seamless Web3 integration.

🌐 Website: https://binoxswap.sbs  

---

# 🚀 Technology Stack

- **Blockchain:** BNB Smart Chain (BSC) — BNB Chain ecosystem  
- **Smart Contracts:** Solidity ^0.8.20  
- **DEX Logic:** Uniswap V2-style router integration  
- **Frontend:** React.js  
- **Web3 Integration:** ethers.js  
- **Development:** Hardhat + OpenZeppelin  

---

# 🌐 BNB Chain Ecosystem

Binox Swap operates on **BNB Smart Chain (BSC)**.

### Supported Networks

| Network | Chain ID |
|--------|--------|
| **BNB Smart Chain Mainnet (BSC)** | 56 |
| **BNB Smart Chain Testnet** | 97 |
| **opBNB (Future Support)** | Coming Soon |

Future expansion may include:
- **BNB Greenfield**
- Multi-chain support (ETH, Polygon, Arbitrum)

---

# 📜 Contract Address

| Network | Contract |
|--------|--------|
| **BNB Smart Chain (BSC)** | `0x032e8e2AfE6286E39AdBE008a9EbA05b9E879Ea5` |

---

# ⚡ Core Features

## 🔄 Token Swapping
- Swap **any BEP-20 token**
- Supports **Token ↔ Token**, **BNB ↔ Token**
- Works with all liquidity pools (PancakeSwap-compatible)

---

## 💸 Ultra Low Fees
- Dynamic swap fee system  
- Default fee: **0.5% (max 5%)**  
- Fees sent to project treasury  

---

## ⚡ Smart Routing Engine
- Uses router to fetch best price  
- Real-time output estimation  
- Supports fee-on-transfer tokens  

---

## 🔒 Secure Smart Contract

Security features:

- Reentrancy protection  
- Safe ERC20 transfers  
- Owner-controlled parameters  
- Emergency withdrawal functions  

---

## 💧 Liquidity Support

Users can:

- Add liquidity (Token + Token)  
- Add liquidity (Token + BNB)  
- Use existing DEX pools  

---

# ⚙️ Key Functions

## Swap Function
```solidity
function swapTokens(
    address tokenA,
    address tokenB,
    uint amountIn,
    uint amountOutMin,
    uint deadline,
    bool feeOnTransfer
)

#bnb #BNB #opBNB 