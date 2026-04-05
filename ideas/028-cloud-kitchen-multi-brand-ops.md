# Idea 028: Cloud Kitchen Multi-Brand Ops Dashboard

## One-liner
A unified order and profitability dashboard for UAE cloud kitchen operators running multiple virtual brands across Talabat, Deliveroo, and Noon Food simultaneously.

## Problem
UAE cloud kitchens typically operate 3-8 virtual restaurant brands from a single kitchen. Each brand is listed on multiple delivery platforms (Talabat, Deliveroo, Noon Food, Careem Food). That means an operator with 5 brands on 3 platforms is logging into 15 different dashboards daily. Platform commissions range from 25-35%, but each platform has different fee structures, promotional deductions, and payment cycles. Operators cannot answer basic questions: "Which brand is most profitable on which platform?" or "Am I losing money on Brand X's Talabat promotions?" Grubtech and Foodics handle order aggregation, but they are enterprise-priced (AED 500-2000/mo) and focus on order routing, not profitability analytics per brand per platform.

## Why now / why not built yet
The UAE cloud kitchen market hit $430M in 2025 and is projected to pass $1B by 2032 (14.1% CAGR). Dubai introduced a new Ghost Kitchen License category making it cheaper to launch. The DCCPFT 2025 guidelines now require platforms to disclose full commission structures upfront, meaning operators finally have the data to do proper margin analysis — but no affordable tool to do it with. Enterprise solutions exist but price out the solo operators and small teams that make up the majority of cloud kitchen operators.

## MVP Scope
- Manual order entry or CSV import from each delivery platform's seller dashboard
- Brand-by-platform P&L: revenue, commissions, delivery fees, promotions, net margin
- Recipe cost integration: input ingredient costs per dish, see food cost % per brand
- Weekly/monthly profitability report per brand per platform
- "Kill or keep" alerts: flag brands or platform listings with margins below a configurable threshold

## Tech Stack
Next.js + Supabase (auth + DB) on Vercel. No external APIs for MVP.

## Revenue Model
Freemium: 2 brands free, AED 99/mo (~$27) for up to 10 brands across unlimited platforms. AED 199/mo with recipe costing module.

## Difficulty
Medium

## Status
Idea
