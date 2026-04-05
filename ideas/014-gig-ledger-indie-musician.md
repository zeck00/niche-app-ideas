# Idea 014: GigLedger — Indie Musician Income & Expense Tracker

## One-liner
A purpose-built income and expense tracker for independent musicians that understands gig pay structures, gear depreciation, and the messy reality of getting paid via Venmo, cash, and "we'll get you next time."

## Problem
Independent musicians (solo artists, session players, small-band members) juggle income from wildly inconsistent sources: bar gigs paid in cash, session work paid via Zelle 3 weeks late, streaming royalties in 17 different currencies, and merch sales on Square. Generic accounting tools like Wave or QuickBooks don't understand gig-specific categories (guarantee vs. door split vs. tip jar), and musicians lose thousands at tax time because they can't prove expenses for gear, mileage to rehearsals, and home studio deductions. Merch Cat handles merch inventory but doesn't track the full financial picture. Most musicians use no system at all.

## Why now / why not built yet
Musician-specific tools focus on either booking (Gigwell, BandHelper) or merch (Merch Cat) but nobody owns the financial hub. Accounting tools aren't worth customizing for someone making $15K-$60K/year from music. The audience is too small and too broke for enterprise software companies, but there are 2M+ independent musicians in the US alone, and they all need to file taxes.

## MVP Scope
- Quick-add income: cash gig, digital payment, royalties, merch — with music-specific categories
- Expense tracking: gear purchases with depreciation calculator, mileage log, studio rent
- Gig history: date, venue, pay type (guarantee/door/tips), actual amount received vs. promised
- Tax summary: Schedule C-ready report showing income by source, deductible expenses, net profit
- "Who owes me" tracker: log outstanding payments with reminder dates

## Tech Stack
Next.js + Supabase on Vercel free tier. Plaid free tier for optional bank linking. Export to CSV/PDF.

## Revenue Model
Free for up to 20 gigs/year. $7/mo for unlimited gigs + tax reports + gear depreciation tracking. Annual plan $59/year (pre-tax-season push).

## Difficulty
Easy

## Status
Idea
