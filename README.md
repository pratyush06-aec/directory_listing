# Stellar Business Directory (Next-Gen V16)

A decentralized Web3 application built on the **Stellar Soroban Smart Contract** network to create, verify, manage, and query a global directory of businesses. 

## 🌌 Next Generation UI
This application features a fully custom-built, high-performance Dark Mode UI that uses native Math and CSS to compute 3D tilts and dynamic "heat glow" spotlight effects—*no cumbersome animation libraries required*. 

### Application Walkthrough

The project provides an immersive visual experience. Let's take a look:

**1. Live UI Recording (Hover Effects & Heat Glow)**  
![UI Recording](./public/demo.webp)  
*Watch the hover-glow border effects follow the pointer alongside the 3D Perspective shifts!*

**2. Preview Design Concept**  
![High Fidelity Preview](./public/preview.png)

---

## 🛠️ Technology Stack
- **Frontend Core**: React 19, Vite, Javascript
- **Styling**: Pure CSS (Glassmorphism, CSS Custom Properties, Native 3D Transforms)
- **Web3 Integration**: `@stellar/freighter-api`, `@stellar/stellar-sdk`

---

## 🚀 Features

### **1. 3D "Landing Page" Experience**
The application now launches into an immersive, deep-space dark mode Splash Page. Hovering over the entry card will dynamically orient the element along an `X/Y` coordinate grid toward your mouse.

### **2. Deploy & Manage Listings**
Directly interacting with the Soroban smart contracts, you can:
- Initialise a new business (Name, Category, Descriptions, Location, Site).
- Perform on-chain updates to records.
- Deactivate Profiles securely via owner authentication.

### **3. Peer Verification & Rating**
Any verified account on the network can run Verification algorithms to approve listings, and submit a 1-to-5 star rating representing the trustworthiness/quality of the business on the Stellar chain.

### **4. "Hacker-Style" Network Terminal**
Watch live JSON payloads and error outputs stream directly into the animated, mocked macOS terminal block to provide a seamless debugging experience natively inside the Web3 layout.

---

## 💻 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) matches `latest`
- [Freighter Wallet](https://www.freighter.app/) Browser Extension

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository_url>
   cd my-stellar-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the Development Server:**
   ```bash
   npm run dev
   ```

4. You can freely interact with the demo by accessing `http://localhost:5173`. Ensure your Freighter wallet is on the Stellar Testnet!

---

*Authored by Antigravity advanced agent for Stellar Soroban V16 Protocol.*
