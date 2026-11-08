## Software Architecture, Full-Stack Systems & Security Research

Designing and operating full-stack web platforms, financial settlement pipelines, and modular Rust services alongside manual source-to-sink code auditing and smart contract security research.

---

### Architecture & Production Systems

- **Digital Commerce & Multi-Chain Settlement Platforms (Next.js, NestJS, Turborepo, PostgreSQL, BullMQ):** Multi-gateway fiat and cryptocurrency checkout systems built around double-entry ledger accounting, AES-256-GCM encrypted fulfillment vaults, keyed HMAC blind indexing for searchable encrypted PII, and idempotent webhook workers.
- **Merchant Verification & High-Integrity Review Systems (TypeScript, Prisma, PostgreSQL):** Domain-ownership state machines with hashed OTP attempt bounds, instant `tokenVersion` session revocation, atomic claim locking against race conditions, and automated anti-abuse validation pipelines.
- **Low-Latency Execution & Risk Engines (Rust, Python, PyO3):** Deterministic exposure and drawdown circuit breakers, Ed25519-authenticated market streams, and lock-free shared-memory bridges.

---

### Security Research & Audit Scope

- **Smart Contracts & DeFi Protocols (Solidity / EVM, Rust / NEAR):** Auditing ERC-4626 and ERC-7540 vaults, lending and liquidation engines, cross-chain intent bridges, oracle feeds, and multi-decimal token accounting. Every finding is verified via local Foundry (`forge test`) or `cargo test` reproductions against unmodified upstream commits across realistic market bounds and active keeper liveness.
- **Web Backends, APIs & Open-Source Platforms (TypeScript, PHP, Go, Python):** Manual source-to-sink taint auditing across Node.js APIs, WordPress, WooCommerce, and OpenCart codebases covering SQL injection, broken access control, privilege escalation, SSRF, and unsafe deserialization, paired with isolated regression tests and minimal `.diff` fixes.

---

### Open-Source Repositories

- **[vaultguard-rs](https://github.com/KAIS0ps/vaultguard-rs):** Zero-dependency `#![forbid(unsafe_code)]` Rust library and CLI for ERC-4626 / ERC-7540 share-math verification, 256-bit `mul_div` rounding checks, multi-decimal truncation detection, async redemption conservation, and oracle staleness bounds.
- **[payguard-rs](https://github.com/KAIS0ps/payguard-rs):** Zero-dependency `#![forbid(unsafe_code)]` Rust library and CLI for constant-time HMAC-SHA256 webhook authentication, replay-window enforcement, settlement invariants, and strict base-10 `uintN` parsing.
- **[security-advisories](https://github.com/KAIS0ps/security-advisories):** Coordinated vulnerability disclosures, technical notes on DeFi triage falsification, CWE / CVSS v3.1 root-cause analyses, and upstream fixes published post-remediation.

---

### Coordinated Disclosure

All vulnerability research runs strictly in isolated local environments with zero automated scanning or test traffic sent to live third-party systems. Findings are reported privately through official vendor and bounty channels (Immunefi, HackenProof, HackerOne, GitHub Security Advisories, and accredited MITRE CNAs including Patchstack and Wordfence) with reproducible local tests and proposed fixes, and are published only after upstream patches ship and disclosure is cleared.
