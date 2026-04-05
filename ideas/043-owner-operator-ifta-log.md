# Idea 043: Owner-Operator IFTA Fuel Log

## One-liner
A stripped-down IFTA fuel tax reporting tool for solo owner-operator truckers that turns fuel receipts and odometer readings into quarterly state-by-state fuel tax reports.

## Problem
Owner-operator truckers (one person, one truck) must file IFTA (International Fuel Tax Agreement) reports quarterly, breaking down miles driven and fuel purchased in each state/province. Most track this on paper logs or a DieselBoss spreadsheet. Getting it wrong means audits and penalties. Full trucking TMS platforms (TruckLogics, Alvys) cost $20-$50/mo and bundle dispatch, invoicing, and fleet management — way too much for a solo operator who just needs to file IFTA. ATBS charges $150+/month for full bookkeeping. There's a gap between "paper logbook" and "$50/mo platform."

## Why now / why not built yet
IFTA reporting tools are built into fleet management software that assumes you manage multiple trucks and drivers. Solo owner-operators are the largest segment of trucking (350,000+ in the US) but are too small for fleet software and too busy driving to figure out spreadsheets. A purpose-built, $5/mo IFTA-only tool doesn't exist.

## MVP Scope
- Log fuel purchases: date, state, gallons, cost, receipt photo
- Log miles by state: manual odometer entry per state crossing (or GPS-assisted)
- Auto-calculate fuel tax owed/credit per state for the quarter
- Generate IFTA-ready report (PDF) matching the standard filing format
- Quarterly reminders with pre-filled data ready to review

## Tech Stack
Next.js + Supabase. PWA optimized for mobile (truckers log from the cab). Vercel hosting. Supabase Storage for receipt photos.

## Revenue Model
Free for 1 quarter of reporting. $5/mo or $49/year for ongoing quarters + receipt archive + multi-year history.

## Difficulty
Medium

## Status
Idea
