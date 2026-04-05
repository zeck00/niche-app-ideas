# Idea 029: Dubai Holiday Home Compliance & Tourism Dirham Tracker

## One-liner
An all-in-one compliance tool for Dubai short-term rental hosts that automates Tourism Dirham calculations, tracks DET permit renewals, and generates guest check-in reports.

## Problem
Dubai has 12,000+ licensed holiday home units, and the number is growing rapidly. Every host must: (1) maintain a valid DET (formerly DTCM) holiday home permit, (2) calculate and remit Tourism Dirham fees (AED 10-15 per bedroom per night, capped at 30 consecutive nights), (3) report guest check-in/check-out data to DET, and (4) ensure their property classification stays current. Most hosts manage this with spreadsheets or rely on expensive management companies (who take 15-25% of revenue). The Tourism Dirham calculation alone is surprisingly complex — it varies by property classification, caps at 30 nights, and must be remitted monthly. Hosts who get it wrong face fines ranging from tens of thousands of dirhams to blacklisting from the tourism system.

## Why now / why not built yet
Dubai's short-term rental market is exploding. The DET regulatory framework tightened in 2024-2025 with stricter enforcement. The Tourism Dirham System 2.0 launched with new reporting requirements. Tools like Chekin handle guest registration but do not do Tourism Dirham calculations or permit renewal tracking. Hostaway and Guesty are vacation rental management platforms but cost $50-200/mo and do not have Dubai-specific compliance features built in. No lightweight, Dubai-specific compliance-only tool exists for the solo host managing 1-5 units.

## MVP Scope
- DET permit tracker: expiry dates, renewal reminders, required documents checklist
- Tourism Dirham calculator: auto-calculates fees based on bookings, classification, and occupancy
- Monthly Tourism Dirham remittance report (ready to submit)
- Guest check-in/check-out log with required data fields per DET requirements
- Property classification guide and self-assessment

## Tech Stack
Next.js + Supabase (auth + DB) on Vercel. Airbnb iCal import for booking sync.

## Revenue Model
Freemium: 1 property free, AED 49/mo (~$13) per additional property. One-time AED 99 for DET application document preparation guide.

## Difficulty
Easy

## Status
Idea
