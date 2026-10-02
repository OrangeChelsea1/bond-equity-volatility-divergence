# Data

Raw market data are not committed to this repository.

The notebook downloads:
- SPY adjusted close
- CBOE VIX close (`^VIX`)
- ICE BofA MOVE Index close (`^MOVE`)

through `yfinance`, then retains dates common to all three series. Missing observations are not forward-filled.

The research dataset ends on 2026-09-25 in the version used for the published POC01 results.
