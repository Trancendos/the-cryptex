# The Cryptex v1.0

> CVE scanning, vulnerability management, STIX/TAXII feeds, and IOC tracking for the Trancendos Ecosystem.

## Features
- CVE feed aggregation (NVD, MITRE, GitHub Advisory)
- STIX/TAXII threat intelligence feeds
- IOC (Indicators of Compromise) management
- CVE auto-management with snapshots and rollback
- Vulnerability scanning and reporting
- Dashboard with severity visualization

## Architecture
```
src/
├── index.ts              # TypeScript class definition
feeds/
├── cve-feed-aggregator.js  # CVE feed aggregation
scripts/
├── cve-auto-manager.js     # Automated CVE management
├── cve-rollback.js         # CVE rollback capability
└── cve-snapshot.js         # CVE state snapshots
```

## Part of the Trancendos Ecosystem
- Port: 3012
- Event Bus: Observatory (port 3010)
