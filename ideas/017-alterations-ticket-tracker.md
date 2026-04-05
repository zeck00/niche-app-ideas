# Idea 017: StitchTicket — Solo Tailor & Alterations Job Tracker

## One-liner
A mobile-first job tracker for solo tailors and alterations shops that replaces the paper ticket pinned to each garment with a digital system for tracking orders, measurements, and pickup reminders.

## Problem
Solo tailors and small alterations shops (1-3 person operations) manage orders with paper tickets safety-pinned to garments, a physical notebook for measurements, and verbal pickup dates that customers forget. When a customer calls asking "is my dress ready?", the tailor digs through a rack of 40 garments to find the ticket. Existing solutions like Atelierware, Geelus, and Orderry are built for multi-employee shops with POS systems and cost $30-100+/mo. A solo tailor doing 15-30 jobs/week making $40K-$70K/year won't pay $50/mo for software. They need something as simple as their paper ticket — but searchable.

## Why now / why not built yet
Tailoring software companies target growing businesses that can afford $50+/mo subscriptions. The solo tailor — an immigrant seamstress working from home, a retired costume designer doing neighborhood alterations, a dry cleaner offering basic hemming — is too small and too price-sensitive. There are 30,000+ alterations/tailoring businesses in the US, most with 1-2 employees. They're invisible to SaaS companies but they all have smartphones.

## MVP Scope
- Quick job entry: customer name, phone, garment type, alteration needed, price quoted, due date
- Photo capture: snap the garment + pin location (replaces the paper ticket)
- Status board: incoming / in-progress / ready / picked-up — swipe to advance
- Auto-SMS pickup reminder: "Your alterations are ready for pickup" one day before due date
- Simple daily earnings view: jobs completed today, total revenue this week/month

## Tech Stack
Next.js PWA + Supabase on Vercel free tier. Twilio free trial or Resend for SMS reminders. Camera API for garment photos.

## Revenue Model
Free for up to 10 active jobs. $5/mo for unlimited jobs + SMS reminders + photo storage. $39/year annual plan.

## Difficulty
Easy

## Status
Idea
