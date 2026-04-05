# Idea 027: UAE Clinic Inspection Prep Checklist

## One-liner
A DHA/DOH/MOHAP inspection readiness tool for small clinics and medical practices in the UAE, turning dense regulatory standards into actionable checklists with audit trails.

## Problem
Small UAE clinics (dental offices, physiotherapy practices, dermatology clinics) face periodic inspections from DHA (Dubai), DOH (Abu Dhabi), or MOHAP (federal). The standards documents run 100+ pages — covering everything from EMR audit trails to fire extinguisher placement to medication storage temperatures. Clinic owners (often the doctor themselves) prepare by frantically reviewing PDF documents the week before an inspection. There is no tool that breaks these standards into daily/weekly/monthly checklist items with photo evidence logging. A failed inspection means fines, license suspension, or forced closure. The DHA updated its Outpatient Facility Standards in January 2025, and most clinics do not even know what changed.

## Why now / why not built yet
The UAE has 4,000+ licensed healthcare facilities, with small clinics making up the majority. DHA released new standards in early 2025. The regulatory environment is tightening — DHA now checks EMR access logs and patient record audit trails. Enterprise compliance software (like Qualio or MasterControl) costs $500-2000/mo and is designed for hospitals, not a 3-doctor clinic. Nobody has built a lightweight, Arabic/English checklist tool specifically mapped to DHA/DOH/MOHAP standards.

## MVP Scope
- Pre-built checklists mapped to DHA outpatient facility standards (2025 edition)
- Daily/weekly/monthly task scheduling with reminders
- Photo evidence capture for physical compliance items (fire safety, storage, signage)
- Inspection history log with corrective action tracking
- Bilingual interface (Arabic/English)

## Tech Stack
Next.js + Supabase (auth + DB + storage for photos) on Vercel. PWA for mobile use during walk-throughs.

## Revenue Model
Freemium: basic checklist free, AED 79/mo (~$22) for full standard coverage, photo evidence, and audit trail export. AED 149/mo per additional branch.

## Difficulty
Medium

## Status
Idea
