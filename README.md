# thetas.ai

**AI knows what to teach. We tell it who it's teaching.**

[thetas.ai](https://thetas.ai) · [thetasai.com](https://thetasai.com) · [thetas.ai/developers](https://thetas.ai/developers)

thetas.ai is a private learning feed for students and a lesson recorder for tutors, built on a per-student learning brain that records what each student has shown they can do from their own marked work and their tutor's lessons. I co-founded Thetas and build the product end to end. The source is private; this repo is a public showcase.

> **[The whole company system (student app, tutor side, learning brain and MCP server, admin portal, Studio and internal tools) is on the ThetasAI organisation page](https://github.com/ThetasAI)**

<p>
  <img src="images/student-home-theta.webp" alt="Student Home with Theta open beside it" width="49%">
  <img src="images/student-feed.webp" alt="The Feed: a practice question picked from a weak spot" width="49%">
</p>
<p>
  <img src="images/tutor-lesson-review.webp" alt="A recorded lesson drafted into notes, waiting for the tutor's approval" width="49%">
  <img src="images/learning-brain.webp" alt="What the learning brain knows about a student" width="49%">
</p>

## What it does

- **Students**: one question at a time, picked from weak spots, set work and ideas that are starting to fade; a study plan toward the exam date; and Theta, an assistant that knows their plan and progress.
- **Tutors**: record a lesson and Thetas drafts the notes, per-student profile updates and follow-up practice. The tutor approves each part before anything reaches a student.
- **Any AI**: Claude, ChatGPT, Gemini, Cursor and other MCP clients can read the learning brain over MCP, with tokens the student or tutor controls.

## Built with

- Next.js 15, React 19, TypeScript, Tailwind
- Python, FastAPI, PostgreSQL with pgvector
- Gemini and Claude
- MCP

## Status

Closed beta, IB Maths, Hong Kong. Screenshots use demo accounts only.
