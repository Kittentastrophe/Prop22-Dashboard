# Prop 22 Driver Pay Dashboard

Biweekly Prop 22 earnings dashboard for California Uber drivers, built as a static HTML calculator for GitHub Pages.

## What it does

This dashboard helps estimate Uber driver earnings under California Prop 22 using biweekly inputs.

It calculates:
- 120% wage guarantee.
- $0.34 per engaged mile adjustment.
- Total earnings floor.
- Prop 22 adjustment payout.
- Net pay after subtracting base fares.
- Total projected pay including any adjustment.

## Inputs

Enter the following for a full two-week pay period:
- Active hours.
- Engaged miles.
- Local minimum wage.
- Base earnings from rides.

## Formula

- Wage guarantee = active hours × local minimum wage × 1.2
- Mileage adjustment = engaged miles × 0.34
- Total earnings floor = wage guarantee + mileage adjustment
- Prop 22 adjustment payout = max(0, total earnings floor - base earnings)


## Notes

- Use engaged time and engaged miles only, not total online time. [code_file:3]

## License

Personal use.
