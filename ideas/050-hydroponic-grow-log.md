# Idea 050: Hydroponic Grow Log

## One-liner
A lightweight pH/EC/nutrient tracking journal for small-scale hydroponic and aquaponic growers that logs readings, spots trends, and alerts when parameters drift out of range.

## Problem
Small hydroponic growers (home hobbyists, micro-greens businesses, small greenhouse operators) check pH, EC (electrical conductivity), and water temperature daily. They write readings on paper, in Notes apps, or in spreadsheets with no trend analysis. When plants show deficiency symptoms, they can't look back and correlate with parameter changes. Hardware monitoring systems (Growee, HydroDirector) cost $200-$600 for sensors + software. Existing grow apps (BudLabs) are branded to specific nutrient companies. There's no brand-neutral, software-only grow log that just tracks what you're measuring.

## Why now / why not built yet
Hydroponics is booming (urban farming, local food, micro-greens businesses). Hardware-based monitoring systems are great but expensive. Most small growers already own a handheld pH/EC meter — they just need a place to log readings and see trends. Nobody has built a $5/mo software-only journal because the hydroponics software market is dominated by hardware companies bundling apps with sensors.

## MVP Scope
- Define grow systems (names, crop, method: DWC, NFT, ebb-flow, etc.)
- Quick daily log entry: pH, EC/PPM, water temp, reservoir level, notes
- Trend charts per system showing parameter history over time
- Out-of-range alerts: set ideal ranges per crop, get flagged when readings drift
- Harvest log: track yield per system per cycle for performance comparison

## Tech Stack
Next.js + Supabase (auth + DB). Chart.js or Recharts for trend visualization. Vercel hosting. PWA for quick logging.

## Revenue Model
Free for 1 system. $5/mo for unlimited systems + alerts + harvest analytics + CSV export.

## Difficulty
Easy

## Status
Idea
