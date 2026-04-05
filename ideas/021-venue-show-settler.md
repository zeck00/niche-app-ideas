# Idea 021: ShowSettle — Small Venue Show Settlement Calculator

## One-liner
A dead-simple show settlement tool for small music venue owners and independent promoters who need to split door revenue with artists using guarantee-vs-door deals without enterprise booking software.

## Problem
Small music venues (under 300 capacity) and independent promoters settle with artists after every show using napkin math. A typical deal is "$200 guarantee or 80% of door after expenses, whichever is higher" — and calculating this at midnight after the show while the artist is waiting to get paid is error-prone and awkward. VenuePilot, Prism.fm, and Gigwell are full-featured booking platforms that cost $50-300+/mo — absurd for a bar owner doing 2 shows/week. Most small venues use a calculator app and a handshake. There's no record, disputes happen, and artists get shorted.

## Why now / why not built yet
Venue management software targets mid-to-large venues and festival promoters with budgets for subscriptions. The bar owner in a college town who books 2 local bands on Fridays is not their customer. Independent promoters running DIY shows in warehouse spaces and community centers are invisible to the industry. Yet these are the venues where 80%+ of live music actually happens. The settlement math is consistent enough to be productized but niche enough that nobody has.

## MVP Scope
- Show setup: venue name, date, artist(s), deal structure (flat guarantee / door split / guarantee-vs-door)
- Door count input: ticket price, number sold, guest list count
- Expense deductions: sound engineer, door person, marketing costs — with defaults saveable per venue
- Auto-calculate settlement: shows the math transparently, generates a one-page settlement sheet
- Both parties sign digitally on-screen; PDF receipt emailed to artist and venue

## Tech Stack
Next.js + Supabase on Vercel free tier. PDF generation via client-side library. Email via Resend free tier.

## Revenue Model
Free for 4 shows/month. $9/mo for unlimited shows + saved venue presets + artist payment history + year-end tax summary. $79/year annual plan.

## Difficulty
Easy

## Status
Idea
