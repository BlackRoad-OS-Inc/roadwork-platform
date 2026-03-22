# RoadWork

AI tutoring platform with adaptive learning and spaced repetition. Free for K-12 students.

## What It Does

RoadWork adapts to each student. It uses FSRS (Free Spaced Repetition Scheduler) to time reviews for maximum retention, accepts answers via photo, voice, or text, and adjusts difficulty based on performance.

## Features

- **Adaptive difficulty** — problems adjust based on your answers
- **FSRS spaced repetition** — scientifically-timed review intervals
- **Multi-modal input** — type, photograph your work, or speak your answer
- **Progress tracking** — see what you know and what needs review
- **Free for K-12** — no paywall for students

## How It Works

1. Student picks a subject and starts a session
2. RoadWork presents problems at the right difficulty level
3. Student answers via text, photo upload, or voice
4. AI evaluates the response and explains any mistakes
5. FSRS schedules the next review at the optimal interval

The system tracks what each student struggles with and reinforces those areas without wasting time on mastered material.

## Stack

- **Runtime**: Cloudflare Worker
- **Database**: D1 (student progress, question bank, review schedule)
- **AI**: Answer evaluation and step-by-step explanations
- **Algorithm**: FSRS v4 for spaced repetition scheduling
- **Input**: Text, image upload, voice transcription

## Deploy

```bash
npm install
npm run dev        # Local dev server
npm run deploy     # Deploy to production
```

## Subjects

Math, science, reading, and writing for K-12. Question banks are extensible — add your own content following the schema in the worker source.

## Why Free for K-12

Chegg charges $20/month. CourseHero charges $10/month. Students already have enough expenses. RoadWork is free for K-12 because tutoring should not be gated by income.

## License

Proprietary. Copyright (c) 2024-2026 BlackRoad OS, Inc. All rights reserved.

---

*Remember the Road. Pave Tomorrow.*
