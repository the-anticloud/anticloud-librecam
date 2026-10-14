# Educators — LIBRECAM

**Project:** LIBRECAM  
**Category:** FACTORY_MANUFACTURING  
**Upstream:** see BENCH.json  
**Pinned commit:** `46961097d837550bf68ec14eacb9e1f1a4297bd5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `283ce8c6bc17312d4b913574b4b70e37877dc5a9074baed02ff4b4ca9ad1ddbe`  
**Date:** October 2026

## Teaching with LIBRECAM

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `283ce8c6bc17312d4b913574b4b70e37877dc5a9074baed02ff4b4ca9ad1ddbe` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
