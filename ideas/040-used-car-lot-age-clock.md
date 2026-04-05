# Idea 040: Used Car Lot Age Clock

## One-liner
A lightweight inventory aging dashboard for small independent used car dealers that shows exactly how many days each vehicle has sat on the lot, its carrying cost, and when to cut the price.

## Problem
Small independent used car dealers (5-30 cars on the lot) track inventory in spreadsheets or their heads. Every day a car sits costs money (floor plan interest, insurance, lot rent). Dealers know they should cut prices after 45-60 days but have no system reminding them. Full DMS platforms (Frazer, DealerSocket) cost $200-$500/mo and are designed for larger operations. The result: cars sit too long, margins evaporate, and cash flow stalls.

## Why now / why not built yet
Existing dealer management systems are enterprise-grade and priced for 50+ car lots. Small buy-here-pay-here and independent lots with 10-20 cars can't justify those costs. Nobody has built a simple "inventory aging clock" that just answers: how old is each car, what is it costing me daily, and when should I drop the price?

## MVP Scope
- Add vehicles: VIN decoder auto-fills year/make/model, enter purchase price and date
- Dashboard: grid of vehicles sorted by days-on-lot with color-coded urgency (green/yellow/red)
- Daily carrying cost calculator (floor plan rate + insurance + lot rent / total cars)
- Price drop alerts: configurable rules (e.g., "flag at 45 days, urgent at 60 days")
- Sold log: mark as sold, record sale price, auto-calculate actual profit after carry costs

## Tech Stack
Next.js + Supabase. Free VIN decoder API (NHTSA vPIC). Vercel hosting. Resend for email alerts.

## Revenue Model
Free for up to 10 vehicles. $12/mo for unlimited vehicles + profit analytics + export. One-time $49 lifetime option.

## Difficulty
Easy

## Status
Idea
