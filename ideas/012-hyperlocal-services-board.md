# Idea 012: NearTask — Hyperlocal Micro-Services & Skilled Neighbor Board

## One-liner
A neighborhood-level bulletin board for micro-services and one-off tasks — "tune my guitar," "help me move a couch," "teach me to bake bread" — connecting neighbors who need something done with neighbors who can do it.

## Problem
Nextdoor and Facebook Groups handle neighborhood chatter, but finding a specific micro-service ("anyone know someone who can fix a zipper?" or "need someone to teach my kid basic Arabic for 3 sessions") is buried in noise. TaskRabbit is for professional taskers in major cities — not for the retired carpenter down the street who'd happily fix your shelf for $20. Craigslist is sketchy and not community-verified. There's a gap for "trusted neighbor with a skill" discovery, especially in tight-knit communities, suburban neighborhoods, and expat compounds in the UAE/ME where WhatsApp groups serve this function badly.

## Why now / why not built yet
TaskRabbit requires professional profiles and serves metro areas. Nextdoor buries service requests in a general feed. No platform focuses specifically on hyperlocal skill exchange at the neighborhood level with trust signals (verified address, neighbor vouches). Reddit identified this exact gap — "lack of micro-skills or hyperlocal one-off gigs" — as an untapped opportunity. In UAE expat communities (compounds, building groups), this runs entirely on WhatsApp with zero discoverability.

## MVP Scope
- Neighborhood-scoped board: tasks and skills organized by category (home repair, tutoring, tech help, creative, errands)
- Post a need ("Looking for someone to teach basic pottery, 2 sessions") or offer a skill ("I can help with resume writing, $25/hr")
- Trust layer: verified address (via postal code + unit), neighbor endorsements
- Simple booking: agree on price/time via in-app chat, mark complete
- Arabic/English bilingual interface for UAE/ME communities

## Tech Stack
Next.js PWA + Supabase on Vercel. Resend for notifications. PostHog free tier for analytics.

## Revenue Model
Free to post and browse. $2.99/mo for "featured" listings (top of board). 5% service fee on transactions completed through the platform. Community sponsor tier at $19/mo for local businesses to advertise on their neighborhood board.

## Difficulty
Medium

## Status
Idea
