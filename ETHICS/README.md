# Ethics — CLOTH_SIMULATION

**Project:** CLOTH_SIMULATION  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/Hedlundaren/cloth-simulation  
**Pinned commit:** `cadca8e1b9d7922986cd25e64cd070356dd55153`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `daa135a3076519ab72fc44caa65460f044e570911c5e1a94e141b4cd2311b1e1`  
**Date:** October 2026

## Position

CLOTH_SIMULATION is packaged for offline deployment with a verifiable audit trail. The
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
