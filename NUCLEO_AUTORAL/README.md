# RAFAELIA Ω — Núcleo autoral / Orcha
Steward: Rafael Melo Reis | RAFCODE-Φ | 2026-10-29.
This directory isolates original downstream proposals, architecture and future freestanding modules; it is not a copy of, or replacement for, CERN's Orcha.

## Initial state
- Core source files: NONE. No freestanding runtime has been implemented.
- Status: DESIGN_ONLY; CI and device tests: TOKEN_VAZIO.
- Direction: opt-in freestanding C/ASM interfaces, stable ABI, reproducible builds, no hidden network calls, no allocator dependency where explicitly required.
- No change to existing Orcha imports, dependency tree, build/test workflows, security model, or API.
- Third-party code introduced later requires explicit compatible licensing, full original notices, exact origin and checks.
- Read LICENSE and PROVENANCE here before creating any new content.
