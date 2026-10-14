# Build and Test

**Project:** `LIBRECAM`
**Upstream:** https://github.com/LibreCAM/librecam
**License:** MIT

## Quick Start

```bash
git clone https://github.com/LibreCAM/librecam
cd librecam
pip install -r requirements-anticloud.txt
python anticloud_main.py --offline --pax-local
```

## Anticloud Improvements Applied

1. PAX L5 Narrow L2 General 27B local predictive maintenance on edge PLC hardware
2. AIOSS tamper-evident production log for every part and batch
3. AES-256 encryption for proprietary process parameters
4. Single-binary MES executable for locked-down factory floor PCs
5. Zero-cloud: all analytics and inference run on local industrial servers
6. GPU/CPU equalizer: vision inspection on GPU, telemetry on CPU
7. Offline OEE calculation replacing cloud analytics dashboards
8. Open OPC-UA/Modbus integration replacing proprietary SCADA middleware

## Benchmark Targets

| Metric | Target |
| --- | --- |
| Latency | Primary inference task: <5s on CPU, <1s on GPU |
| Throughput | Batch processing: >100 items/hour on single CPU server |
| Memory | <8GB RAM for standard deployment |
| Accuracy | Task-specific accuracy within 5% of cloud-API baseline |

## Build Status

Not yet measured. Run verified build and record actual figures above.
