# DIKWP BusPulse OS

DIKWP BusPulse OS is a GitHub-ready pilot system for a Guangdong/Guangzhou bus group DIKWP trial. It converts noisy bus operations data into DIKWP semantic ledgers, semantic-closure judgments, human-confirmed action tickets, and audit records.

## Quick Start

```bash
pip install -e .
buspulse analyze examples/sample_bus_pilot_case.json --out outputs/demo
buspulse static-audit src --out outputs/demo/static_boundary_audit_report.json
```

## Boundary

This is decision support and audit infrastructure only. It does not control real vehicles, traffic signals, chargers, payment, personnel decisions, or safety-critical actions.
