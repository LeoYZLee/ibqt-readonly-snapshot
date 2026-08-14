# IBQT read-only snapshot

This repository publishes a sanitized, read-only snapshot of the IBQT trading dashboard for automated analysis.

- `latest.json` is refreshed every five minutes.
- Account identifiers, process commands, client IDs, and logs are excluded.
- The snapshot contains connection health, sanitized job status, the latest strategy chart, and trade/signal events.
- The operational dashboard remains separately protected.

Raw snapshot:

https://raw.githubusercontent.com/LeoYZLee/ibqt-readonly-snapshot/main/latest.json
