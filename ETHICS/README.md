# Ethics — LIBRECAM

**Project:** LIBRECAM  
**Category:** FACTORY_MANUFACTURING  
**Upstream:** see BENCH.json  
**Pinned commit:** `46961097d837550bf68ec14eacb9e1f1a4297bd5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `283ce8c6bc17312d4b913574b4b70e37877dc5a9074baed02ff4b4ca9ad1ddbe`  
**Date:** October 2026

## Position

LIBRECAM is packaged for offline deployment with a verifiable audit trail. The
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
