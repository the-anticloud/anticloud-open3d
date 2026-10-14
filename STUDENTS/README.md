# Students — OPEN3D

**Project:** OPEN3D  
**Category:** VOXELIZATION  
**Upstream:** https://github.com/isl-org/Open3D  
**Pinned commit:** `b6c5e196384ad71e75b6e6f9c5da22d046221f1d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5c2d6c9ff5d9f1c945c22a77beffb3ffaa3bc754c87b0c81f8a2451e5a846807`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `b6c5e196384ad71e75b6e6f9c5da22d046221f1d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `5c2d6c9ff5d9f1c945c22a77beffb3ffaa3bc754c87b0c81f8a2451e5a846807`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
