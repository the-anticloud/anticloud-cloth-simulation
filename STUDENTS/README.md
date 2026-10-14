# Students — CLOTH_SIMULATION

**Project:** CLOTH_SIMULATION  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/Hedlundaren/cloth-simulation  
**Pinned commit:** `cadca8e1b9d7922986cd25e64cd070356dd55153`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `daa135a3076519ab72fc44caa65460f044e570911c5e1a94e141b4cd2311b1e1`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `cadca8e1b9d7922986cd25e64cd070356dd55153`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `daa135a3076519ab72fc44caa65460f044e570911c5e1a94e141b4cd2311b1e1`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
