# Educators — OPEN3D

**Project:** OPEN3D  
**Category:** VOXELIZATION  
**Upstream:** https://github.com/isl-org/Open3D  
**Pinned commit:** `b6c5e196384ad71e75b6e6f9c5da22d046221f1d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5c2d6c9ff5d9f1c945c22a77beffb3ffaa3bc754c87b0c81f8a2451e5a846807`  
**Date:** October 2026

## Teaching with OPEN3D

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `5c2d6c9ff5d9f1c945c22a77beffb3ffaa3bc754c87b0c81f8a2451e5a846807` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
