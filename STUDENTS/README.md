# Students — V3_CORE

**Project:** V3_CORE  
**Category:** CRYPTOCURRENCY  
**Upstream:** see BENCH.json  
**Pinned commit:** `d0831dc6b8a318df3872b6d68f6de135c9f3ec29`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f58fbb70d5b2cfebbc9c5c183de146748dc41a45ad15993f4549ef1ac7b4d8e9`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `d0831dc6b8a318df3872b6d68f6de135c9f3ec29`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `f58fbb70d5b2cfebbc9c5c183de146748dc41a45ad15993f4549ef1ac7b4d8e9`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
