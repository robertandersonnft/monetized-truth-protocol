# monetized-truth-protocol
The Monetized Truth Protocol (MTP) codifies how identity-bound, verifiable actions are scored, tokenized, and rewarded in decentralized ecosystems. This repo contains the core logic, examples, documentation, and integration modules for using MTP across Web3 environments. Extended definition of RealworldNative-Radius0x Glossary author: robertanderson.nft
# 🧠 Monetized Truth Protocol (MTP)

The **Monetized Truth Protocol** enables decentralized systems to quantify, score, and reward verifiable action, authenticated identity, and provable intent.

> Truth is not just protected — it's monetized.

---

## 📐 MTS Formula


Where:
- A = Action Proof (e.g. match verified on-chain)
- I = Identity Entropy (IDoS strength)
- V = Validator Certainty
- R = Reputation Score
- F = Feedback Accuracy (agentic consensus)
- S = Staked Intent

---

## 🔧 What's in This Repo?

| Folder | Contents |
|--------|----------|
| `contracts/` | Solidity contract for TrustScoreOracle |
| `formulas/` | Python and TypeScript versions of the MTS calculator |
| `examples/` | Real-world use cases (e.g., ChessGrid0x match score) |
| `docs/` | Whitepaper, manifesto, and technical definitions |
| `website/` | Page code for radius0x.xyz/mtp |
| `tests/` | Unit tests for scoring logic |

---

## 🧩 Integrations

- **ChessGrid0x:** Score every move and reward verified play
- **DriverHR:** Score rides and deliveries based on IDoS-verified service
- **GenesisGrid:** Store action proofs and feedback snapshots immutably

---

## 🛠️ Installation (Python SDK)

```bash
git clone https://github.com/realworldnative/monetized-truth-protocol.git
cd monetized-truth-protocol
pip install -r requirements.txt
