# Idea 047: Senior Downsizing Inventory

## One-liner
A simple photo-based inventory app for seniors (or their adult children) preparing to downsize, helping them catalog belongings, decide keep/sell/donate/discard, and share decisions with family.

## Problem
When seniors downsize from a home to a smaller space or assisted living, they face an overwhelming task: sorting through decades of belongings. Professional senior move managers charge $50-$150/hour. Families argue over who gets what. The current process is walking through rooms with sticky notes and a notepad. No tool exists to photograph items, tag them with decisions (keep/sell/donate/toss), assign items to family members, and share the plan. Generic inventory apps (Sortly, Home Inventory) aren't designed for the emotional, family-collaborative, decision-heavy downsizing workflow.

## Why now / why not built yet
10,000 Baby Boomers turn 65 every day in the US. Downsizing is a $2B+ industry (senior move managers, estate sales, junk removal). But the planning and decision-making step — before the movers arrive — has no dedicated digital tool. It's too emotionally specific for generic inventory apps, and tech startups don't build for 70-year-olds.

## MVP Scope
- Room-by-room photo inventory: snap a photo, add item name and optional value estimate
- Decision tags: Keep (+ where it goes), Give to [family member], Sell, Donate, Discard
- Family sharing: invite children/family to view inventory and claim items
- Summary dashboard: counts and estimated values by category (keep/sell/donate)
- Printable checklist for movers, estate sale, and donation pickup

## Tech Stack
Next.js + Supabase (auth + DB + storage). Extra-large UI elements and high contrast for senior usability. Vercel hosting. PWA.

## Revenue Model
Free for 1 room (up to 30 items). $9/mo or $29 one-time for unlimited rooms + family sharing + PDF export.

## Difficulty
Easy

## Status
Idea
