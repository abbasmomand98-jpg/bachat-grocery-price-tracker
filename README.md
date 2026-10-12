# Bachat — Grocery Price Tracker (UX Concept)

**The problem:** In Pakistan, daily grocery prices swing wildly. Retail shops charge 2–3x the sabzi-mandi wholesale rate, no published reference prices exist, and monthly kitchen budgets blow up with no warning.

**The concept:** A mobile-first web app that shows daily mandi (wholesale) rates vs average retail prices per item, lets you build a basket and see totals at both rates with the PKR savings, tracks your monthly kitchen budget with overspend warnings, and flags price spikes (like tomatoes) before they hit your wallet.

## Features
- **Price feed** — mandi vs retail rates per kg/litre/dozen with % markup badges, live search + category filters (Grains, Vegetables, Dairy, Meat, Pantry), based on Karachi (Empress Market, Sabzi Mandi Super Highway)
- **Basket builder** — add items with quantity steppers; totals computed at mandi and retail rates with the savings highlighted in PKR
- **Monthly budget tracker** — set your budget (default PKR 45,000), log purchases, progress bar, on-track / warning / overspend states
- **Price-spike alerts** — automatic flags for items spiking 15%+ in a week, plus shopping-timing tips

## How to run
No build step, no dependencies. Just open `index.html` in any browser:

```
open index.html        # macOS
xdg-open index.html    # Linux
```

## Demo
Live demo: https://abbasmomand98-jpg.github.io/bachat-grocery-price-tracker/

## Tech
Plain HTML + CSS + JavaScript. All prices are realistic demo data for illustration.
