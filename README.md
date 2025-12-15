# NuChain-Core
 The foundational Layer 1 blockchain protocol leveraging Proof of Thought (PoT) and verifiable AI (zkML).
# NuChain-Core

![NuChain Logo Placeholder]
> **The world's first intelligent Layer 1, leveraging Proof of Thought (PoT) and verifiable AI (zkML) for boundless, sustainable scalability.**

---

## 🧠 1. Key Differentiators

NuChain is engineered to transcend the traditional Blockchain Trilemma by integrating verifiable machine learning into its consensus mechanism.

* **Proof of Thought (PoT):** Nodes secure the network by performing useful, verifiable AI/ML tasks instead of wasted computation.
* **zkML Integration:** We use zk-STARKs to instantly verify complex AI computation, achieving high throughput ($TPS$) with uncompromising security.
* **AI Security Sentinel:** An on-chain ML model scans transactions for fraud *before* they enter the block, providing a proactive security layer.

[Link to WHITEPAPER.pdf for mathematical proofs]

## 🛠️ 3. Getting Started: Run a Thinker Node

To participate in consensus and earn $NU rewards, clone the repository and run the client.

**Prerequisites:** [Rust stable](https://www.rust-lang.org/tools/install) (latest) or Go v1.21+

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/NuChain-Protocol/nuchain-core.git](https://github.com/NuChain-Protocol/nuchain-core.git)
    cd nuchain-core
    ```
2.  **Build the Client:**
    ```bash
    # For Thinker Node with full verification capabilities
    cargo build --release --features zkml-verifier
    ```
3.  **Start Local Node (Dev Mode):**
    ```bash
    ./target/release/nuchain-client --chain dev --thinker
    ```
    
## 👨‍💻 4. Building on NuChain

Our goal is to create the best experience for dApp developers.

* **[NuChain SDK (JavaScript)](./sdk/nuchain-js-sdk/):** The easiest way to interact with the NuChain RPC endpoint.
* **Documentation Portal:** Start learning how to deploy smart contracts, query the chain state, and utilize verifiable AI oracles in our [Official Docs](https://docs.nuchain.io).
