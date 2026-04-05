# Idea 041: Livestock Treatment Logger

## One-liner
A mobile-first vaccination, deworming, and medication log for small livestock farmers that tracks withdrawal periods and generates compliance-ready health records per animal.

## Problem
Small ranchers and hobby farmers (10-100 head of cattle, goats, sheep, or pigs) track vaccinations, dewormers, and antibiotics on paper notebooks or memory. When selling animals, they need health treatment records for buyers, auctions, and USDA compliance. Withdrawal periods (the mandatory wait time after medication before an animal can be slaughtered or milked) are critical — mistakes can mean condemned carcasses and fines. Existing livestock software (CattleMax, HerdWatch) costs $15-$30/mo and includes breeding/genetics/financial features most small operators don't need.

## Why now / why not built yet
Livestock management apps are built for commercial operations with hundreds of head. A small-holder with 30 goats or 50 cattle just needs: "what did I give this animal, when, and when is it safe to sell?" The medication-withdrawal-period angle is the key unserved pain — no free/cheap tool focuses specifically on treatment compliance.

## MVP Scope
- Animal registry: tag number, species, breed, photo, birth date
- Log treatment: medication name, dosage, route, date, withdrawal period (auto-populated from common drug database)
- Withdrawal countdown timer per animal with "clear to sell" status
- Printable/PDF health record per animal for sale, auction, or vet
- Reminders for upcoming boosters and scheduled treatments

## Tech Stack
Next.js + Supabase. Works offline as PWA (critical for rural areas with poor connectivity, syncs when online). Vercel hosting.

## Revenue Model
Free for up to 20 animals. $8/mo for unlimited animals + PDF export + multi-farm support. $29 one-time lifetime.

## Difficulty
Easy

## Status
Idea
