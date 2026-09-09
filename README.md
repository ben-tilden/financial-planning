# Household Finance Worksheet

A self-contained HTML household finance planner. Open `finance-worksheet-final.html` in any browser — no build step or server required.

## Features

- Income, paycheck deductions, expenses, and asset tracking
- Multi-year projections with charts
- Estimated federal, NY State, and NYC taxes
- Life events (one-time or ongoing income/expense changes)
- Asset liquidity modes (brokerage, Roth basis, restricted accounts)
- Light/dark theme
- Export and import worksheet state as JSON

## Quick start

1. Open `finance-worksheet-final.html` in your browser.
2. Enter your numbers, or click **Import** and load `examples/household-starter.json` to explore with sample data.
3. Use **Export** to save your scenario locally.

## Personal data

Your own exports should stay on your machine (or in a separate private repo). Files matching `household-worksheet*.json` at the repo root are gitignored by default. Only the anonymized `examples/household-starter.json` is tracked for contributors.

## Contributing

Changes to the worksheet logic belong in `finance-worksheet-final.html`. If you add or rename fields in the export format, update `examples/household-starter.json` so importers stay compatible.

Numbers are planning estimates, not financial or tax advice.
