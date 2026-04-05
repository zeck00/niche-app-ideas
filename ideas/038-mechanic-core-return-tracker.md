# Idea 038: Mechanic Core Return Tracker

## One-liner
A dead-simple app for independent auto repair shops to track core deposits, return deadlines, and refund status so they stop losing hundreds per month to forgotten cores.

## Problem
Independent mechanics pay core deposits ($20-$300+) on alternators, starters, brake calipers, and other remanufactured parts. They must return the old "core" within a window (usually 30 days) to get the deposit refunded. Most shops track this on sticky notes or not at all. Missed returns mean pure profit loss — shops report losing $200-$500/month on forgotten cores. The existing shop management systems (Tekmetric, ShopMonkey) bury core tracking as an afterthought inside massive platforms that cost $200-$400/month.

## Why now / why not built yet
Full shop management software treats core returns as a line item, not a workflow. Solo mechanics and 2-3 bay shops can't justify $300/mo platforms just to track cores. Nobody has built a standalone, $10/mo tool focused purely on this one painful, money-leaking problem. The indie dev scene doesn't know this niche exists.

## MVP Scope
- Log a core deposit: part name, supplier, deposit amount, return deadline, VIN/job reference
- Dashboard showing pending cores sorted by urgency (days until deadline)
- Push/email reminders at 7 days, 3 days, and 1 day before deadline
- Mark as returned + track refund received (or disputed)
- Monthly summary: total deposits outstanding, total recovered, total lost

## Tech Stack
Next.js + Supabase (auth + DB) + Vercel. Resend for email reminders. PWA for mobile use in the shop.

## Revenue Model
Free for up to 5 active cores. $9/mo for unlimited cores + supplier analytics. One-time $29 for lifetime access option.

## Difficulty
Easy

## Status
Idea
