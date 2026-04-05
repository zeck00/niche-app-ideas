# Idea 022: FlipLedger — Thrift Reseller Profit & Inventory Tracker

## One-liner
A mobile-first profit tracker for clothing resellers (Depop, Poshmark, Mercari) that captures true per-item profit by accounting for sourcing cost, platform fees, shipping, and time spent — the one number cross-listing tools don't give you.

## Problem
Clothing resellers thrift items for $3-15, photograph them, list them across 3-5 platforms, and sell them for $20-80. Cross-listing tools (Vendoo, Crosslist, Nifty) solve the listing problem but don't answer the critical question: "Am I actually making money on this item?" After Poshmark's 20% fee, $7 shipping, $5 sourcing cost, and 30 minutes of photography time, that $40 sale might be a $5 profit — or a loss. Resellers track this in spreadsheets (if at all), but updating a spreadsheet after every thrift run and every sale is a chore that 70% abandon within a month. Free Google Sheets templates exist but require manual fee calculations that differ per platform.

## Why now / why not built yet
Cross-listing platforms (Vendoo, Crosslist, Closo) focus on listing automation and inventory sync, not financial tracking. They tell you "this item sold on Poshmark" but not "this item earned you $4.12 after all costs." Accounting tools (Wave, QuickBooks) don't understand platform-specific fee structures. The reseller community is large (10M+ in the US) and growing fast with Gen Z thrifters, but the per-user revenue potential looks tiny to VC-backed startups. A solo-built tool on free infrastructure can serve this market profitably.

## MVP Scope
- Sourcing log: snap receipt, tag items, assign cost-per-item from a thrift haul
- Listing tracker: which platforms each item is listed on, with auto-calculated fees per platform
- Sale capture: mark as sold, enter sale price, platform auto-calculates fees + shipping
- Per-item profit card: sourcing cost + fees + shipping + optional time-cost = true profit
- Dashboard: total invested, total sold, total profit, average ROI per item, best sourcing spots

## Tech Stack
Next.js PWA + Supabase on Vercel free tier. Camera API for receipt/item photos. Fee calculators hardcoded per platform (Poshmark 20%, Mercari 10%, Depop 10%, eBay ~13%).

## Revenue Model
Free for 30 items. $4.99/mo for unlimited items + analytics + tax export. $39/year annual plan.

## Difficulty
Easy

## Status
Idea
