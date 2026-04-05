# Idea 003: GigProof — Income Verification Report Generator for Gig Workers

## One-liner
Aggregates earnings data from multiple gig platforms (Uber, DoorDash, Instacart, etc.) into a professional income verification report that landlords and lenders actually accept.

## Problem
70+ million Americans work in the gig economy. When they apply for apartments or loans, landlords want proof of income — but gig workers have no pay stubs. They're told to provide "bank statements" or "1099s," but bank statements mix personal spending with income, and 1099s only arrive annually. Landlords reject applications, or gig workers must offer 2-3x security deposits to compensate. There is no standardized "income report" format for multi-platform gig workers that a landlord or loan officer can quickly review and trust.

## Why now / why not built yet
Gig platforms each have their own earnings dashboard but no export-friendly format. No one aggregates across platforms into a single professional document. Existing tools like Gridwise track earnings for the driver's benefit but don't produce landlord/lender-facing verification documents. The 1099-K threshold dropped to $5,000 in 2025, making formal documentation more important than ever.

## MVP Scope
- Connect earnings via platform CSV exports (Uber, Lyft, DoorDash, Instacart, Grubhub, Amazon Flex)
- Manual entry fallback for platforms without easy export
- Generate professional PDF report: monthly income summary, platform breakdown, 3/6/12-month averages, year-over-year trend
- Verification link: landlord/lender gets a unique URL to confirm report authenticity
- Bank statement cross-reference: upload bank statement to auto-match deposits to platform payouts

## Tech Stack
Next.js + Supabase on Vercel. PDF generation via @react-pdf/renderer. No external APIs needed — CSV parsing only.

## Revenue Model
First report free. $4.99 per report, or $9.99/mo for unlimited reports. Bulk pricing for property managers ($49/mo to verify unlimited applicants).

## Difficulty
Medium

## Status
Idea
