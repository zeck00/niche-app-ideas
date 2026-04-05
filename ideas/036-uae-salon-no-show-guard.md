# Idea 036: UAE Salon No-Show Guard & Arabic Booking Widget

## One-liner
A lightweight booking widget and no-show reduction tool for UAE salons and beauty centers, with native Arabic/English support, WhatsApp reminders, and deposit collection.

## Problem
UAE salons lose 15-25% of revenue to no-shows. The problem is particularly acute for ladies' salons and beauty centers in the GCC, where booking is predominantly done via WhatsApp or phone calls. Existing booking systems (Fresha, Booksy, Vagaro) have poor Arabic support — RTL text rendering breaks on client-facing booking pages, and appointment confirmations in Arabic look garbled. More critically, these platforms do not integrate with the WhatsApp-first booking culture of the UAE. A salon owner in Jumeirah gets 80% of bookings via WhatsApp voice notes and text messages — no booking system captures these. When a client no-shows for a AED 500 hair treatment, the salon has no deposit, no cancellation fee, and no record beyond a WhatsApp chat. The salon software market in the UAE is growing, but solutions are retrofitted Western tools, not Arabic-first.

## Why now / why not built yet
The UAE beauty market is growing at 4.5%+ annually. Salon software compliance requirements tightened in 2025-2026 (VAT integration, Emirates ID for some services). The no-show problem is universal but the WhatsApp-booking culture makes it uniquely hard to solve in the GCC. Western booking tools treat WhatsApp as an afterthought. Arabic-first salon tools like Salonaty exist but are primarily POS-focused, not booking-optimization-focused. Nobody has built a lightweight, no-show-specific tool because the market seems small — but a single busy salon losing AED 3,000-8,000/month to no-shows will happily pay AED 99/mo to fix it.

## MVP Scope
- Embeddable booking widget with native Arabic/English toggle (RTL-correct)
- WhatsApp automated reminders: 24hr and 2hr before appointment
- Optional deposit collection via payment link (Stripe UAE or Tap Payments)
- No-show tracking per client with automatic flagging of repeat offenders
- Simple daily appointment view for salon staff (not a full POS)

## Tech Stack
Next.js + Supabase (auth + DB) on Vercel. WhatsApp Business API for reminders. Stripe or Tap Payments for deposit collection.

## Revenue Model
Freemium: booking widget free for 1 staff member. AED 49/mo per staff member for WhatsApp reminders and no-show tracking. AED 99/mo with deposit collection.

## Difficulty
Easy

## Status
Idea
