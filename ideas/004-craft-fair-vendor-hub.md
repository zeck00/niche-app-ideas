# Idea 004: FairFlow — Craft Fair & Market Vendor Management

## One-liner
A lightweight vendor management tool for craft fair organizers: applications, booth assignments, payment tracking, and vendor communication — replacing the spreadsheet-and-email chaos.

## Problem
Craft fair and farmers market organizers (often volunteers or small business owners) manage 20-200 vendor applications per event using Google Forms, spreadsheets, and personal email. They manually track who applied, who paid, booth assignments, electricity needs, insurance certificates, and day-of logistics. When events recur weekly/monthly (like farmers markets), the admin burden multiplies. Existing solutions like Eventeny ($99+/mo) and Seen Markets are priced for large operations. The small-town Saturday market with 30 vendors has no affordable option.

## Why now / why not built yet
Enterprise event platforms (Eventeny, ConventionForce) serve large festivals and conferences. They're too complex and expensive for a community craft fair organizer running 1-2 events/month with 20-80 vendors. The UAE craft market scene is also booming — ARTE runs weekly markets in Dubai, and the government allocated AED 60 million to promote handicrafts — but organizers there use the same manual processes.

## MVP Scope
- Event creation with customizable vendor application form
- Vendor dashboard: apply, upload insurance/permits, pay booth fee (Stripe)
- Organizer dashboard: review applications, approve/reject, assign booth numbers on visual map
- Automated emails: acceptance, payment reminders, day-of logistics
- Recurring event templates (duplicate settings for weekly/monthly markets)

## Tech Stack
Next.js + Supabase + Stripe on Vercel free tier.

## Revenue Model
Free for events under 15 vendors. $12/mo for unlimited vendors per event, or $2/vendor/event for pay-as-you-go. Annual plan at $99/year.

## Difficulty
Easy

## Status
Idea
