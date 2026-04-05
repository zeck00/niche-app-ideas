# Idea 049: Freight Load Profit Calculator

## One-liner
A per-load profitability calculator for small freight brokers and carriers that factors in fuel, tolls, deadhead miles, driver pay, and broker margin to show true profit before accepting a load.

## Problem
Small freight brokers (1-5 person operations) and owner-operators evaluate loads from load boards (DAT, Truckstop.com) dozens of times per day. The posted rate looks good, but after fuel costs, deadhead miles to pickup, tolls, lumper fees, and detention time, the load might be unprofitable. Most do this math in their head or on a napkin. Full TMS platforms calculate profitability but cost $200-$500/mo and require full onboarding. There's no quick "plug in the numbers, get a go/no-go" calculator for the person staring at a load board.

## Why now / why not built yet
Load board platforms show rates and mileage but don't factor in the broker/carrier's own cost structure (their specific fuel cost per mile, insurance overhead, etc.). TMS software does this but is priced for mid-size brokerages. The micro-broker segment (solo broker with an MC number, working from home) is exploding — 17,000+ new broker authorities per year in the US — and they need a $5 tool, not a $300 platform.

## MVP Scope
- Quick calculator: enter origin, destination, rate, fuel price, MPG, deadhead miles
- Save your cost profile: per-mile costs, insurance, desired margin percentage
- Instant result: gross revenue, total cost, net profit, profit per mile, go/no-go rating
- Load history: log accepted loads and track actual vs. estimated profit
- Lane analysis: over time, see which lanes (routes) are most profitable

## Tech Stack
Next.js + Supabase (auth + DB). Free mileage API or simple zip-to-zip calculation. Vercel hosting. PWA for mobile.

## Revenue Model
Free calculator with no saved history. $5/mo for saved profiles, load history, and lane analytics. $39/year option.

## Difficulty
Easy

## Status
Idea
