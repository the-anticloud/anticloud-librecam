# Students — LIBRECAM

**Project:** LIBRECAM  
**Category:** FACTORY_MANUFACTURING  
**Upstream:** see BENCH.json  
**Pinned commit:** `46961097d837550bf68ec14eacb9e1f1a4297bd5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `283ce8c6bc17312d4b913574b4b70e37877dc5a9074baed02ff4b4ca9ad1ddbe`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `46961097d837550bf68ec14eacb9e1f1a4297bd5`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `283ce8c6bc17312d4b913574b4b70e37877dc5a9074baed02ff4b4ca9ad1ddbe`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
