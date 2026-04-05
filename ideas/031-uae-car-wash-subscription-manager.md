# Idea 031: UAE Car Wash Subscription & Booking Manager

## One-liner
A lightweight booking and subscription management tool for independent car wash operators in the UAE, with WhatsApp booking confirmations and route optimization for mobile units.

## Problem
The UAE car wash market is dominated by two models: fixed-location washes and mobile door-to-door services. Mobile car wash operators (hundreds in Dubai alone) manage bookings via WhatsApp messages, track subscriptions in notebooks, and route their daily stops manually. A typical operator handles 20-40 subscription customers (monthly packages of 4-8 washes at AED 150-400/mo) plus on-demand bookings. They have no system to track which subscription customer is due for their next wash, which payments are overdue, or how to route their day efficiently. Apps like Keno and ScrubUp serve consumers but do not provide operator-side tools. Fixed-location washes face similar issues — walk-in tracking, loyalty programs, and upsell tracking are all manual.

## Why now / why not built yet
UAE vehicle ownership is among the highest globally, and the extreme heat/dust means cars need frequent washing. The mobile car wash segment has exploded because building owners now restrict water usage, pushing demand to professional services. Most operators are solo entrepreneurs or 2-3 person teams — they cannot afford or operate complex POS systems. No tool exists at their price point that handles the subscription + booking + routing combo specific to the UAE car wash model (where a single operator might cover Dubai Marina, JLT, and Business Bay in one day).

## MVP Scope
- Customer database with vehicle details, location, gate/parking codes
- Subscription tracker: package type, washes remaining, renewal date, payment status
- Daily route planner: drag-and-drop stop ordering with map view
- WhatsApp message templates: booking confirmations, "on my way" alerts, payment reminders
- Simple payment logging (cash, bank transfer, card — no payment processing)

## Tech Stack
Next.js + Supabase (auth + DB) on Vercel. WhatsApp Business API (free tier) for messaging. Leaflet/OpenStreetMap for route visualization.

## Revenue Model
Freemium: 15 customers free, AED 29/mo (~$8) for unlimited customers. AED 59/mo with route optimization and WhatsApp integration.

## Difficulty
Easy

## Status
Idea
