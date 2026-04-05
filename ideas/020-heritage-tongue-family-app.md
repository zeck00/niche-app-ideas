# Idea 020: TongueTie — Heritage Language Practice Tracker for Diaspora Families

## One-liner
A family-oriented tracker that helps diaspora parents maintain their children's heritage language by setting daily practice goals, logging activities (reading, speaking, media), and celebrating streaks — without being yet another language learning app.

## Problem
Diaspora families (Arab, South Asian, African, East Asian communities abroad) want their children to maintain the heritage language, but there's no tool to coordinate and track the effort. Parents set informal rules ("speak Urdu at dinner") that erode over time. By the third generation, heritage languages are typically lost. Tandem and HelloTalk are for adults learning foreign languages, not for a family trying to keep Yoruba alive at home. The existing apps that touch this space (Bibala for African languages, BhashaKids for South Asian) are content-focused — they teach vocabulary. What's missing is the habit and accountability layer: did we actually speak Arabic today? Did the kids watch their Somali cartoon? How many days this month did we maintain the family language policy?

## Why now / why not built yet
Research confirms digital tools can help heritage language maintenance, but app developers build language-learning products (Duolingo model) not language-maintenance products. The distinction matters: heritage speakers already understand the language passively — they need active practice, not lessons. The audience is massive (46M+ heritage language speakers in the US) but fragmented by language, making it hard for any single content-focused app to serve everyone. A language-agnostic tracking tool sidesteps this problem.

## MVP Scope
- Family setup: parents + children profiles, select heritage language(s)
- Daily practice log: quick-tap what you did today (spoke at dinner, read a book, watched a show, called grandparents)
- Family streak tracker: how many consecutive days the family maintained the language policy
- Weekly goals: set targets (e.g., "3 days of Tagalog dinner conversation, 2 heritage media sessions")
- Celebration milestones: badges for streaks, shareable "family language report card"

## Tech Stack
Next.js PWA + Supabase on Vercel free tier. Family sharing via invite links (no app store needed).

## Revenue Model
Free for 1 language + 1 child. $3.99/mo for multiple children + multiple languages + extended streak history + printable progress certificates. $29/year family plan.

## Difficulty
Easy

## Status
Idea
