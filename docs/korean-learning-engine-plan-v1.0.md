# Context-First Korean Learning Engine

Working name: `hanflow`

## Goal

Build a full-stack app that helps me learn Korean through real life, personal context — not a generic flashcard app.

- Capture my real thoughts and daily situations
- Transform them into natural Korean sentences
- Train speaking + listening + recall using repetition and feedback

## Core Learning Loop

1. Capture raw text or voice from my life
2. Correct and translate to natural Korean
3. Save as sentence cards with context tags
4. Practice with spaced repetition
5. Listen with TTS and repeat out loud
6. Record speech, transcribe, and compare
7. Track progress and weak points

## MVP Scope

- Auth and user data isolation
- Sentence capture and storage
- Translation + correction pipeline
- Sentence card generation
- Daily review queue (SRS)
- Basic TTS playback
- Speech attempt logging
- Dashboard (streak, due cards, retention trend)

## Tech Stack

- Next.js (App Router), TypeScript
- Supabase (Postgres + Auth + Storage)
- DeepL for translation
- Google Cloud TTS/STT
- Deployed on Vercel + Supabase
