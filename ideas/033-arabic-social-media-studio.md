# Idea 033: Arabic-First Social Media Content Studio

## One-liner
A social media content planner and scheduler built natively for Arabic RTL text, with bilingual post previews, Arabic hashtag suggestions, and Gulf-region posting time optimization.

## Problem
Arabic content creators and social media managers across the GCC face a consistent frustration: every major social media scheduling tool (Buffer, Hootsuite, Later, Planable) was built for English left-to-right text. Arabic RTL support is an afterthought — text renders incorrectly in preview modes, mixed Arabic/English posts break formatting, and content calendars display Arabic text awkwardly. When a social media manager at a Dubai agency previews an Arabic Instagram carousel in Hootsuite, the text alignment is wrong, the line breaks are different from what will actually post, and hashtags in Arabic get mangled. Beyond rendering, none of these tools understand GCC-specific posting patterns (Thursday evening engagement peaks, Ramadan schedule shifts, Friday prayer time dead zones).

## Why now / why not built yet
The MENA region has 200M+ social media users with Arabic as the primary content language. The Arabic content creator economy is booming — Saudi and UAE brands are shifting budgets to local Arabic influencers. Yet every scheduling tool treats Arabic as a secondary language. The technical challenge of proper RTL rendering in content previews is real but solvable. Nobody has built this because the indie SaaS scene is overwhelmingly English-first, and enterprise Arabic tools (like Lucidya) focus on social listening, not content scheduling.

## MVP Scope
- Content calendar with native RTL rendering for Arabic text
- Post composer with accurate Arabic/English bilingual preview per platform (Instagram, X, TikTok)
- Arabic hashtag suggestions based on trending Gulf-region tags
- Optimal posting time recommendations for GCC time zones and cultural patterns
- Draft management with team approval workflow (agency use case)

## Tech Stack
Next.js + Supabase (auth + DB) on Vercel. Social media platform APIs for scheduling (Instagram Graph API, X API free tier).

## Revenue Model
Freemium: 3 social accounts and 10 scheduled posts/mo free. AED 69/mo (~$19) for unlimited posts and 10 accounts. AED 149/mo for agency plan with team and client management.

## Difficulty
Medium

## Status
Idea
