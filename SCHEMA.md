# Event Schema v1

## `signal_closed`

```json
{
  "schema_version": 1,
  "event_type": "signal_closed",
  "signal_id": "S4-159_1712998800123",
  "strategy_id": "S4-159",
  "strategy_version": "1.0.0",
  "binner_md5": "a1b2c3...",

  "entry_ts_ms": 1712998800123,
  "exit_ts_ms":  1712998843901,
  "hold_ms":     43778,

  "side": "long",
  "entry_price": 70755.4,
  "exit_price":  70801.2,

  "mae_bps":       2.8,
  "mfe_bps":       7.1,
  "realized_bps":  6.5,
  "net_bps_after_fees": 3.5,
  "hit_3bps":   true,
  "exit_reason": "trailing_tp",

  "gate_states_at_trigger": { "G4": true, "G7": true, "G8": true, "G9": true },
  "market_context": {
    "hl_range_usd": 12.4, "cex_conv": 0.031, "slope": 0.14
  },

  "virginia_worker_version": "2026.04.13-a",
  "written_at_ms": 1712998844120
}
```

Unknown fields: readers ignore with WARN. Schema upgrades are additive.
