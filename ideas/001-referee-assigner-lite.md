# Idea 001: Referee Assigner Lite

## One-liner
A dead-simple referee/umpire scheduling and payment tracker for small amateur sports leagues that can't justify $50+/mo enterprise tools.

## Problem
Small amateur leagues (recreational soccer, church basketball, youth flag football) with 5-20 teams still manage referee assignments via group texts and Venmo. Enterprise tools like Assignr and Horizon WebRef are built for large associations and cost $50-200+/mo. A league coordinator running a 12-team Sunday soccer league doesn't need enterprise — they need a clean calendar, availability collection, and a record of who got paid. Double-bookings and no-show refs are the #1 complaint, and 70%+ of small leagues still use spreadsheets.

## Why now / why not built yet
Existing referee scheduling tools (Assignr, RefR Sports, Stack Officials) target large officiating associations with hundreds of refs. They charge per-official or per-game fees that make no sense for a casual league with 8 volunteer refs. The small-league coordinator is invisible to these vendors.

## MVP Scope
- League setup: add teams, refs, game schedule
- Ref availability: refs mark open/blocked dates via shared link (no login required)
- Auto-assign refs to games based on availability + conflict rules (no back-to-back, no assigning to own team)
- SMS/email notification when assigned, with one-click confirm/decline
- Payment log: mark refs as paid per game, export for end-of-season totals

## Tech Stack
Next.js + Supabase (auth + DB) on Vercel free tier. Twilio free trial for SMS or Resend for email.

## Revenue Model
Free for 1 league up to 10 teams. $8/mo per additional league or $6/mo for leagues with 11-30 teams. One-time season pass option at $29.

## Difficulty
Easy

## Status
Idea
