# Idea 010: PlotKeeper — Community Garden & Shared Space Manager

## One-liner
A management tool for community gardens, shared workshops, and co-op spaces: plot/bench assignments, waitlists, fee collection, and member communication — replacing the volunteer coordinator's spreadsheet nightmare.

## Problem
Community gardens in the US have exploded (estimated 29,000+), each managed by volunteer coordinators who track plot assignments, waitlists, annual fees, rule compliance, and member communication through a mess of spreadsheets, paper sign-up sheets, and Facebook groups. When a plot becomes available, the coordinator has to check a waitlist that may be in three different places. Fee collection is via check or cash with no tracking. The one existing tool (Community Garden App from Vancouver) is limited and not widely adopted.

## Why now / why not built yet
Community gardens are managed by volunteers, not businesses — so no one builds software for them because the buyer has no budget. But many gardens charge $25-75/year per plot, and the coordinator role burns people out due to admin overhead. A tool that costs less than one plot fee and saves 5+ hours/month of admin is an easy sell to garden boards. The same tool works for shared workshop spaces (makerspaces), co-op tool libraries, and allotment gardens in the UK/ME.

## MVP Scope
- Garden setup: define plots/benches on a visual grid map
- Member directory with plot assignments and lease dates
- Waitlist management: auto-notify next person when a plot opens
- Annual fee collection via Stripe with payment status dashboard
- Announcements and rule reminders via email/SMS

## Tech Stack
Next.js + Supabase + Stripe on Vercel free tier. Resend for email notifications.

## Revenue Model
Free for gardens under 20 plots. $6/mo for 21-100 plots. $12/mo for 100+ plots. Annual billing at $49/year and $99/year respectively.

## Difficulty
Easy

## Status
Idea
