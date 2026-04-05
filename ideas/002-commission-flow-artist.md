# Idea 002: CommissionFlow — Freelance Illustrator Order Manager

## One-liner
An end-to-end commission pipeline for freelance illustrators: intake form, deposit collection, revision tracking, and final delivery — replacing the chaos of DMs, PayPal requests, and spreadsheets.

## Problem
Freelance illustrators and digital artists manage custom commissions through a patchwork of Instagram DMs, Discord messages, PayPal invoice links, and Google Sheets trackers. 70% of freelance illustrators report late payments. Revision scope creep is rampant because nothing is documented. Artists selling $50-500 commissions can't justify $30/mo tools like HoneyBook designed for photographers. Etsy sells thousands of Notion commission tracker templates — proof that artists are desperate for structure but have no real tool.

## Why now / why not built yet
General freelance tools (Bonsai, HoneyBook) are built for photographers/designers billing $2k+ projects. They're overbuilt and overpriced for an illustrator doing 10-20 commissions/month at $50-200 each. No one has built a lightweight, art-commission-specific flow with deposit splits, revision counters, and a client-facing status page.

## MVP Scope
- Public commission request form (embeddable on any site): style, size, deadline, reference images
- Auto-quote with deposit requirement (e.g., 50% upfront via Stripe)
- Kanban pipeline: Inquiry > Deposit Paid > In Progress > Revision > Final Approval > Delivered
- Built-in revision counter with configurable limit (e.g., "2 revisions included, $15/extra")
- Client status page: client sees current stage, uploads references, approves final

## Tech Stack
Next.js + Supabase + Stripe (for deposits/payments) on Vercel free tier.

## Revenue Model
Free for up to 5 active commissions. $7/mo for unlimited commissions. Optional 1% payment processing surcharge on transactions handled through the platform.

## Difficulty
Easy

## Status
Idea
