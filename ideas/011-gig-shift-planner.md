# Idea 011: ShiftWise — Multi-App Gig Worker Shift Planner & Earnings Optimizer

## One-liner
A weekly planner for multi-app gig workers (Uber + DoorDash + Instacart) that tracks hours, earnings, and expenses per platform side-by-side — showing which app actually pays more per hour after costs.

## Problem
Multi-app gig drivers are the norm — most work 2-4 platforms simultaneously to minimize downtime. But they have no unified view of their true hourly earnings per platform after gas, vehicle wear, and phone costs. Gridwise tracks mileage; Maxymo automates app-switching; neither answers the fundamental question: "Am I actually making more on DoorDash or Uber this week?" Drivers make platform allocation decisions based on gut feel, not data. In the UAE, Careem/Talabat/Deliveroo drivers face the same problem, with the added complexity of platform commission differences (Careem 25%, Deliveroo 15%).

## Why now / why not built yet
Existing gig tools focus on single features (mileage tracking, tax prep, app-switching automation). None provide a simple weekly dashboard that compares net earnings per hour across platforms. The comparison requires combining hours worked, gross earnings, platform fees, and variable costs — a calculation most drivers do on paper or not at all.

## MVP Scope
- Log shifts: start/end time, platform, earnings, trips/deliveries completed
- Expense tracking: gas/fuel, car wash, phone mount, data plan (allocated per platform by hours)
- Dashboard: net $/hour per platform this week, this month, all-time
- Optimal schedule suggestions: "Your DoorDash dinner shifts net $22/hr vs Uber's $17/hr"
- Weekly PDF earnings summary (for income proof / personal records)

## Tech Stack
Next.js PWA + Supabase on Vercel free tier. Charts via Recharts. PDF via @react-pdf/renderer.

## Revenue Model
Free with ads (basic dashboard). $4.99/mo for ad-free + PDF exports + expense tracking. $2.99/mo UAE-localized tier (AED support, Careem/Talabat/Deliveroo presets).

## Difficulty
Easy

## Status
Idea
