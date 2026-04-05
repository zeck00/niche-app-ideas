# Idea 009: ProofPile — Automated Testimonial Collector for Solo Service Providers

## One-liner
Auto-sends testimonial requests to clients after project completion, collects text + video responses via a branded form, and generates embeddable testimonial widgets — built for solopreneurs, not enterprises.

## Problem
Solo service providers (consultants, coaches, freelancers, contractors) know testimonials drive sales but never collect them consistently. They feel awkward asking, forget to follow up, and when they do get a testimonial via email, it sits in their inbox forever. Existing tools (Senja, Famewall, Testimonial.to) charge $29-49/mo and are designed for SaaS companies collecting hundreds of reviews. A solo consultant who needs 5-10 strong testimonials per year can't justify that cost. In the UAE/ME market, bilingual testimonials (Arabic + English) add an extra layer — no tool handles RTL testimonial display properly.

## Why now / why not built yet
The testimonial collection space is crowded at the $30+/mo tier (SaaS-focused) but empty at the solo provider level. Solopreneurs need: (1) automated ask after project ends, (2) a simple form clients actually fill out, (3) a way to display them on their site. That's it. No one has built the $5/mo version of this with Arabic/RTL support.

## MVP Scope
- Connect project completion triggers (manual, Stripe payment webhook, or calendar event)
- Auto-send testimonial request email with branded collection form
- Form captures: text review, optional video (webcam recording), star rating, permission to display
- Testimonial wall: public page with all approved testimonials
- Embeddable widget: copy-paste code for any website, supports RTL/Arabic layout

## Tech Stack
Next.js + Supabase + Resend (email) on Vercel. Cloudflare R2 for video storage.

## Revenue Model
Free for up to 10 testimonials. $5/mo for unlimited testimonials + custom branding + video support. $12/mo for agency plan (multiple client brands).

## Difficulty
Easy

## Status
Idea
