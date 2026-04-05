# Idea 032: Dubai Small Yacht Charter Ops Manager

## One-liner
A booking, crew, and maintenance tracker for small yacht charter operators in Dubai who manage 1-5 boats and coordinate everything through WhatsApp and spreadsheets.

## Problem
Dubai has hundreds of small yacht charter companies operating 1-5 boats out of Dubai Marina, Dubai Harbour, and Palm Jumeirah marinas. These operators handle bookings (2-hour sunset cruises, full-day charters, overnight trips), crew scheduling (captains, deckhands, hostesses), maintenance logs (required by Dubai Maritime City Authority), and guest manifests. Most manage everything via WhatsApp groups and Google Sheets. Double-bookings happen frequently. Crew availability is tracked by memory. Maintenance is reactive, not scheduled. Enterprise yacht management software (Sealogical, Aquator Marine) targets superyachts and costs $200-500/mo per vessel — overkill for a 55-foot party yacht doing sunset cruises. The 2025 STCW amendments add new fatigue management requirements for crew, adding another compliance burden.

## Why now / why not built yet
Dubai's yacht charter market has exploded with tourism growth (17M+ visitors in 2024). Small operators have proliferated — many are individual boat owners who charter through agencies. The Dubai Maritime City Authority is tightening regulations. Enterprise solutions serve superyachts, not the budget charter segment. Nobody has built a lightweight tool because the market is geographically concentrated (Dubai/Abu Dhabi) and niche — but it is a real, growing niche with operators who have revenue and willingness to pay.

## MVP Scope
- Booking calendar with boat assignment (avoid double-booking across fleet)
- Crew roster: availability, certifications, rotation scheduling
- Maintenance log per vessel: scheduled tasks, engine hours, last service dates
- Guest manifest generator (required for port authority)
- Simple revenue tracker per boat per month

## Tech Stack
Next.js + Supabase (auth + DB) on Vercel. No external APIs needed for MVP.

## Revenue Model
Freemium: 1 boat free, AED 99/mo (~$27) for up to 5 boats. AED 49/boat/mo for fleets of 6+.

## Difficulty
Easy

## Status
Idea
