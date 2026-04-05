# Idea 005: PickupPulse — Drop-in Sports & Pickup Game Organizer

## One-liner
A micro-app for organizing recurring pickup sports games: RSVP tracking, automatic team balancing, venue/court booking reminders, and sub requests when regulars can't make it.

## Problem
Millions of adults play weekly pickup basketball, soccer, volleyball, and tennis. Organization happens via group chats (WhatsApp, iMessage) that become unmanageable: "I'm in," "I'm out," "Can someone sub?", "Wait, do we have enough?", "Which court?". The organizer manually counts heads, begs for subs, and often shows up to find 7 people for a 10-person game. No one tracks skill levels for fair team splits. This is especially painful in expat-heavy cities like Dubai where player rosters constantly churn.

## Why now / why not built yet
League management software (TeamSnap, LeagueApps) is built for formal leagues with seasons, standings, and registrations. Pickup games are informal, recurring, and roster-fluid — a completely different use case. No tool specifically handles the "who's in this week?" problem for casual recurring games. Dubai's amateur sports scene (DAFL has 1500+ players, padel is exploding) runs almost entirely on WhatsApp groups.

## MVP Scope
- Create a recurring game: sport, day/time, venue, min/max players
- Share join link (no app download needed — PWA)
- Weekly RSVP: players confirm/decline by deadline
- Auto-waitlist and sub requests when someone drops out
- Simple team maker: random split or skill-based balancing (players self-rate)

## Tech Stack
Next.js PWA + Supabase on Vercel. Push notifications via web push API.

## Revenue Model
Free for 1 game group. $3/mo per additional group, or $5/mo for "organizer pro" (unlimited groups, recurring payment collection from players, attendance stats).

## Difficulty
Easy

## Status
Idea
