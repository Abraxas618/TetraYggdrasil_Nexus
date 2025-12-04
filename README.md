TetraYggdrasil Nexus

Prototype Experimental Post-Quantum Mesh Communication Framework
Repository: https://github.com/Abraxas618/TetraYggdrasil_Nexus
License: MIT
Author: Michael Tass MacDonald


---

1. Overview

TetraYggdrasil Nexus is an experimental research prototype exploring post-quantum communication methods, zero-knowledge authentication, and IPv6 mesh networking using the Yggdrasil overlay.

The objective of this prototype is to evaluate:

Post-quantum key exchange and authentication (Kyber, Dilithium, ML-KEM)

WASM-accelerated networking logic

zk-STARK-based message-authentication schemes

Lightweight, peer-to-peer mesh routing over Yggdrasil


This system is not functional, not secure, and not production-ready.
It is published strictly as an open research artefact.


---

2. Key Research Components

Post-Quantum Primitives
Experimental integration of Kyber-1024, Dilithium-V, and related KEM/signature schemes for studying authentication and secure channel bootstrapping.

Yggdrasil IPv6 Mesh Routing
Utilizes the Yggdrasil overlay to explore decentralized addressing, peer discovery, and encrypted IPv6-native tunnels.

Zero-Knowledge Authentication (zk-STARK)
Prototype logic for message-authentication experiments using STARK-based verification.

Recursive Hashing Models
Early-stage integration of Recursive Tesseract Hashing (RTH) for experimental state-transition commitments.

WASM-Optimized Communication Layer
Rust/WASM components to test low-latency message passing and serialization.


All features are purely research trial components.


---

3. System Architecture (Prototype)

Languages / Technologies:

TypeScript

Rust → WebAssembly (WASM)

Node.js / Vite

Yggdrasil mesh networking

AES + Post-Quantum KEM/SIG (conceptual wrappers)

STARK verification libraries


Structure:

src/
public/
components/
backend/
rust-wasm/

Conceptual Modules:

Key Management Panel (PQC key generation)

Mesh Sync Panel (Yggdrasil peer handshake tests)

Diagnostic Dashboard (network visualization + logs)

ZK Authentication Test Suite



---

4. Experimental Metrics (Simulated)

These numbers are placeholders used to explore expected latency tiers across hypothetical communication environments.
They are not empirical and must not be interpreted as validated performance.

Environment	Latency (Simulated)	Notes

Terrestrial Fiber	~10–20 ms	Standard mesh routing
Earth–Lunar	~1–2 sec	Light-speed constraint
Interplanetary	30–90 sec	Long-delay networking


These values serve as test inputs for latency-robust design studies.


---

5. Quick Start

npm install
npm run dev

1. Open http://localhost:5173


2. Generate a PQC key (simulation mode)


3. Connect to a local Yggdrasil test node


4. View routing and message logs in the dashboard



The application operates entirely in simulation mode.


---

6. Licensing

This repository is released under the MIT License, consistent with Baramay Station’s open research mandate.

All content is:

experimental

non-operational

provided for academic, educational, and exploratory purposes



---

7. Provenance & Archival Integrity

Zenodo DOI

A DOI-backed archival revision is available at:

10.5281/zenodo.15207676

Bitcoin Timestamp (OpenTimestamps)

A cryptographic timestamp (.ots) file is included to document authorship and ensure long-term reproducibility of the repository’s state.

Verify using:

pip install opentimestamps-client
ots verify Codex_Blockchain_Archive.zip.ots

IPFS Mirrors

IPFS copies ensure decentralized preservation of relevant archives:

File	IPFS Link

Codex Combined Archive	https://ipfs.io/ipfs/bafybeifchitc5jr5gqni5awxeptw6ub3p4cdavgtwtzysqsi3uwaald5na
Codex Bitcoin Timestamp (.ots)	https://ipfs.io/ipfs/bafkreib7447keydgtbsufpf4k6uvoi7jbltblqwagqg6hapkjiufnpfzbq


These mirrors are for archival reproducibility only.


---

8. Related Research Projects (All Experimental)

TetraCodex (Apache 2.0) — Foundational R&D framework

TetraCrypt-PQC-Nexus (Apache 2.0) — PQC + geometric cryptography experiments

TetraCrypt_Yggdrasil_Unified (MIT) — Combined PQC + mesh prototype

TetraNexus (Apache 2.0) — High-level integration research

TetraVote (MIT) — Zero-knowledge voting research prototype


None are production systems.


---

9. Project Purpose

TetraYggdrasil Nexus serves as:

a technical exploration,

a mathematical testbed,

an open-source educational reference, and

a semi-reproducible prototype for studying experimental PQC + mesh concepts.


It does not guarantee security, privacy, or operational capability.