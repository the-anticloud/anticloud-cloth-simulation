# Educators — CLOTH_SIMULATION

**Project:** CLOTH_SIMULATION  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/Hedlundaren/cloth-simulation  
**Pinned commit:** `cadca8e1b9d7922986cd25e64cd070356dd55153`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `daa135a3076519ab72fc44caa65460f044e570911c5e1a94e141b4cd2311b1e1`  
**Date:** October 2026

## Teaching with CLOTH_SIMULATION

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `daa135a3076519ab72fc44caa65460f044e570911c5e1a94e141b4cd2311b1e1` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
