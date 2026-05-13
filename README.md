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

## How to use

1. Open the live GitHub Pages site.
2. Enter your biweekly totals.
3. Review the dashboard cards and pay breakdown bars.

## Deploy on GitHub Pages

1. Upload the main file as `index.html`.
2. Go to repository **Settings**.
3. Open **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/root`, then save.

GitHub Pages serves static sites from a repository and uses `index.html` as the main entry file. [web:22][web:23]

## Notes

- This is a static HTML dashboard with no database required. [code_file:3]
- It is designed for quick personal estimation and payout checking. [code_file:3]
- Use engaged time and engaged miles only, not total online time. [code_file:3]

## License

Personal use.
