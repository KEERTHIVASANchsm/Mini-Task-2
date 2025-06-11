# Mini-Task-2

1. Create a comparison table or markdown sheet with the following columns for each platform:

  Blockchain Platform Comparison

| Blockchain Name      | Ethereum (Public)           | Hyperledger Fabric (Private) | R3 Corda (Consortium)        |
|----------------------|-----------------------------|------------------------------|------------------------------|
| **Type**             | Public                      | Private                      | Consortium                   |
| **Consensus**        | PoS (Proof of Stake)        | Pluggable (Kafka, Raft)      | Notary-based (Pluggable)     |
| **Permission Model** | Open (Permissionless)       | Permissioned                 | Permissioned                 |
| **Speed (TPS)**      | 15–30 (100+ with L2)        | 1,000+                       | 200–500                      |
| **Smart Contracts**  | Yes (Solidity, Vyper)       | Yes (Go, Java, JavaScript)   | Yes (Kotlin, Java)           |
| **Token Support**    | Native (ETH) + ERC-20/721   | No native token              | Optional (CBDC, Custom)      |
| **Use Case**         | DeFi, NFTs, dApps           | Enterprise B2B, Supply Chain | Inter-bank Finance, Trade    |
| **Key Feature**      | EVM, Large Dev Ecosystem    | Channels for Privacy         | Legal Prose in Contracts     |

2. Write a Short Report (150–200 words):
 
(1) Compare and contrast the technical capabilities of each.
      
      Ethereum (Public):

          Strengths: Open access, strong smart contract support (Solidity/Vyper), large developer ecosystem, EVM compatibility.

          Weaknesses: Lower throughput (~30 TPS base layer), higher gas fees, less privacy.

          Best for: Decentralized applications (dApps), DeFi, NFTs.

      Hyperledger Fabric (Private):

          Strengths: High throughput (1,000+ TPS), permissioned access, modular consensus (Kafka/Raft), channel-based privacy.

          Weaknesses: No native token, requires setup effort, less decentralized.

          Best for: Enterprise B2B solutions (supply chain, healthcare).

      R3 Corda (Consortium):

          Strengths: Financial-grade security, legal-prose smart contracts (Kotlin/Java), notary-based consensus for trusted validation.

          Weaknesses: Moderate throughput (~500 TPS), limited to known participants.

          Best for: Inter-bank transactions, trade finance, regulated industries.

(2) Which platform would you choose for :

  1. decentralized app (dApp)?

      Choice: Ethereum

      Justification:

          Public accessibility ensures broad user adoption.

          EVM compatibility allows for easy deployment of smart contracts (Solidity/Vyper).

          Strong ecosystem (MetaMask, OpenZeppelin, Layer 2 scaling solutions).

          Native token (ETH) and ERC standards (ERC-20, ERC-721) enable tokenization.

  2. Which platform would you choose for a supply chain network among known partners?

       Choice: Hyperledger Fabric

        Justification:

           Permissioned access ensures only authorized participants join.

           High throughput (1,000+ TPS) supports real-time tracking.

           Channel-based privacy allows selective data sharing.

           No native token needed, focusing purely on enterprise logistics.

  3. Which platform would you choose for an inter-bank financial application?

       Choice: R3 Corda (Consortium Mode)

        Justification:

           Designed for financial institutions with legal-prose smart contracts.

           Notary-based consensus ensures trust among known banks.

           Supports regulatory compliance and settlement finality.

           Optional tokenization (CBDCs, custom assets) for cross-border payments.

 (3) Justify your choice based on technical points.
      
      Each blockchain serves distinct needs: 
        Ethereum for open dApps, 
        Hyperledger Fabric for private supply chains, 
        and R3 Corda for regulated financial networks. 
      The choice depends on decentralization  
             needs, 
             speed, 
             and governance requirements.
