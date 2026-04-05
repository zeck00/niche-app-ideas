# Idea 046: Insurance Agent Commission Ledger

## One-liner
A commission tracking app for independent insurance agents that reconciles what carriers owe vs. what they actually paid, catching missed and short-paid commissions.

## Problem
Independent insurance agents earn commissions from 5-15+ carriers. Each carrier pays on different schedules (monthly, quarterly), at different rates (new business vs. renewal), with different statement formats (PDF, CSV, portal). Agents currently track expected commissions in spreadsheets and manually compare against carrier statements — a tedious, error-prone process. Missed commissions are common (carriers short-pay, forget renewals, or miscalculate) and agents who don't reconcile lose 3-8% of their income. Dedicated commission tracking software (Commission Tracker) starts at $67/mo — expensive for solo agents just starting out.

## Why now / why not built yet
Commission reconciliation is a known pain point discussed in every insurance agent forum. The existing solutions are built for agencies with 10+ agents and priced accordingly. Solo and small-agency independent agents (the majority of the market) are stuck with Excel. Nobody has built a $10/mo tool that just answers: "Am I getting paid everything I'm owed?"

## MVP Scope
- Log policies: carrier, client, policy type, premium, expected commission rate, effective date
- Track expected commissions: auto-calculate what each carrier should pay each period
- Log actual payments received per carrier
- Reconciliation dashboard: expected vs. received, flagging discrepancies
- Carrier scorecard: which carriers consistently pay on time vs. which are problems

## Tech Stack
Next.js + Supabase (auth + DB). Vercel hosting. CSV import for carrier statement data.

## Revenue Model
Free for up to 25 policies. $10/mo for unlimited + reconciliation alerts + annual tax summary export.

## Difficulty
Easy

## Status
Idea
