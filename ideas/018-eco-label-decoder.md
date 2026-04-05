# Idea 018: LabelTruth — Eco-Label & Certification Decoder

## One-liner
A scan-and-decode tool that tells consumers what sustainability labels on products actually mean, who issues them, and whether they're credible or greenwashing — in plain language.

## Problem
There are 230+ eco-labels worldwide, and consumers cannot tell the difference between a rigorous third-party certification (USDA Organic, Fair Trade USA) and a logo a brand invented in Canva (e.g., "Earth Friendly Choice" with a green leaf). 53% of EU environmental claims are vague or misleading according to the European Commission. The 3-CO app exists but covers only 150 labels and is research-focused, not consumer-friendly. Consumers standing in a store aisle need a 5-second answer: "Is this label real? What does it guarantee?" — and nothing delivers that today.

## Why now / why not built yet
The EU's EmpCo Directive (effective Sept 2026) will crack down on unverified green claims, creating consumer awareness. With 230+ labels and no central registry, building a comprehensive database required effort that non-profits like Ecolabel Index started but never made mobile-friendly. The 3-CO app gamifies it but is too academic. A consumer-facing tool that gives instant, plain-language verdicts on any eco-label — with a credibility score — doesn't exist. The data is available (Ecolabel Index is open); the UX is missing.

## MVP Scope
- Photo scan: snap an eco-label, match it against a database of 200+ labels via image recognition
- Plain-language card: issuing body, what it certifies, how rigorous the audit is, credibility rating (1-5 stars)
- "Red flag" alerts for self-created labels with no third-party verification
- Search by label name or browse by category (food, fashion, cleaning, electronics)
- Comparison view: "This product has Fair Trade but not Organic — here's what that means"

## Tech Stack
Next.js PWA + Supabase on Vercel free tier. Label recognition via local image matching (no AI API needed — labels are logos with known hashes). Open data from Ecolabel Index.

## Revenue Model
Free for 10 scans/month. $2.99/mo for unlimited scans + personalized shopping lists + "greenwashing alerts" newsletter. Affiliate revenue from recommending genuinely certified alternatives.

## Difficulty
Medium

## Status
Idea
