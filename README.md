# live-feedback

Append-only event log: Virginia (paper-trading worker) → Spark (GDAR).

One JSON file per closed signal at
`events/YYYY/MM/DD/<strategy_id>_<signal_id>.json`.

Schema: see SCHEMA.md. Version: 1.

Producers: Virginia strategy worker only.
Consumers: Spark GDAR cycle.
