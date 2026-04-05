# Idea 006: ShieldDoc — One-Click NDA & Freelance Contract Generator

## One-liner
Generate jurisdiction-aware NDAs, freelance service agreements, and IP assignment docs in 60 seconds — built for solopreneurs and freelancers who can't afford a lawyer for every new client.

## Problem
Every freelancer, consultant, and small agency needs NDAs and basic contracts, but they either use sketchy free templates (that may not be enforceable in their state/country), pay $200+ per contract from a lawyer, or skip contracts entirely and get burned. Existing contract tools (PandaDoc, DocuSign) are full-featured document platforms priced at $19-49/mo — overkill for a freelancer who needs 2-3 contracts/month. The OneNDA standard exists but requires understanding legal language to customize. In the UAE, where freelance visas are booming, contracts must account for DIFC vs. onshore jurisdiction differences that no template covers.

## Why now / why not built yet
Free NDA generators exist (Ruul, Venngage) but produce generic, one-size-fits-all documents. None ask about jurisdiction, IP ownership specifics, or generate contracts localized for UAE/GCC free zones. The gap is between "free generic PDF" and "$200 lawyer review." A smart questionnaire that produces a properly localized, professional document fills that middle ground.

## MVP Scope
- Guided questionnaire: type of agreement, jurisdiction (US state / UAE free zone / UK / etc.), parties, key terms
- AI-assisted clause selection based on answers (not generation — selection from pre-vetted clauses)
- Generate professional PDF with e-signature fields
- Built-in e-signature (both parties sign in-browser)
- Document vault: store and retrieve all signed agreements

## Tech Stack
Next.js + Supabase on Vercel. PDF generation via @react-pdf/renderer. Clause library stored in database.

## Revenue Model
First 2 documents free. $4.99 per document, or $12/mo for unlimited documents. UAE/GCC localized templates as a premium add-on at $19/mo.

## Difficulty
Medium

## Status
Idea
