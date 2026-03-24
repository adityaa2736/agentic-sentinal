#  AgenticSentinel: The Autonomous DeFi Guardian

**AgenticSentinel** is a professional-grade, multi-feature AI monitoring platform designed to provide real-time intelligence for the Algorand DeFi ecosystem. It combines autonomous price tracking, risk analysis, and secure blockchain execution into a premium "Trading Terminal" experience.

---

##  Key Features

### 1. Real-Time Market Dashboard
- **Asset Hub**: Track ALGO, BTC, ETH, and Gold with live prices polled from official APIs.
- **Trend Intelligence**: Visual indicators (▲/▼) for 24h market performance.
- **Event Markers**: Visual markers on price charts to highlight historical "Flash Crashes" for AI risk assessment.

### 2.  Stock Exchange Trading Terminal
- **Split-Pane Layout**: A professional interface with "Market Analytics" (charts/volume/cap) and an "Execution Terminal" (order form).
- **Simulated Equities**: Trade AAPL, TSLA, NVDA, and more via simulated smart contracts.
- **Pera Wallet Integration**: Secure transaction signing with permanent logging to the Algorand Testnet.

### 3.  Blockchain Wallet Explorer
- **Global Search**: Audit any Algorand address to see live ALGO balances and asset inventories.
- **One-Click Sync**: Automatically sync with your connected Pera Wallet to instantly load your own blockchain profile.

### 4.  Real-Time Informing System
- **Toast Notifications**: Premium floating alerts for "Session Authorized" and "System Updates."
- **Low Balance Sentinel**: Automated warning system if your wallet balance drops below 5 ALGO.

### 5. Pro Architecture
- **Sidebar Navigation**: Fixed Sidebar (Glassmorphism) for instant switching between Market, Exchange, and Explorer.
- **Risk Ticker**: An infinite scrolling horizontal marquee for high-priority DeFi alerts.
- **AI Engine**: Continuous monitoring of price volatility and protocol risks.

---

##  Tech Stack

- **Frontend**: React.js 18+, Recharts, Lucide Icons, Glassmorphism UI (Vanilla CSS).
- **Wallet**: Pera Wallet Connect API, Algorand SDK.
- **Backend**: Node.js, Socket.io for live data streaming, Algod/Indexer APIs.
- **AI Service**: Python FastAPI, Scikit-learn, Pandas (Volatility & Trend Prediction).

---

##  Setup & Execution

### 1. Requirements
Ensure you have Node.js and Python 3.10+ installed.

### 2. Port Configuration
- **Frontend**: [http://localhost:5173](http://localhost:5173)
- **Backend API**: [http://localhost:5000](http://localhost:5000)
- **AI Service**: [http://localhost:8000](http://localhost:8000)

### 3. Launch the Sentinel
```powershell
# 1. Start AI Agent (ai_service/)
python main.py

# 2. Start Backend (backend/)
npm start

# 3. Start Frontend (frontend/)
npm run dev
```

---

##  Disclaimer
*This system is a proof-of-concept for Agentic AI in DeFi and uses the Algorand Testnet for all simulated activities.*
