# Prêt-à-Parler

A French language learning app built for one user — my dad — who was working toward C1 proficiency and frustrated with every app that kept things surface-level.

Most language apps are built around recall: flashcards, scripted phrases, predictable topics. That's fine for beginners, but my dad didn't need basic. He needed something that pushed him into real conversation — the kind where you actually have to think on your feet, not just retrieve a memorized response. So I built it for him.

---

## What it does

The app combines real-time pitch detection and pronunciation feedback with YouTube transcript integration, so practice is grounded in real French content rather than textbook scenarios. Conversations are powered by Claude API, which means each session goes somewhere different — that was intentional, and it turned out to be the thing he loved most about it. His words: it felt like talking to a smart French person, not completing a lesson.

Under the hood: Whisper handles speech transcription, HuggingFace Transformers runs client-side ML, WaveSurfer.js visualizes audio in real time, and Turso (LibSQL) tracks progress and adapts lessons over time. The backend runs on Netlify Functions.

It started as a one-user app. He quietly opened it to his French class for broader feedback, which became an unplanned but very real validation loop.

---

## Stack

`TypeScript` · `React` · `Claude API` · `Whisper` · `HuggingFace Transformers` · `WaveSurfer.js` · `YouTube Transcript API` · `Turso (LibSQL)` · `Netlify Functions`

---

## Status

Private repo. Built for a real user, tested with a few more.
