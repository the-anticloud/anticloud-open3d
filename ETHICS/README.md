# Ethics — OPEN3D

**Project:** OPEN3D  
**Category:** VOXELIZATION  
**Upstream:** https://github.com/isl-org/Open3D  
**Pinned commit:** `b6c5e196384ad71e75b6e6f9c5da22d046221f1d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5c2d6c9ff5d9f1c945c22a77beffb3ffaa3bc754c87b0c81f8a2451e5a846807`  
**Date:** October 2026

## Position

OPEN3D is packaged for offline deployment with a verifiable audit trail. The
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
