# Idea 048: Senior Social Activity Finder

## One-liner
A curated local activity board for seniors that aggregates free/low-cost events from senior centers, libraries, churches, and community orgs — filterable by mobility level, transport needs, and interests.

## Problem
Isolated seniors want to stay active but don't know what's available near them. Senior center programs, library events, church socials, free exercise classes, and community meals are scattered across different websites, Facebook pages, and paper flyers. Adult children trying to help their parents find activities spend hours searching. Existing event platforms (Eventbrite, Meetup) aren't designed for seniors — the UX is overwhelming, events skew young, and there's no filter for "wheelchair accessible" or "provides transportation."

## Why now / why not built yet
Senior isolation is a public health crisis (the US Surgeon General's loneliness advisory). The events and activities exist — senior centers run dozens of programs — but discovery is broken. Tech companies don't build for 70+ demographics. The data is hyperlocal and fragmented, which makes it unattractive for VC-backed startups. Perfect for a simple, community-submitted activity board.

## MVP Scope
- Browse activities by zip code, date, category (exercise, social, educational, meals, arts)
- Filters: mobility level (fully mobile, walker, wheelchair), cost (free/paid), transportation provided
- Senior centers and community orgs can submit/manage their own events (self-serve)
- Save favorites and get weekly email digest of upcoming local activities
- Large-text, high-contrast, minimal UI designed for older users

## Tech Stack
Next.js + Supabase (auth + DB). Vercel hosting. Resend for weekly digest emails. Optional: pull from public library/parks event APIs.

## Revenue Model
Free for seniors. Senior centers and activity providers pay $8/mo to list and promote events. Sponsored placement for local businesses ($15/mo).

## Difficulty
Medium

## Status
Idea
