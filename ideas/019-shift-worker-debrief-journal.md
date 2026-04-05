# Idea 019: ShiftDebrief — Post-Shift Journaling for High-Stress Workers

## One-liner
A 2-minute structured debrief journal designed specifically for nurses, EMTs, firefighters, and corrections officers to process shift experiences before they compound into burnout.

## Problem
High-stress shift workers (nurses, paramedics, police, corrections officers, ER techs) experience cumulative emotional load that generic wellness apps completely miss. After a 12-hour overnight shift dealing with a patient death or a violent incident, nobody opens Headspace for a 20-minute meditation. They need a 90-second emotional dump that's structured enough to be useful but fast enough to do in the parking lot before driving home. Existing journaling apps (Day One, Reflectly, Rosebud) are designed for morning routines and evening wind-downs — not for someone finishing a shift at 3 AM who needs to discharge what just happened. Grief apps focus on bereavement; burnout apps focus on corporate burnout. Nobody builds for the acute, recurring stress of shift work in high-stakes environments.

## Why now / why not built yet
Healthcare and first-responder burnout hit crisis levels post-COVID, but tech solutions target employers (EAPs, corporate wellness platforms) not the individual worker. B2C mental health apps are generic. Building for nurses or EMTs specifically requires understanding their workflow (12-hour shifts, rotating schedules, emotional trauma type) which consumer app teams don't have. The audience is large (4M+ nurses in the US alone) but scattered across institutions, so B2C acquisition is hard — but word-of-mouth in these tight-knit communities is incredibly strong.

## MVP Scope
- Post-shift check-in: 3 quick-tap screens — energy level, emotional intensity, one-word mood tag
- Structured debrief prompt: "What's one thing sticking with you from this shift?" (free text, 2-3 sentences max)
- Shift pattern tracking: correlate mood with shift type (day/night/swing), duration, and day-of-week
- Weekly digest: "Your toughest shifts were Tuesdays and nights. Your best coping pattern was X."
- Private vault: entries are encrypted, never shared, and can be bulk-exported or deleted

## Tech Stack
Next.js PWA + Supabase on Vercel free tier. Client-side encryption for journal entries. Push notifications via web push API.

## Revenue Model
Free with 7 entries/month. $4.99/mo for unlimited entries + trend analysis + weekly digests. $39/year annual plan. Future B2B play: hospital/department licenses at $3/user/mo.

## Difficulty
Easy

## Status
Idea
