<p align="center">
  <img src="./assets/banner.svg" alt="KAIS0ps - Software Architecture, Web Engineering &amp; Open-Source Security Research" width="100%" />
</p>

## Software Architecture, Web Engineering & Security Research

Senior Software Architect, Full-Stack Developer, and Independent Security Researcher with **20+ years of experience** designing, building, and securing web platforms, distributed backends, and high-performance software systems across **TypeScript / Node.js, PHP, Rust, Python, and Go**.

Combines production software engineering (multi-tenant SaaS monorepos, scalable web infrastructure, WAF/bot-defense testing tools, and modular Rust services) with manual **static source-to-sink code auditing** and **Zero-Day vulnerability research** across open-source projects.

---

### Core Engineering & Security Focus

| Domain | Scope & Specialization | Deliverables |
|---|---|---|
| **Full-Stack Web & Systems Architecture** | Multi-tenant SaaS monorepos (`Next.js`, `NestJS`), relational & cache layers (`PostgreSQL`, `MariaDB`, `Redis`, `Docker`), WAF & behavioral bot-defense testing, modular Rust backends | Production web platforms, modular libraries & defense-in-depth architectures |
| **Open-Source CMS, E-Commerce & Plugins** | Manual source-to-sink taint auditing across `WordPress`, `WooCommerce`, `OpenCart`, and third-party plugins/themes (SQLi, auth & access-control bypass, privilege escalation, SSRF, unsafe deserialization) | Reproducible local PoCs, `CVSS v3.1` root-cause advisories & surgical `.diff` patches |
| **Modern Web Backends, APIs & Desktop** | Authentication & RBAC state machines, `REST` / `GraphQL` / `WebSocket` input boundaries, ORM query parameterization, Electron / WebView `IPC` and preload isolation | Self-contained regression tests & non-breaking upstream fixes |
| **Protocols, Web3 SDKs & AI / MCP Tooling** | Cryptographic primitives (`HMAC-SHA256`, `EIP-712` typed-data signing), cross-chain & wallet SDKs, integer bounds safety, fail-closed AI agent & `MCP` capability enforcement | Deterministic Rust/TS test harnesses, strict sanitizers & invariant guards |

---

### Featured Open-Source Repositories

- **[security-advisories](https://github.com/KAIS0ps/security-advisories):** Archive of coordinated Zero-Day vulnerability disclosures (`CVD`), root-cause analyses, `CVSS v3.1` assessments, and remediation patches across open-source web platforms, CMS plugins, and modern libraries, published strictly after upstream vendor fixes.
- **[payguard-rs](https://github.com/KAIS0ps/payguard-rs):** Zero-dependency modular Rust library and CLI for constant-time `HMAC-SHA256` webhook verification, replay-window enforcement, and strict base-10 256-bit `uintN` parsing.

---

### Coordinated Vulnerability Disclosure (CVD) Commitment

All vulnerability research is conducted exclusively in **isolated local source environments** with zero live disruption to production services or third-party systems. Findings are reported privately through official vendor and bounty channels (`HackenProof`, `HackerOne`, `GitHub Security Advisories`, and accredited `MITRE CNAs` including `Patchstack` and `Wordfence`) accompanied by reproducible offline test cases and conflict-free `.diff` patches. No technical details are published prior to official remediation and coordinated disclosure clearance.
