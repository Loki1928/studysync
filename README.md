StudySync

One board, two people. A real-time study accountability app for any pair of study partners — plan your day, tick tasks off, and watch each other stay on track.

Whether it's UPSC and CA, NEET and JEE, GATE and CAT, board exams, language learning, or any goal you're grinding toward — StudySync keeps both of you honest, side by side.

🔗 Live app: https://loki1928.github.io/studysync/

Why this exists

Studying alone is hard. Promises like "I'll finish this chapter today" are easy to break when nobody's watching. StudySync puts your day and your partner's day on the same screen — no chasing each other on WhatsApp for updates, no lying to yourself about how the week went. The numbers are right there, for both of you.

Features
🔑 Private rooms — one person creates a room and gets a 6-character code; the other joins with it. Built for exactly two people.
✅ Daily task board — add today's tasks, tick them off, and your completion percentage updates live.
👀 Side-by-side progress — your partner's tasks and percentage sit right next to yours, syncing in real time. A tick on their phone shows up on your screen within a second.
📊 Auto-calculated analytics — paired bar charts for the last 7 days, monthly averages, and total tasks done. No manual tracking, ever.
🔥 Streaks — consecutive days with at least one completed task. Don't break the chain.
⏳ Exam countdowns — add any exam or deadline and watch the days-left counter. Both partners can track different exams on the same board.
📝 Test & mock tracker — schedule tests in advance; when the day arrives, mark Gave it ✓ or Missed so your partner knows.
📱 Works everywhere — phone, tablet, laptop. It's just a link. Each device remembers you, so you open it and you're in.
How it works
Open the app → Create a room → enter your name and what you're preparing for → get a room code.
Send your partner the link and the code.
They hit Join with a code — done. You're now on the same board, forever in sync.
Tech
Single-file app — one index.html, zero build steps, zero frameworks. Vanilla JS + CSS.
Firebase Realtime Database (free tier) for storage and live sync.
GitHub Pages for hosting — free, permanent link.

Data never lives in this repo. Everything is stored in your own Firebase project, so redeploying the app never touches your progress.

Run your own copy
Fork or download this repo.
Follow SETUP.md — create a free Firebase project, paste your config into index.html, enable GitHub Pages. Takes ~10 minutes, no credit card.
Privacy note

A room is protected by its code — anyone with the code (and your database URL) could view the room. It's designed for personal use between two people who trust each other. Don't post your room code publicly.

Roadmap ideas
Subject-wise task breakdown
Scores/notes on completed tests
Motivational nudges when your partner finishes their day
Weekly summary comparisons

Suggestions and PRs welcome.
