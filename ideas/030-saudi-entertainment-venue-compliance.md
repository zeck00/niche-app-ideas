# Idea 030: Saudi Entertainment Venue Compliance Manager

## One-liner
A GEA/SCEGA compliance checklist and permit tracker for small entertainment venues, event organizers, and family entertainment centers in Saudi Arabia.

## Problem
Saudi Arabia's entertainment sector is booming post-Vision 2030 — the GEA estimates 450,000 new jobs by 2030. Thousands of small venues (family entertainment centers, escape rooms, VR arcades, small event spaces, cafes with live shows) need GEA licenses. The licensing regulation defines 10 license types across 3 categories, each with different requirements for safety plans, crowd management, medical teams, content compliance, and cultural standards. The GEA/SCEGA portal has improved, but operators still struggle to understand which license they need, what documents to prepare, and how to maintain ongoing compliance. A failed inspection means warnings, forced closure, or permanent blacklisting. Family entertainment centers alone make up 36% of the market, and VR arcades are growing at 18.5% CAGR — these are first-time operators who have never dealt with entertainment regulation before.

## Why now / why not built yet
Saudi entertainment spending exceeded SAR 50B in 2024-2025 investment alone. The sector is brand new — cinemas only opened in 2018, mixed-gender concerts started in 2019. Most operators are first-timers with zero compliance experience. The GEA regulation document is dense and in formal Arabic. SCEGA enhanced its digital portal in 2026, but it is a submission tool, not a guidance tool. No one has built an operator-facing compliance companion because the entire sector barely existed 5 years ago.

## MVP Scope
- License type selector: answer 5 questions, get told which GEA license(s) you need
- Pre-built compliance checklists per license type (safety, crowd management, content, medical)
- Document preparation tracker with templates (emergency plans, crowd control plans)
- Permit renewal calendar with auto-reminders
- Bilingual Arabic/English interface

## Tech Stack
Next.js + Supabase (auth + DB) on Vercel. No external APIs needed.

## Revenue Model
Freemium: license selector and basic checklist free. SAR 99/mo (~$26) for full compliance tracking, document templates, and renewal reminders. SAR 249 one-time for GEA application preparation package.

## Difficulty
Medium

## Status
Idea
