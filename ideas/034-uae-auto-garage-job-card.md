# Idea 034: UAE Auto Garage Digital Job Card

## One-liner
A bilingual Arabic/English digital job card and customer communication tool for independent auto repair shops in the UAE, replacing paper job cards with photo-documented repair tracking.

## Problem
The UAE has thousands of independent auto repair garages — from Al Quoz industrial area in Dubai to Mussafah in Abu Dhabi. These shops run on paper job cards: a mechanic writes the car details, customer complaint, parts used, and labor on a carbon-copy form. The customer gets a handwritten receipt they cannot read (often in a mix of Arabic, English, and Urdu). There is no digital record, no before/after photos, no way for the customer to approve additional work remotely, and no service history. When a customer disputes a charge or claims work was not done, the garage has no evidence. Meanwhile, the customer has no way to know their car's service history across multiple shops. Enterprise DMS systems (like AutoFlow or AutoLeap) cost AED 300-1000/mo and require training that multilingual workshop staff cannot absorb.

## Why now / why not built yet
UAE vehicle ownership is growing rapidly, but trust in independent garages remains low — customer complaints about unauthorized repairs, overcharging, and poor communication are constant. The UAE consumer protection framework is tightening. Yet the independent garage segment (which does 60%+ of non-warranty repairs) has zero digital tooling. Western garage management software does not support Arabic, does not handle the multi-language workforce reality (Arabic-speaking customers, Hindi/Urdu-speaking mechanics, English documentation), and is priced for Western markets.

## MVP Scope
- Digital job card: vehicle details, customer complaint, diagnosis, approved work, parts used, labor
- Photo documentation: before/after repair photos attached to each job card
- Customer approval flow: WhatsApp link to approve additional work with cost estimate
- Service history per vehicle (searchable by plate number)
- Bilingual job card PDF generation (Arabic/English) for customer receipt

## Tech Stack
Next.js + Supabase (auth + DB + storage for photos) on Vercel. WhatsApp Business API for customer links. PWA for tablet/phone use in the workshop.

## Revenue Model
Freemium: 20 job cards/month free, AED 49/mo (~$13) unlimited. AED 99/mo with customer approval flow and service history lookup.

## Difficulty
Easy

## Status
Idea
