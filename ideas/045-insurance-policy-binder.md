# Idea 045: Family Insurance Policy Binder

## One-liner
A household-level insurance policy organizer that stores all your policies in one place, tracks renewal dates, coverage gaps, and tells your family where everything is if something happens.

## Problem
The average US household has 5-8 insurance policies (auto, home/renters, health, life, umbrella, pet, dental, vision) spread across different carriers, renewal dates, and payment schedules. Policy documents live in email inboxes, filing cabinets, and carrier portals. When something happens — a car accident, a pipe burst, a death — nobody knows which policy covers what, what the deductibles are, or where to find the policy number. Existing apps (Oneinsure, Cake) either focus on Indian markets, bundle estate planning complexity, or are just glorified note-taking. Users report they "could do the same thing with Excel and Google Calendar."

## Why now / why not built yet
Insurance companies want you locked into their portals — there's no incentive for them to build a cross-carrier view. Personal finance apps track bank accounts but ignore insurance. The problem is boring and unglamorous, which is exactly why indie devs haven't built it. But every household has this problem, and it becomes urgent exactly when you're least able to figure it out (emergencies, death).

## MVP Scope
- Add policies: carrier, type, policy number, premium, deductible, coverage limits, renewal date, agent contact
- Household view: all policies for all family members on one dashboard
- Renewal calendar with reminders (30 days, 7 days before)
- Coverage gap checker: flag common gaps (umbrella, disability, life insurance adequacy)
- Emergency access: shareable read-only link for spouse/family with all policy details

## Tech Stack
Next.js + Supabase (auth + DB). End-to-end encryption for policy data. Vercel hosting. Resend for reminders.

## Revenue Model
Free for up to 5 policies. $4/mo or $29/year for unlimited + coverage gap analysis + emergency sharing + PDF export.

## Difficulty
Easy

## Status
Idea
