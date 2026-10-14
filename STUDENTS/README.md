# Students — DARKTABLE

**Project:** DARKTABLE  
**Category:** CAMERAS  
**Upstream:** https://github.com/darktable-org/darktable  
**Pinned commit:** `c6d8389bf6afdfd26df437eeedb0323f054180c7`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ba04512bc07c0b40f74beef18364ab87d053cc9e1227e328dd647e093e4abb07`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `c6d8389bf6afdfd26df437eeedb0323f054180c7`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `ba04512bc07c0b40f74beef18364ab87d053cc9e1227e328dd647e093e4abb07`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
