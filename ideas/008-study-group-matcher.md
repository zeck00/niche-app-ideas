# Idea 008: StudySync — Course-Based Study Group Finder & Coordinator

## One-liner
Matches college students in the same course into study groups based on schedule, campus location, and study style — then handles scheduling, shared notes, and accountability.

## Problem
80% of tutoring tools target K-12; college students are underserved. Students in large lecture classes (200-500 students) want study partners but have no way to find them. University-run study groups are limited to a few courses. Students post "anyone want to study for BIO 201?" on Reddit/Discord and get buried. Coordinating meeting times across 4-5 busy students is its own nightmare. Studies show collaborative learning improves retention and grades (91% report higher grades on platforms like Knack), but forming groups is the hard part.

## Why now / why not built yet
Existing platforms (Knack, StudyStream) focus on paid tutoring or co-working streams. Discord servers are noisy and unstructured. No lightweight tool specifically solves "find 3-4 people in my section of CHEM 201 who are free Tuesday evenings and prefer active recall over passive review." The matching + scheduling combination is the gap.

## MVP Scope
- Sign up with university email, select current courses
- Set preferences: study style (flashcards, practice problems, discussion), schedule availability, campus vs. remote
- Auto-match into groups of 3-5 within same course and compatible schedules
- Group chat + shared document space (links to Google Docs/Notion)
- Session scheduler with calendar sync and attendance tracking

## Tech Stack
Next.js + Supabase on Vercel. Google Calendar API for scheduling sync.

## Revenue Model
Free for students. $49/semester for university departments to sponsor (branded version, usage analytics). Premium student tier at $3/mo for cross-course groups, priority matching, and AI-generated study guides.

## Difficulty
Easy

## Status
Idea
