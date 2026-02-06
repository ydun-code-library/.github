# Ydun.io

**Applied R&D and Systems Practice — decentralised, local-first, privacy-first tools.**

We build infrastructure for a world where your data stays yours. No key escrow. No "trust us" security models. No cloud dependency. Just working cryptography and clean engineering.

Founded by [James Barclay](https://www.ydun.io) in Sweden.

---

## What We Work On

| Domain | What That Means |
|--------|-----------------|
| **Decentralised Architecture** | Systems without single points of control or failure |
| **Local-First Design** | Data lives where it's used; cloud is optional, not required |
| **Privacy Engineering** | Privacy built into the structure, not bolted on after |
| **Zero-Knowledge Proofs** | Making ZK cryptography practically usable |
| **AI Workflows** | Research, deployment, and audit tooling for AI-assisted development |

---

## Public Repos

### [0k-Sync](https://github.com/ydun-code-library/0k-sync)

Zero-knowledge sync protocol for local-first apps. The relay never sees your data — not encrypted-at-rest-but-we-have-the-keys, actually zero knowledge. Pure Rust, no runtime, designed for edge hardware and battery-constrained devices.

- **XChaCha20-Poly1305** encryption, **Argon2id** key derivation
- **QUIC transport** via iroh — relay-first with P2P as bonus
- **309 tests passing**, 2 security audits complete
- Post-quantum hybrid design (ML-KEM-768) in progress

### [curve25519-dalek](https://github.com/ydun-code-library/curve25519-dalek)

Fork of [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) — pure-Rust arithmetic over Curve25519 and Ristretto.

---

## Tech Stack

| Layer | Tools |
|-------|-------|
| **Language** | Rust |
| **Desktop** | Tauri v2 |
| **Crypto** | XChaCha20-Poly1305, Argon2id, BLAKE3, Noise Protocol |
| **Networking** | iroh (QUIC), relay-first architecture |
| **Blockchain** | Cardano, Aiken |

---

## Contact

- **Web:** [ydun.io](https://www.ydun.io)
- **Email:** hello@ydun.io
- **Location:** Sweden

---

<p align="center"><em>Privacy is a structural property, not a feature toggle.</em></p>
