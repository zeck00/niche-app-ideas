# Idea 026: Noon/Amazon.ae Seller Profit Dashboard

## One-liner
A real-time profit tracker for UAE e-commerce sellers on Noon and Amazon.ae that calculates true margins after all hidden fees, commissions, and VAT.

## Problem
UAE e-commerce sellers on Noon and Amazon.ae struggle to understand their real profit per product. Noon charges referral commissions (5-27% depending on category), fulfillment fees, storage fees, return admin fees, cancellation penalties, and 5% VAT on top. Amazon.ae has a different fee structure entirely. Sellers running on both platforms (increasingly common) have no unified view of which products are actually profitable where. Existing tools like SmartToolsPack offer basic calculators, but they are static — you punch in numbers once. There is nothing that imports order history, tracks fee changes over time, and shows "your actual margin last month was 8%, not the 22% you thought." Most sellers discover they are losing money on certain SKUs only after months of selling.

## Why now / why not built yet
UAE e-commerce is surging — Noon processed $3B+ GMV in 2024. The seller base is growing fast, with thousands of new sellers from India and Pakistan entering via cross-border programs. Noon changed its fee structure three times in 2024-2025 alone. Amazon.ae commission rates differ from Amazon.com. No one has built a multi-platform margin tracker specifically for the GCC fee structures (AED-denominated, UAE VAT rules, dual-platform). Western tools like Jungle Scout and Helium 10 do not support Noon at all.

## MVP Scope
- Manual order entry or CSV import from Noon/Amazon.ae seller dashboards
- Fee calculator engine with current Noon and Amazon.ae commission rates by category
- Per-SKU profit/loss breakdown including all fees, shipping, returns, and VAT
- Cross-platform comparison: "This product makes AED 12 on Noon but loses AED 3 on Amazon.ae"
- Monthly P&L summary exportable for VAT filing

## Tech Stack
Next.js + Supabase (auth + DB) on Vercel. No external APIs for MVP (CSV import). Future: Noon Seller API integration.

## Revenue Model
Freemium: 10 SKUs free, AED 39/mo (~$11) for unlimited SKUs. AED 99/mo for multi-platform (Noon + Amazon.ae combined).

## Difficulty
Easy

## Status
Idea
