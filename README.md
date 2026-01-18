# cal-eco-platform-training

This repository is a **training-oriented copy** of the **cal-eco-platform** project,
originally authored by Michael McLaughlin and released under the MIT License.

It is used for learning, refactoring, and experimentation purposes, including
exploration of code structure, reliability improvements, and Web3-related
development patterns.

This repository is **not the canonical upstream project** and does not claim
original authorship of the initial codebase.

---

## Web3 Platform Overview

This project demonstrates a **full-stack Web3 platform** showcasing modern
blockchain integration, real-time features, and scalable application architecture.

The platform combines prediction markets, staking mechanisms, and exchange-style
dashboards, with seamless wallet integration and a robust RESTful backend.

---

## Wallet Connectivity Refactor (Training Focus)

Compared to the upstream baseline, this training repository includes a focused
refactor of wallet connectivity:

- WalletConnect v2 integration with explicit chain configuration (Mainnet / Sepolia)
- More robust activation flow across MetaMask, WalletConnect, and Coinbase
- Reduced runtime edge cases (chain mismatch, silent failures)
- Cleaner environment configuration via `.env.example`
- No change to application features, UI, or API surface

This work is intended for **learning and reliability hardening**, not feature
expansion.

---

## Key Features

- **Prediction Markets**: Bull/Bear prediction system with live price feeds and automated round management
- **Staking Platform**: Multiple staking plans with automated earnings calculation and distribution
- **External Integrations**: Multi-chain support with secure third-party connections and transaction handling
- **Exchange Dashboard**: Real-time market tracking, portfolio management, and analytics
- **Referral System**: Referral tracking, rewards calculation, and hierarchy management
- **Transaction History**: Comprehensive transaction logging with filtering and export
- **Admin Dashboard**: Administrative controls for monitoring and management
- **Support System**: Ticket-based support with message threading
- **Real-time Notifications**: Live updates and event broadcasting
- **Authentication & Security**: Secure authentication and session handling

---

## Architecture Highlights

- **Modular Design**: Clear separation of concerns (controllers, services, models)
- **Middleware Pattern**: Authentication, validation, and error handling layers
- **RESTful API**: Versioned routes with structured responses
- **Real-time Communication**: Bidirectional updates for live data
- **Blockchain Integration**: Secure wallet and transaction handling
- **State Management**: Global state patterns for complex flows
- **Type Safety**: Strong typing across the codebase
- **Error Handling**: Centralised error handling and logging

---

## Getting Started

### Prerequisites

- **Node.js** (v16 or higher)
- **npm** (or yarn)
- **Git**

---

### Installation

#### 1. Install Frontend Dependencies

```bash
npm install

