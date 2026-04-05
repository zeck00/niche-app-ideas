# Idea 013: ScrimOps — Amateur Esports Practice Manager

## One-liner
A lightweight team practice organizer for amateur esports squads that replaces the chaos of Discord DMs and spreadsheets with structured scrim scheduling, attendance tracking, and VOD review notes.

## Problem
Amateur and semi-pro esports teams (Valorant, League of Legends, CS2, Overwatch) coordinate practices entirely through Discord messages and Google Sheets. Team managers post "who's available Thursday?" and get inconsistent replies. Scrims get double-booked, players no-show with no record, and post-match VOD review notes live in random Discord channels nobody searches. The #1 reason amateur teams disband isn't lack of talent — it's organizational collapse. Tools like Toornament and Battlefy focus on tournaments, not the day-to-day grind of team practice.

## Why now / why not built yet
Existing esports tools target tournament organizers (Toornament, Challonge) or large orgs with paid coaches (Mobalytics, Coachify.gg). The 5-person Valorant team with a volunteer IGL who just wants to schedule scrims, track who showed up, and log what they learned — nobody builds for them. Discord bots like ScrimFinder help find opponents but don't manage the practice workflow. The market treats amateur teams as future customers of pro tools instead of building for their current reality.

## MVP Scope
- Team roster with role tags (IGL, support, flex) and availability calendar
- Scrim scheduling: propose time, collect RSVPs, auto-match with opponent teams in the pool
- Attendance log with streak tracking (gamified — show who's been consistent)
- Post-scrim notes: structured fields for what worked, what to fix, linked to replay timestamps
- Practice plan templates (warm-up drill, scrim block, VOD review block)

## Tech Stack
Next.js + Supabase (auth + DB) on Vercel free tier. Discord OAuth for login. Optional Discord webhook for notifications.

## Revenue Model
Free for 1 team up to 7 players. $5/mo for unlimited roster + opponent pool access + practice analytics. $12/mo "org tier" for managing multiple teams under one org.

## Difficulty
Easy

## Status
Idea
