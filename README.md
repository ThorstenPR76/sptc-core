# SPTC – Settlement Protocol for Tokenized Claims

## Overview

SPTC is an open-source, non-monetary, rules-based settlement engine for barter-style transactions using asset representations. The project is **not** a financial product, **not** a payment service, **not** an exchange, and **not** a marketplace.

SPTC is designed as an **infrastructural reference implementation** for deterministic ownership transfer, event-driven state machines, and auditability by design — without money.

---

## Motivation

Most transactional systems tightly couple money, enforcement, and business logic. This coupling introduces unnecessary complexity, regulatory surface area, and opacity.

SPTC deliberately separates these concerns by:
- Modeling ownership changes deterministically
- Using event-sourced state transitions
- Making every action auditable by default
- Eliminating monetary settlement entirely

The result is a transparent, rule-based settlement core that can be studied, extended, or embedded into other systems.

---

## What SPTC Is Not

To avoid ambiguity, SPTC is explicitly **not**:
- a FinTech product
- a crypto or blockchain project
- a payment or wallet system
- a trading venue or exchange
- a marketplace

SPTC does **not** handle money, fiat, crypto assets, custody, or payments of any kind.

---

## Minimal Scope – SPTC Core

The minimal scope defines the smallest meaningful core of the system. The objective is a functional demo with minimal complexity.

### Included Components

- Demo users
- Asset ledger (demo assets only)
- Order creation and matching
- Owner-to-owner settlement
- Trigger engine
- Event-based audit log
- Tax simulation (TDS, shadow mode)

### Explicitly Excluded

- No physical custody
- No deposits or withdrawals
- No fiat or payments
- No scaling or performance optimization

---

## Architecture Principles

- **Rules over discretion** – all state changes follow explicit rules
- **Event sourcing** – system state is derived from immutable events
- **Deterministic settlement** – identical inputs always produce identical outcomes
- **Auditability by design** – no hidden state transitions

---

## Getting Started

This repository is intended as a reference and experimentation environment.

Typical first steps:
1. Read the documentation
2. Explore the core domain model
3. Run the demo scenarios
4. Inspect the audit logs and state transitions

---

## Contributing

SPTC welcomes contributors interested in:
- rules-based system design
- event-driven architectures
- settlement logic
- audit and traceability systems

### How to Contribute

- Choose small, clearly scoped issues
- Submit pull requests with clear reasoning
- Keep changes minimal and well-documented
- Discuss architectural questions openly

### Important Note

SPTC is **not** a commercial product. All contributions are voluntary, unpaid, and must adhere to the defined guardrails and specifications.

---

## License

Open-source license (to be specified).

---

## Disclaimer

SPTC is provided for educational and experimental purposes only. It does not provide financial, legal, or tax services and must not be used as such.
