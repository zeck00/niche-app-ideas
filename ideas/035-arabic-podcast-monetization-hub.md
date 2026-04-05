# Idea 035: Arabic Podcast Sponsorship & Monetization Hub

## One-liner
A sponsorship matchmaking and ad-read management tool for Arabic podcasters, solving the monetization gap in the MENA podcast market where creators cannot find or manage brand deals.

## Problem
Arabic podcasting is growing fast — Podeo claims 50M+ listeners and 95% MENA market share for distribution. But monetization is broken. Unlike the English podcast world (which has Podcorn, Gumball, PartnerStack), there is no standardized way for Arabic podcasters to find sponsors, price ad reads, or manage brand deal pipelines. Brands in the GCC want to sponsor Arabic podcasts (podcast ad spend in MENA is growing 30%+ yearly) but have no discovery mechanism beyond personal connections. Podcasters with 5,000-50,000 listeners per episode have no idea what to charge, no rate card, and no way to prove their audience demographics to potential sponsors. The result: massive demand on both sides, zero infrastructure in between.

## Why now / why not built yet
The MENA podcast market is projected to grow significantly through 2030. Arabic podcast listenership has tripled since 2021. Saudi Arabia and UAE brands are actively shifting marketing budgets to audio. Yet the monetization infrastructure that exists in English (IAB standards, dynamic ad insertion, programmatic audio) is completely absent for Arabic. Nobody has built this because Western podcast ad platforms do not support Arabic content, and MENA-focused players (Podeo) focus on distribution, not creator monetization tooling.

## MVP Scope
- Podcaster profile: show name, episode frequency, listener stats, audience demographics, language/dialect
- Rate card generator: suggest CPM pricing based on audience size and niche
- Brand directory: GCC brands interested in podcast sponsorship, with contact info and budget ranges
- Deal pipeline tracker: outreach, negotiation, contract, recording, payment stages
- Ad-read brief templates: standardized format for sponsor requirements

## Tech Stack
Next.js + Supabase (auth + DB) on Vercel. No external APIs for MVP.

## Revenue Model
Free for podcasters. Brands pay AED 199/mo (~$54) to list and discover podcasters. 10% commission on deals facilitated through the platform (optional, for managed deals).

## Difficulty
Medium

## Status
Idea
