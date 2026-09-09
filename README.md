# Household Finance Worksheet

A self-contained HTML household finance planner. Open [`index.html`](index.html) in any browser — no build step or server required.

Live demo: [ben-tilden.github.io/financial-planning](https://ben-tilden.github.io/financial-planning/)

## Features

- Flexible income earners (solo or multi-person household)
- Customizable variable pay schedules (monthly, quarterly, semi-annual, or annual)
- Paycheck deductions, expenses, and asset tracking
- Multi-year projections with charts
- Estimated federal, NY State, and NYC taxes
- Life events (one-time or ongoing income/expense changes)
- Asset liquidity modes (brokerage, Roth basis, restricted accounts)
- Light/dark theme
- Export and import worksheet state as JSON

## Quick start

1. Open `index.html` in your browser (or use the live demo link above).
2. Enter your numbers, or click **Import** and load `examples/household-starter.json` to explore with sample data.
3. Use **Export** to save your scenario locally.

## Personal data

Your own exports should stay on your machine (or in a separate private repo). Files matching `household-worksheet*.json` at the repo root are gitignored by default. Only the anonymized `examples/household-starter.json` is tracked for contributors.

## Contributing

Changes to the worksheet logic belong in `index.html`. If you add or rename fields in the export format, update `examples/household-starter.json` so importers stay compatible.

Numbers are planning estimates, not financial or tax advice.

## License

Licensed under the MIT License — see [LICENSE](LICENSE).
