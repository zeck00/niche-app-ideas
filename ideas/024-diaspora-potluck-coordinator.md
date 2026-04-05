# Idea 024: GatherRoots — Diaspora Community Event & Potluck Coordinator

## One-liner
A lightweight event coordination tool for diaspora community organizers managing cultural gatherings, potlucks, and holiday celebrations where the real challenge isn't ticketing — it's coordinating who's bringing biryani and who's setting up chairs.

## Problem
Diaspora community organizers (Indian associations, Nigerian community groups, Filipino barangay chapters, Arab cultural clubs) run 5-20 events per year — Diwali dinners, Eid celebrations, Independence Day picnics, cultural nights. These events are coordinated through WhatsApp group chaos: "Who's bringing what dish?", "We need 10 volunteers for setup", "Please send $15 per family via Zelle to Aunty Fatima." Eventbrite handles ticketing but not potluck coordination or volunteer sign-up. Google Forms collect RSVPs but can't track who paid, who's bringing what, and who volunteered for cleanup. The organizer (always a volunteer) spends 20+ hours per event on logistics that should take 2.

## Why now / why not built yet
Event tech targets professional organizers and companies. Diaspora community events are volunteer-run, informal, and hybrid (part ticketed, part potluck, part cultural program). No event platform handles the combination of: RSVP + food coordination + volunteer shifts + informal payment collection + multilingual communication. The audience is massive but invisible to tech companies because these events don't show up on Eventbrite — they happen in temple halls, community centers, and rented parks, organized via WhatsApp.

## MVP Scope
- Event page: date, location, description — shareable link (no app download needed)
- Potluck board: dish categories with signup slots ("We need 3 rice dishes, 2 desserts, 5 drinks")
- Volunteer shifts: setup, food service, cleanup — sign up with time slots
- Payment tracker: mark who's paid the per-family contribution (integrates with nothing — just a checklist the organizer updates)
- Multilingual: interface in English + one RTL language (Arabic/Urdu) and one additional language (Hindi/Tagalog/Yoruba)

## Tech Stack
Next.js + Supabase on Vercel free tier. i18n for multilingual support. PWA for mobile-first access.

## Revenue Model
Free for 1 event at a time. $5/mo for unlimited events + payment tracking + recurring event templates + attendee directory. $39/year for community organizations with 3+ organizers.

## Difficulty
Easy

## Status
Idea
