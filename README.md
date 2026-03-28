# Gotham Protocol

**The First Natively Encrypted Financial Layer for Autonomous Artificial Intelligence**

[![Status: Ideation Phase](https://img.shields.io/badge/Status-Ideation%20Phase-yellow)](#)
[![Network: Sepolia](https://img.shields.io/badge/Network-Sepolia-blue)](#)
> **Note:** Gotham Protocol is currently in the early ideation phase. The concepts and architectural structures described below represent our target vision.

## The State of Agent Commerce

We are rapidly entering an era where AI agents conduct millions of micro-transactions a day—paying for API access, distributed compute, and specialized datasets. Yet, because these transactions happen on standard blockchains, an agent's entire operational playbook is violently transparent.

Competitors and predatory algorithms can simply scan an agent's on-chain wallet to reverse-engineer its strategies, observe its suppliers, and dynamically discriminate prices against it. For the agent economy to thrive, it requires absolute financial confidentiality.

## The Gotham Solution

**Gotham Protocol** solves this existential crisis by bringing robust privacy to machine-to-machine payments. 

Built exclusively on **[Fhenix](https://fhenix.io)**—the premier Ethereum L2 powered by Fully Homomorphic Encryption (FHE)—Gotham introduces a token-centric cloaking field. Agents can conduct high-frequency, complex multi-step workflows without ever exposing their token balances or transaction values. 

While the fundamental requirement of web-based payment confirmation (the x402 standard) is strictly adhered to, the underlying economic footprint completely disappears into the mathematical shadows of FHE.

---

## What Makes Gotham Unique?

We rejected the notion of vulnerable, centralized privacy pools or restrictive off-chain ZK circuits. Instead, Gotham embraces self-sovereignty:

* **Pure Self-Custody:** Agents bridge their stablecoins to the Fhenix network and wrap them into Gotham's confidential standard (cUSDC) utilizing our ERC-7984 compliant contracts. Funds remain strictly inside the agent's EVM wallet.
* **Invisible Transfers:** When an agent pays a service provider, the amount is encrypted. Observers see that a transaction happened between Agent A and Provider B, but the value transferred is mathematically obscured.
* **Zero Protocol Friction:** Moving funds between entities within the Gotham ecosystem incurs absolute zero fees, ensuring high transaction velocity is never penalized. 
* **Trustless Price Verification:** Service providers can mathematically verify that an incoming encrypted payment meets their required threshold off-chain, guaranteeing service delivery without breaking confidentiality.

---


## Sustainable Protocol Economics

Gotham sustains its development through a simple, unavoidable toll-bridge mechanic. 

While peer-to-peer transfers are rigorously free, a micro-fee (e.g., 0.1%) is applied symmetrically whenever an entity wraps standard tokens into the Gotham layer, or unwraps them back to plaintext chains. This creates a powerful incentive for liquidity to remain inside the privacy layer indefinitely, amplifying network effects with every new agent onboarded.

---

## The Master Roadmap

To realize true agentic privacy, we are executing against the following phases:

1. **Protocol Genesis (Ideation Phase):** Conceptual design of the native ERC-7984 wrappers and highly-optimized nonce verification registries for the Fhenix stack.
2. **Developer Tooling (Upcoming):** Release of the Node.js middleware toolkit and the automated 402-fetch client wrappers.
3. **Escrow & Commerce Pipelines:** Implementation of advanced multi-step encrypted escrows (ERC-8183) for complex, stateful agent collaborations.
4. **Mainnet Convergence:** Deployment to Fhenix Mainnet, exhaustive third-party security auditing, and the integration of decentralized multi-token factories.

---

## Open Source Commitment
Gotham Protocol is fiercely committed to the decentralized future. Our core execution contracts are licensed under **BUSL-1.1**, structurally engineered to convert cleanly to **GPL-2.0** forty-eight months post Mainnet genesis.
