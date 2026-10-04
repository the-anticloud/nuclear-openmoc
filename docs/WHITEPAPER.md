# Technical Whitepaper — OPENMOC

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/mit-crpg/openmoc
**Category:** NUCLEAR

## Abstract

This whitepaper describes the Anticloud integration of `OPENMOC` (Method of characteristics neutron transport)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local reactor anomaly detection — fully air-gapped
2. AIOSS tamper-evident operational log (NRC audit-ready)
3. AES-256 encryption for all safety system data
4. Single-binary safety monitor deployable on NRC-certified hardware
5. Zero-cloud: all inference and logging runs on isolated network
6. GPU/CPU equalizer: real-time inference on industrial GPU or redundant CPU cluster
7. Formal verification annotations on all safety-critical code paths
8. Offline dosimetry and simulation replacing cloud physics engines

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.