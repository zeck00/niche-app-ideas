# Idea 023: CarbonSnap — 15-Minute Carbon Footprint Estimator for Small Businesses

## One-liner
A quick-and-dirty carbon footprint estimator that gives small businesses (cafes, salons, studios, shops) a credible emissions snapshot in 15 minutes without needing a sustainability consultant or enterprise ESG software.

## Problem
Small businesses increasingly face pressure from customers, landlords, and local regulations to demonstrate environmental awareness, but carbon accounting software (Persefoni, Plan A, Watershed) is built for enterprises and costs $5K-50K+/year. A coffee shop owner who wants to know "roughly how much CO2 does my business produce?" and put a credible number on their window has zero options between "guess" and "hire a consultant." Seedling and Arbor target SMEs but still assume a sustainability officer exists. For a 5-employee business, even $500/year for carbon reporting is absurd relative to revenue.

## Why now / why not built yet
ESG reporting is cascading down from public companies to their supply chains, and small businesses are starting to feel the pressure. Over 1,255 ESG regulations have been introduced globally since 2011. But the carbon accounting market chases enterprise deals ($50K+ ACV). Nobody wants to build a $5/mo tool for a nail salon. The data needed for basic estimates (industry emission factors, energy usage multipliers, transportation factors) is freely available from EPA and DEFRA. The tooling gap is between "nothing" and "$5,000/year" — and that gap is enormous.

## MVP Scope
- Guided questionnaire: business type, square footage, energy bills, employee commutes, waste estimate (10-15 questions)
- Auto-calculate using EPA/DEFRA emission factors by industry and region
- One-page report: estimated annual CO2e, breakdown by scope (energy, transport, waste), comparison to industry average
- Actionable tips: top 3 things this specific business can do to reduce emissions
- Shareable badge: "Our estimated carbon footprint is X tons/year" for website or window display

## Tech Stack
Next.js + Supabase on Vercel free tier. Static emission factor database (no API calls needed). PDF report generation client-side.

## Revenue Model
First report free. $4.99/report for updated annual snapshots. $9/mo for quarterly tracking + badge embed + reduction tracking over time.

## Difficulty
Easy

## Status
Idea
