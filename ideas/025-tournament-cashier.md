# Idea 025: TournCash — Community Tournament Entry Fee & Prize Pool Manager

## One-liner
A simple entry fee collection and prize pool distribution tool for community gaming tournaments, local poker nights, and amateur sports brackets where Venmo requests and cash envelopes are the current "system."

## Problem
Community tournament organizers — the person running a weekly Smash Bros bracket at a game store, a local poker league, a FIFA tournament at a college dorm, or a rec-center ping pong tournament — collect entry fees ($5-50) via a mix of cash, Venmo, and CashApp, then distribute prizes manually. They lose track of who paid, miscalculate prize splits, and have no record for disputes. Matcherino exists for esports crowdfunding but targets large events. Challonge handles brackets but not money. The tournament organizer at a local game store running a 16-person bracket with a $10 buy-in needs to collect $160, deduct $20 for the venue, and split $140 between 1st/2nd/3rd — and currently does this on paper.

## Why now / why not built yet
Tournament bracket tools (Challonge, Battlefy, Start.gg) focus on competitive structure, not financial logistics. Payment tools (Venmo, CashApp) handle transfers but not tournament-specific accounting. The intersection — "who entered, who paid, what's the pot, how do we split it" — falls in a gap. The market is hyperlocal and low-value per transaction, making it invisible to fintech companies. But there are millions of informal tournaments happening weekly across gaming stores, bars, campuses, and community centers.

## MVP Scope
- Tournament setup: name, entry fee, max players, prize split percentages (e.g., 60/30/10)
- Player registration: shareable link, players enter name and mark payment method (cash/Venmo/other)
- Payment tracker: organizer checks off who's paid — shows real-time pool total
- Prize calculator: auto-splits pool after optional venue/organizer cut, shows exact payout per placement
- Settlement receipt: one-page summary showing all entries, deductions, and payouts — screenshot-friendly

## Tech Stack
Next.js + Supabase on Vercel free tier. No payment processing needed (tracks payments, doesn't process them). PDF/image export for receipts.

## Revenue Model
Free for tournaments up to 16 players. $3.99/mo for unlimited tournament size + recurring tournament templates + season tracking + leaderboards. $29/year annual plan.

## Difficulty
Easy

## Status
Idea
