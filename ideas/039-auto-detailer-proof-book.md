# Idea 039: Auto Detailer Proof Book

## One-liner
A before/after photo documentation app for mobile auto detailers that auto-generates shareable proof-of-work galleries and protects against damage claims.

## Problem
Mobile auto detailers take before/after photos on their phone camera roll, which gets messy fast. Photos aren't tied to specific jobs or customers. When a client claims the detailer scratched their car, they have no organized proof the scratch existed before. Existing detailing software (Mobile Tech RX, Fieldd) costs $30-$100/mo and bundles scheduling, invoicing, and CRM — overkill for solo detailers who just need organized photo proof. Many detailers use Instagram as their "portfolio" but can't send a client-specific gallery.

## Why now / why not built yet
Full-service detailing platforms bundle photo capture as one feature among dozens. Solo mobile detailers (a booming gig-economy segment) need just the photo workflow, not a $50/mo platform. The camera-roll-to-portfolio pipeline is broken and nobody has built a lightweight, purpose-built tool for it.

## MVP Scope
- Snap before/after photos tied to a job (customer name, vehicle, date, service type)
- Auto-generate a branded before/after comparison gallery with watermark
- Shareable link for customer (no app install needed)
- Damage documentation mode: timestamp + GPS-stamped photos for liability protection
- Public portfolio page: curated best-of gallery for social media/website embedding

## Tech Stack
Next.js + Supabase (auth + storage + DB) + Cloudflare R2 for image CDN. Vercel hosting. PWA for quick camera access.

## Revenue Model
Free for 10 jobs/month. $7/mo for unlimited jobs + custom branding + portfolio page. $3 add-on for PDF report generation.

## Difficulty
Easy

## Status
Idea
