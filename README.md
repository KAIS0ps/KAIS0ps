<p align="center">
  <img src="./assets/banner.svg" alt="KAIS0ps - Application and Web3 Security Research" width="100%" />
</p>

## Security Research & Defensive Engineering

Independent security researcher focused on **static source-to-sink code auditing**, **cryptographic signing verification**, **payment gateway integrity**, and **surgical remediation patches** across Rust, Go, TypeScript, Python, and PHP ecosystems.

---

### Core Focus Areas

| Domain | Research Scope | Engineering Deliverables |
|---|---|---|
| **Web3 & Wallet Core Security** | EIP-712 typed-data deserialization, ABI integer bounds, EIP-7702 delegation controls, key-derivation hardness, desktop WebView isolation | Deterministic unit harnesses & bit-exact Rust/TS patches |
| **Payment & Settlement Integrity** | Webhook HMAC verification, timestamp replay windows, minor-unit amount/currency binding, idempotent order state machines, SQL/ORM parameterization | Zero-regression `.diff` remediations & invariant libraries |
| **AI Agent & MCP Authorization** | Capability tier enforcement, fail-closed tool routing, LangGraph state isolation, secret redaction across storage and telemetry sinks | Strict capability guards & state sanitization filters |

---

### Featured Open-Source Projects

- **[payguard-rs](https://github.com/KAIS0ps/payguard-rs)** — Zero-dependency modular Rust library and CLI for constant-time `HMAC-SHA256` webhook verification, replay-window enforcement, payment settlement invariant checks, and strict base-10 256-bit `uintN` parsing.
- **[security-advisories](https://github.com/KAIS0ps/security-advisories)** — Archive of coordinated vulnerability disclosures (`CVD`), root-cause analyses, `CVSS v3.1` assessments, and remediation patches published strictly after upstream vendor fixes.

---

### Coordinated Vulnerability Disclosure (CVD) Commitment

All vulnerability research is conducted exclusively against **isolated local source environments** with zero live disruption to production services or third-party merchants. Findings are reported privately through official vendor channels (`HackerOne`, `GitHub Security Advisories`, and accredited `MITRE CNAs`) accompanied by reproducible offline test cases and conflict-free patches. No technical details are published prior to official remediation and coordinated disclosure clearance.
