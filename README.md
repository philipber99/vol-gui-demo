# Options Volatility Workbench demo

[Open the browser demo](https://philipber99.github.io/vol-gui-demo/)

Explore option chains, volatility surfaces, strategy analytics and sample
position tracking using recorded market data. The reference day is
**November 12, 2026**. Sample securities are **AAPL, AMD, MSFT and NVDA**.

The demo starts on **Market Overview**. Strategy Workbench already contains an
AAPL call vertical: long one **$345 call** and short one **$355 call**, both
expiring **November 20, 2026**. The sample includes ten shared trading sessions
of price history and recorded historical strategy-path examples.

The application runs entirely in the browser with static sample files. It has
no live data connection, brokerage connection, login or order submission.
Position edits and preferences are stored only in this browser. **Reset demo**
restores the starting state; **Load sample spread** loads the recorded example
for the selected security.

Recorded coverage is limited. Unrecorded contracts or analytics settings show
a coverage explanation. History lengths vary by security; missing observations
are not filled with invented prices. Historical strategy-path data retain their
original source dates, which can precede the reference day.

This repository contains only the compiled static demo, selected market-data
samples and this README. Backend code, connection settings, credentials, export
tools, local reports, logs and source maps are excluded. Third-party license
notices remain in the compiled assets.
