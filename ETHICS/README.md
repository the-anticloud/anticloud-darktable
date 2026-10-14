# Ethics — DARKTABLE

**Project:** DARKTABLE  
**Category:** CAMERAS  
**Upstream:** https://github.com/darktable-org/darktable  
**Pinned commit:** `c6d8389bf6afdfd26df437eeedb0323f054180c7`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ba04512bc07c0b40f74beef18364ab87d053cc9e1227e328dd647e093e4abb07`  
**Date:** October 2026

## Position

DARKTABLE is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
