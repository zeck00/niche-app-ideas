# Idea 016: GearLog — Freelance Audio/AV Equipment Tracker

## One-liner
An equipment inventory and loan tracker for freelance sound engineers, AV techs, and event production crews who constantly lend, rent, and lose track of who has their $3,000 condenser mic.

## Problem
Freelance sound engineers and AV technicians own $10K-$100K+ in personal gear that they bring to gigs, lend to colleagues, and rent to clients. There is no simple tool to track what's in the locker, what's on a job site, what's lent out (and to whom), and what needs maintenance. Gear goes missing constantly. When invoicing, engineers manually recall which equipment they brought to calculate rental surcharges (typically 8-15% of gear value). Enterprise asset tracking tools (EZOfficeInventory, Sortly) are built for warehouses, not a freelancer with 40 items in a Pelican case. Most engineers use a spreadsheet they never update.

## Why now / why not built yet
The freelance AV/sound market is huge but invisible — these are solo operators, not companies. Asset management software targets businesses with hundreds of items and multiple warehouses. Nobody builds for the guy with 3 racks of audio gear in his garage who works 150 gigs/year. The pain is real but the market looks too small per-user to attract investment. A solo-built tool on free infrastructure changes that math.

## MVP Scope
- Equipment catalog: name, serial number, value, purchase date, photo, condition notes
- Location tracking: home / on-gig / lent-to (person + return date) / in-repair
- Gig kit builder: drag items into a "gig bag" for upcoming jobs, auto-generate packing list
- Rental rate calculator: auto-suggest per-day rental based on item value and depreciation
- Lending log: who borrowed what, when, agreed return date, with overdue alerts

## Tech Stack
Next.js + Supabase on Vercel free tier. Cloudflare R2 free tier for gear photos. PWA for offline access at venues.

## Revenue Model
Free for up to 20 items. $8/mo for unlimited items + lending log + rental invoicing. $49/year annual plan.

## Difficulty
Easy

## Status
Idea
