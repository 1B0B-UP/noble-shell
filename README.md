# Noble Shell

Engineering study platform with spaced-repetition flashcards, AI quizzes, and exam prep.

## Features

- **Flashcards** — FSRS spaced-repetition algorithm with 20 predefined engineering topics (PID control, Kubernetes, hydraulic systems, and more)
- **AI quizzes** — generated quiz questions per topic with scoring
- **Topic summaries** — AI-generated summaries for each subject
- **Feed** — curated YouTube and Wikipedia content per topic
- **FE/PE prep** — exam-focused study mode for Fundamentals of Engineering and Professional Engineer exams
- **Math refresh** — built-in math review section
- **Focus sessions** — timed study blocks
- **Progress tracking** — streak, XP, weekly activity chart, weak area detection
- **Study habits** — habit tracking cards

## Stack

- Next.js, React, Tailwind v4
- SQLite (via node:sqlite)
- Ollama for AI features (default model: `llama3.2:3b`)
- Recharts

## Run locally

Requires [Ollama](https://ollama.com) running locally for AI features.

```bash
npm install
npm run dev
```

Runs on [http://localhost:4001](http://localhost:4001).
