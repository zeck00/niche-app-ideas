# Idea 037: UAE Freelancer Corporate Tax Prep Tool

## One-liner
A simplified corporate tax preparation tool for UAE freelancers and sole proprietors who now must file annual returns under the 2023 corporate tax law, turning confusing FTA requirements into a guided checklist.

## Problem
Since June 2023, the UAE introduced a 9% corporate tax on income above AED 375,000. Freelancers on green visas and freezone sole proprietors are caught in this net but have zero guidance. A graphic designer earning AED 500,000/year from a Dubai freezone permit now needs to: register with the FTA, determine their tax period, track deductible expenses, calculate taxable income, and file an annual return. The FTA portal is functional but assumes accounting knowledge. Freelancers do not have accountants — they previously had zero tax obligations and zero bookkeeping habits. Tools like Wafeq and Zoho Books UAE are full accounting platforms that overwhelm a solo freelancer who just needs to answer: "How much tax do I owe and what can I deduct?" The AED 375,000 threshold means even mid-tier freelancers are affected.

## Why now / why not built yet
The first corporate tax filing deadlines hit in 2025 for many freelancers, and confusion is rampant. The UAE has 70,000+ active freelancer permits. Most have never filed any tax return anywhere. Accounting firms charge AED 3,000-10,000 for corporate tax filing — disproportionate for a freelancer earning AED 400K. No one has built a lightweight, freelancer-specific tool because the UAE tax ecosystem is brand new (3 years old), the freelancer segment is underserved by accounting firms, and SaaS builders have focused on SME accounting, not solo-freelancer tax prep.

## MVP Scope
- Guided onboarding: "Are you a freelancer? Freezone or mainland? Estimated annual income?" to determine obligations
- Income and expense tracker with UAE-specific deductible categories
- Corporate tax calculator: taxable income, applicable rate, estimated tax liability
- FTA filing checklist: step-by-step guide with screenshots of what to do on the FTA portal
- Document vault: store trade license, FTA registration, bank statements for 5-year retention requirement

## Tech Stack
Next.js + Supabase (auth + DB + storage) on Vercel. No external APIs needed.

## Revenue Model
Freemium: tax calculator and obligation checker free. AED 39/mo (~$11) for expense tracking and filing preparation. AED 199 one-time for guided filing walkthrough package.

## Difficulty
Easy

## Status
Idea
