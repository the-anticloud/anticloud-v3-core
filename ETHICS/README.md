# Ethics — V3_CORE

**Project:** V3_CORE  
**Category:** CRYPTOCURRENCY  
**Upstream:** see BENCH.json  
**Pinned commit:** `d0831dc6b8a318df3872b6d68f6de135c9f3ec29`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f58fbb70d5b2cfebbc9c5c183de146748dc41a45ad15993f4549ef1ac7b4d8e9`  
**Date:** October 2026

## Position

V3_CORE is packaged for offline deployment with a verifiable audit trail. The
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
