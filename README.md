# Wind Watcher

## URL parameters for filters

You can link directly to a filtered view by adding query parameters to the URL.
When you change filters in the UI, the URL is updated so it can be shared.

Supported parameters:

- `state`: `ACT`, `NSW`, `NT`, `QLD`, `SA`, `TAS`, `VIC`, `WA`, or `ALL`
- `region`: `RW`, `AL`, `PF`, `SG`, `TC`, `JD`, `SL`, `JL`, `WS`, `RH`, or `ALL`
- `wind`: `all`, `warning` (High), or `danger` (Very high)
- `search`: free-text search (URL-encoded)
- `alerts`: `1`, `true`, `yes`, `on` to enable alerts-only; `0`, `false`, `no`, `off` to disable

Examples (replace the base URL with your deployed site):

- `https://your-site/?state=WA&wind=danger`
- `https://your-site/?state=QLD&region=SG&search=airlie&alerts=1`
- `https://your-site/?wind=warning&search=bay`
