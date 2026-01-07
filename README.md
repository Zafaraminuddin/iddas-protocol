# iddas-protocol
The IDDAS Protocol: a deterministic, lineage-based protocol for identity-free activation, attribution, and verifiable outcomes.
# IDDAS Protocol

IDDAS is a deterministic protocol for identity-free activation, lineage-based attribution, and verifiable outcomes.

This repository contains the **canonical public specification** of the IDDAS Protocol, including its economic rules, attribution logic, and governance constraints.

The protocol is designed to ensure that:
- Action precedes identity
- Attribution follows lineage, not accounts
- Economic rules are fixed, published, and non-silent
- Outcomes are independently verifiable

---

## What This Repository Is

This repository is the **authoritative reference** for the IDDAS Protocol.

It defines:
- The protocol’s purpose and scope
- Core concepts and terminology
- The economic rule governing distribution
- Constraints on modification and versioning
- The separation between on-chain anchors and off-chain execution

This repository is intended to be:
- Public
- Readable
- Stable
- Auditable over time

---

## What This Repository Is Not

This repository is **not**:
- An application
- An admin interface
- A dashboard
- A deployment target
- A product marketing site

Implementations, services, and applications may reference or implement this protocol, but they are **not part of it**.

---

## Protocol Stability and Changes

The IDDAS Protocol is designed to prevent silent or retroactive changes.

If the protocol evolves:
- Changes must be explicit
- Changes must be versioned
- Changes apply only going forward
- Prior actions remain evaluated under the rules in effect at the time they occurred

Historical versions remain accessible.

---

## On-Chain vs Off-Chain

The protocol intentionally separates concerns:

**On-chain (anchored):**
- Rule hashes
- Version identifiers
- Verification anchors
- Distribution references

**Off-chain (executed):**
- Activation flows
- Lineage calculations
- Identity handling (if any)
- Payment execution

This separation is deliberate and foundational to the protocol’s trust model.

---

## Governance

The protocol’s rules are published and fixed by design.

No per-client economics.  
No silent overrides.  
No retroactive adjustments.

Any change to the protocol must result in a new, published version.

---

## Status

This repository represents the **current public version** of the IDDAS Protocol.

Implementations may exist independently and are not authoritative unless they explicitly reference a published protocol version from this repository.

---

## License

License terms will be specified explicitly.  
Until then, no implicit rights are granted.
