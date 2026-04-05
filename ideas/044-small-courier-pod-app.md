# Idea 044: Small Courier Proof-of-Delivery App

## One-liner
A free-tier proof-of-delivery app for solo couriers and tiny delivery businesses that captures photo, signature, GPS, and timestamp proof — then sends it to the customer automatically.

## Problem
Solo couriers, local flower delivery shops, pharmacy delivery drivers, and small same-day delivery businesses need proof they delivered a package — especially for high-value or liability-sensitive items. They currently take a photo on their phone and text it to the customer, with no organized record. When disputes arise ("I never got it"), they have no timestamped, GPS-tagged proof. Existing last-mile platforms (Onfleet, Detrack, Track-POD) start at $29-$149/mo and are built for fleets of 5+ drivers with dispatch and route optimization. A solo courier doesn't need route optimization — they need proof.

## Why now / why not built yet
Last-mile delivery software targets fleet operators and logistics companies. The solo courier / micro-delivery segment (1-3 drivers) is growing fast thanks to same-day delivery demand, but these operators are priced out of fleet software. Nobody has built a "just proof-of-delivery" app at a $5/mo price point.

## MVP Scope
- Create a delivery: recipient name, address, package description, optional order number
- Capture proof: photo + GPS location + timestamp (auto-captured), optional signature
- Auto-send delivery confirmation to recipient via email/SMS with proof link
- Delivery history log with search and filter
- Proof archive: tamper-evident records with original metadata for dispute resolution

## Tech Stack
Next.js + Supabase (auth + DB + storage). Cloudflare R2 for photo storage. Vercel hosting. Resend for delivery confirmations.

## Revenue Model
Free for 30 deliveries/month. $5/mo for unlimited + SMS confirmations + branded proof pages. $12/mo for multi-driver team.

## Difficulty
Easy

## Status
Idea
