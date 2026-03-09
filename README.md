# 🔐 Mini Task 2 — Blockchain Platform Comparison & Analysis

A structured technical comparison of three major blockchain architectures — Ethereum, Hyperledger Fabric, and R3 Corda — analysed across consensus mechanisms, performance, permission models, and real-world use cases.

---

## 📊 Platform Comparison Table

| Blockchain | Type | Consensus | Permission Model | Speed (TPS) | Smart Contracts | Best For |
|---|---|---|---|---|---|---|
| **Ethereum** | Public | PoS (Proof of Stake) | Permissionless | 15–30 (100+ with L2) | Solidity, Vyper | DeFi, NFTs, dApps |
| **Hyperledger Fabric** | Private | Pluggable (Kafka, Raft) | Permissioned | 1,000+ | Go, Java, JavaScript | Enterprise B2B, Supply Chain |
| **R3 Corda** | Consortium | Notary-based (Pluggable) | Permissioned | 200–500 | Kotlin, Java | Inter-bank Finance, Trade |

---

## 📝 Technical Analysis

### Ethereum (Public)
- **Strengths:** Open access, strong smart contract ecosystem (Solidity/Vyper), EVM compatibility, large developer community
- **Weaknesses:** Lower base throughput (~30 TPS), higher gas fees, less privacy
- **Best for:** Decentralised applications, DeFi protocols, NFT platforms

### Hyperledger Fabric (Private)
- **Strengths:** High throughput (1,000+ TPS), permissioned access, modular consensus (Kafka/Raft), channel-based data privacy
- **Weaknesses:** No native token, significant setup overhead, less decentralised
- **Best for:** Enterprise B2B (supply chain, healthcare, logistics)

### R3 Corda (Consortium)
- **Strengths:** Financial-grade security, legal-prose smart contracts (Kotlin/Java), notary-based consensus for trusted settlement
- **Weaknesses:** Moderate throughput (~500 TPS), limited to known participants
- **Best for:** Inter-bank transactions, trade finance, regulated industries

---

## 🎯 Platform Selection by Use Case

| Use Case | Best Match | Key Technical Reasons |
|---|---|---|
| **Decentralised App (dApp)** | Ethereum | EVM compatibility · Layer 2 scaling · ERC-20/721 token standards · MetaMask/OpenZeppelin ecosystem |
| **Supply Chain Network** | Hyperledger Fabric | 1,000+ TPS · Private channels · Permissioned access · No crypto overhead |
| **Inter-Bank Finance** | R3 Corda | Notary-based validation · UTXO model · Legal-prose contracts · Regulatory compliance |

---

## 💡 Key Takeaway

Each blockchain solves a different trust problem:
- **Ethereum** — trust through decentralisation (no central authority)
- **Hyperledger Fabric** — trust through permissioning (only verified participants)
- **R3 Corda** — trust through legal enforceability (contracts with real-world standing)

The right choice depends on who needs to trust whom, how fast transactions need to settle, and how much privacy the network requires.

---

## 📌 Context

Part of a structured blockchain learning path — building theoretical understanding of different architectures before practical implementation on Ethereum, Polygon, and ICP.
