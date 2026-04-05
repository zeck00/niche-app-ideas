# Idea 042: Small Farm Harvest Log

## One-liner
A simple crop-by-crop harvest tracking app for small diversified farms that logs yields, calculates per-bed/per-row profitability, and shows what's actually worth growing next season.

## Problem
Small market farms (1-10 acres) grow 20-50 different crops. They know their total revenue but rarely know which specific crops are profitable vs. which are labor sinks. Existing farm management software (Tend, Heirloom) focuses on crop planning and planting schedules but is weak on the post-harvest analysis: "I planted 3 beds of kale and 2 beds of arugula — which one actually made money after labor?" Most small farmers track harvest weights on paper tally sheets or not at all, losing the data that would improve next season's planning.

## Why now / why not built yet
Farm planning tools help you decide WHAT to plant. But nobody serves the feedback loop: tracking what you actually harvested, what it sold for, and whether it was worth the bed space. This is a gap between "crop planning" apps and "farm accounting" apps that neither category fills well. Small diversified farms are a growing segment (local food movement, CSAs) but are too small for enterprise ag-tech.

## MVP Scope
- Define fields/beds/rows and assign crops
- Quick harvest entry: crop, quantity (weight or count), date, destination (market, CSA, wholesale)
- Revenue tracking per crop per bed (link to sales or enter manually)
- Season summary: revenue per bed-foot, yield per bed-foot, comparison across crops
- "Grow Again?" score combining yield, revenue, and effort rating

## Tech Stack
Next.js + Supabase. PWA for field use (offline harvest entry, sync later). Vercel hosting.

## Revenue Model
Free for 1 season of data. $6/mo or $29/year for multi-season history, comparisons, and CSV export.

## Difficulty
Easy

## Status
Idea
