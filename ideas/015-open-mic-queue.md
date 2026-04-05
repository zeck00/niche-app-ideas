# Idea 015: MicQueue — Open Mic & Live Show Signup Manager

## One-liner
A QR-code-powered performer queue and signup system for open mic nights, comedy shows, and jam sessions that replaces the paper clipboard and lets hosts manage the lineup from their phone.

## Problem
Open mic nights at bars, comedy clubs, coffee shops, and community venues still run on paper sign-up sheets and a host shouting names into a microphone. Performers arrive not knowing how long the wait is, hosts lose track of the order, no-shows leave awkward gaps, and there's no way for regulars to pre-register. ScanQueue exists for karaoke but is karaoke-specific. Jotform and ClickUp templates require manual management and don't handle real-time queue flow. Hosts running 2-3 open mics per week waste 20+ minutes per night on clipboard logistics.

## Why now / why not built yet
Open mics are run by individual hosts at small venues — a market too fragmented and low-budget for event tech companies. Eventbrite is overkill. The karaoke world got ScanQueue, but comedy, poetry, acoustic, and jam session open mics have no equivalent. Post-COVID, open mics exploded as venues needed cheap programming, creating more demand from hosts who run multiple nights per week.

## MVP Scope
- Venue creates an event with QR code poster — performers scan to join the queue
- Performer enters name, act type (comedy/music/poetry), and estimated set length
- Host dashboard: live queue, drag to reorder, tap to mark "on stage" / "done" / "no-show"
- Audience-facing display: "Now performing" / "Up next" / "X performers remaining"
- Recurring event support: same QR code, same venue, weekly schedule

## Tech Stack
Next.js + Supabase on Vercel free tier. QR code generation via client-side library. Real-time updates via Supabase Realtime.

## Revenue Model
Free for 1 recurring event per venue. $6/mo for unlimited events + performer history + analytics (average wait time, busiest nights). $15/mo for multi-venue hosts managing 3+ locations.

## Difficulty
Easy

## Status
Idea
