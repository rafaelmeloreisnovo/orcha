# AGENTS — Orcha fork / RAFAELIA Ω
Status: DOCUMENTED_ONLY. Branches: `main` (working) and `main-oficial-upstream` (upstream-aligned baseline + local navigation).
Start at [001_PONTEIRO/START_HERE.md](001_PONTEIRO/START_HERE.md); machine-readable anchor: [001_PONTEIRO/upstream.json](001_PONTEIRO/upstream.json).

## Source and authority
- Official upstream: https://github.com/inveniosoftware/orcha
- Source baseline (immutable commit): https://github.com/inveniosoftware/orcha/commit/04a625fcc8660ae5b77f74ae8070e0c7e2b83310
- Official README: https://github.com/inveniosoftware/orcha/blob/04a625fcc8660ae5b77f74ae8070e0c7e2b83310/README.md (Git blob SHA `b8cfabb52c8178c8c11f70b349193a5dd43cf6c0`).
- Official LICENSE: https://github.com/inveniosoftware/orcha/blob/04a625fcc8660ae5b77f74ae8070e0c7e2b83310/LICENSE (Git blob SHA `fe847f0ebaf7dc4fe61794ca217da0326351897d`).
- The original upstream LICENSE states MIT License, Copyright (c) 2026 CERN. Keep the full original notice and MIT terms with the official source; never replace or silently relicense.
- Original README, LICENSE, upstream code, tests, CI, attribution and commit history are not overridden by this AGENTS file.
- Local authorial, currently non-executable nucleus: [NUCLEO_AUTORAL/README.md](NUCLEO_AUTORAL/README.md) and [NUCLEO_AUTORAL/LICENSE](NUCLEO_AUTORAL/LICENSE). Its notice applies only to original materials placed in that isolated directory, not upstream files.

## Execution boundaries
SOURCE != ARTIFACT != EXECUTION != EVIDENCE != CLAIM. No code or scientific result may be marked PASS from a source file alone.
`freestanding` is a planned engineering objective, NOT implemented or tested. Preserve existing behavior; no automatic network ingestion, no PR merges, force-push, credential copying or license changes.
Update protocol: pin official upstream SHA -> compare Git ancestry -> add isolated changes -> run applicable CI/runtime checks -> record receipts -> fast-forward only if safe -> keep rollback SHA. If missing proof, write TOKEN_VAZIO.
Third-party files and user-uploaded documents require separate copyright, privacy, consent and provenance checks.
