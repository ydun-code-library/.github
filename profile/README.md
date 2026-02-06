# Ydun.io

**Applied R&D and Systems Practice — decentralised, local-first, privacy-first tools.**

We build infrastructure for a world where your data stays yours. No key escrow. No "trust us" security models. No cloud dependency. Just working cryptography and clean engineering.

We build for where the world is going — not where it's been.

This is the code and research library behind [ydun.io](https://www.ydun.io). Founded by James Barclay in Sweden.

---

## What We Work On

| Domain | What That Means |
|--------|-----------------|
| **Decentralised Architecture** | No single entity controls the system. No single point of failure. Users run their own infrastructure, or use ours — the cryptography doesn't care |
| **Local-First Design** | Data and privacy are first-class citizens. Your data lives on your device. Cloud is optional. You own it — you're not the product |
| **Privacy Engineering** | Privacy built into the structure, not bolted on after. If the architecture requires trust, the architecture is wrong |
| **Zero-Knowledge** | Zero knowledge as a principle, not just a proof system. ZK proofs, ZK sync, ZK infrastructure — the system never learns what it doesn't need to know |
| **AI & Cybersecurity** | Frontier models with custom RAG systems. Bridging knowledge gaps in auditing, offensive and defensive cybersecurity, and AI-assisted development |

---

## Public Repos

### [0k-Sync](https://github.com/ydun-code-library/0k-sync)

Zero-knowledge sync protocol for local-first apps. The relay never sees your data — not encrypted-at-rest-but-we-have-the-keys, actually zero knowledge. Pure Rust, no runtime, designed for edge hardware and battery-constrained devices.

- **XChaCha20-Poly1305** encryption, **Argon2id** key derivation
- **QUIC transport** via iroh — relay-first with P2P as bonus
- **309 tests passing**, 2 security audits complete
- Post-quantum hybrid design (ML-KEM-768) in progress

---

## Tech Stack

| Layer | Tools |
|-------|-------|
| **Languages** | Rust, TypeScript, JavaScript, Python, SolidJS |
| **Desktop** | Tauri v2 |
| **Crypto** | XChaCha20-Poly1305, Argon2id, BLAKE3, Noise Protocol |
| **Networking** | iroh (QUIC), relay-first architecture |
| **Blockchain** | Cardano, Midnight, Bitcoin, Ergo — UTXO and EUTXO models |
| **Smart Contracts** | Aiken, Plutus |

---

## Code & Research

This library holds both working implementations and the research behind them. Protocol specifications, security audits, cryptographic design documents, and architecture decisions — not just the finished code, but the thinking that produced it.

---

## Contact

- **Web:** [ydun.io](https://www.ydun.io)
- **Email:** hello@ydun.io
- **Location:** Sweden

---

<p align="center"><em>Privacy is a structural property, not a feature toggle.</em></p>
