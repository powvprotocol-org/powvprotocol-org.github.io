# PoWV Protocol (Proof of Weighted Value)

Official public interface and documentation repository for the PoWV Protocol research and laboratory environment.

PoWV studies how measurements and other physical events can be represented as traceable digital evidence through structured acquisition, canonical encoding, cryptographic integrity controls, edge validation, replay protection, and auditable aggregation.

The current implementation is an experimental proof of concept. It does not claim production qualification, hardware-backed attestation, public-blockchain settlement, institutional tokenization, or proof that a physical measurement was inherently true.

## Key Architecture Focus

- **Physical-to-Digital Evidence:** Capture and normalize measurements with explicit provenance, timestamp, device, and operational context.
- **Edge Verification:** Evaluate event structure, registered device identity, cryptographic integrity, and replay state at the system boundary.
- **Auditability:** Preserve verifiable event identifiers and aggregate local audit state without equating a hash or Merkle root with public-chain settlement.

## Current Validation Scope

Laboratory work currently covers physical scale acquisition, host-side event normalization, SHA-256 event identification, HTTP delivery to an ESP32 receiver, ECDSA P-256 verification in a separate binary gateway flow, replay controls, and local audit aggregation. The physical scale path and the signed gateway path are not yet a single production-qualified end-to-end system.

---

For technical documentation and the protocol overview, visit [powvprotocol.com](https://powvprotocol.com).
