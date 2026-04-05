# Idea 007: VoxDesk — Voice Actor Audition & Client Manager

## One-liner
A lightweight CRM and project tracker built specifically for freelance voice actors: audition pipeline, client follow-ups, rate tracking, and audio file delivery — all in one place.

## Problem
Freelance voice actors juggle auditions across 5+ platforms (Voices.com, Voice123, Backstage, Fiverr, direct clients), track bookings in spreadsheets, send audio files via email or WeTransfer, and invoice through PayPal. They have no unified view of their audition-to-booking pipeline, win rate, or average rate per word/hour. The industry recommends tools like Trello and Moxie ($20/mo), but these are generic — they don't understand audition workflows, turnaround times, or usage rights tracking, which are unique to voice work.

## Why now / why not built yet
Voice acting has exploded as a remote gig (podcasts, audiobooks, e-learning, gaming). There are 100k+ freelance voice actors in the US alone. But no tool is purpose-built for their workflow. General freelance CRMs don't track audition win rates, usage rights (broadcast vs. web vs. perpetual), or per-word/per-minute rate calculations. The voice actor community is tight-knit and underserved — a niche tool would spread fast through industry forums and Facebook groups.

## MVP Scope
- Audition tracker: log submissions with platform, client, project type, rate quoted, status (submitted/callback/booked/lost)
- Client CRM: contact info, past projects, preferred rates, notes
- Project board: active jobs with deadline, script status, recording status, delivery status
- Rate calculator: per word, per minute, per finished hour — with usage rights multiplier
- Secure audio delivery: upload final files, client gets download link with expiration

## Tech Stack
Next.js + Supabase on Vercel. Cloudflare R2 for audio file storage (free tier: 10GB).

## Revenue Model
Free for up to 10 active auditions/projects. $9/mo for unlimited tracking + file delivery. $15/mo for team plan (agents managing multiple talent).

## Difficulty
Easy

## Status
Idea
