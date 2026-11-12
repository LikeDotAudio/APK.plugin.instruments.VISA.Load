# SDK — INSTRUMENT.Load

Every Load model this library drives, and how to drive it. Each model answers the same five verbs over HTTP (its own port), WebSocket, a Unix socket and the bus; one page per model below lists its routes and every command.

← [Manual and Artifacts](INDEX.md)

| Verb | What it does |
|---|---|
| `get` | reads one value |
| `set` | writes one value |
| `nab` | reads more than one thing (observation, telemetry) |
| `rig` | configures several arguments at once |
| `do` | executes an action; takes no value |

| Model | Maker | get | set | nab | rig | do | Port |
|---|---|---:|---:|---:|---:|---:|---:|
| [6060B](SDK/6060B.md) | HP / Agilent / Keysight | 47 | 55 | 49 | 1 | 40 | 15700 |
| [6063B](SDK/6063B.md) | HP / Agilent / Keysight | 47 | 55 | 49 | 1 | 40 | 15701 |
| [EL30000](SDK/EL30000.md) | HP / Agilent / Keysight | 47 | 55 | 49 | 1 | 40 | 15702 |
| [N3300A](SDK/N3300A.md) | HP / Agilent / Keysight | 47 | 55 | 49 | 1 | 40 | 15703 |
