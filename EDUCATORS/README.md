# Educators — V3_CORE

**Project:** V3_CORE  
**Category:** CRYPTOCURRENCY  
**Upstream:** see BENCH.json  
**Pinned commit:** `d0831dc6b8a318df3872b6d68f6de135c9f3ec29`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f58fbb70d5b2cfebbc9c5c183de146748dc41a45ad15993f4549ef1ac7b4d8e9`  
**Date:** October 2026

## Teaching with V3_CORE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `f58fbb70d5b2cfebbc9c5c183de146748dc41a45ad15993f4549ef1ac7b4d8e9` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
