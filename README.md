# Thetas.ai — AI Revision Platform

🌐 **Live:** [thetas.ai](https://thetas.ai)
🏢 **Parent brand:** [thetasai.com](https://thetasai.com)

> Upload your curriculum. Get a personalised feed of practice questions, flashcards, and AI-generated study notes.

This repo is a public showcase. The application source is private.

---

## What it does

Thetas.ai is an AI-powered revision tool built for secondary school students preparing for international curricula. Students upload syllabus materials, and the platform generates adaptive practice content tuned to their weak topics.

## Key features

- **Curriculum templates** — pre-built support for IB, IGCSE, and HKDSE
- **Adaptive practice modes** — Weakness (target gaps), Revision (consolidate strengths), Explore (broaden coverage)
- **Chapter tests with AI grading** — multi-factor scoring on free-response answers, not just multiple choice
- **AI study notes & flashcards** — generated from uploaded materials, editable by the student
- **Credit-based pricing** — Free tier (50 credits) and Pro ($9.99 / 2,000 credits)
- **Currently in trial** with Hong Kong secondary IB Math students

## Architecture (high level)

| Layer | Stack |
|-------|-------|
| Frontend | React, TypeScript |
| Backend | Spring Boot microservices |
| AI orchestration | Spring AI (provider-agnostic LLM routing) |
| Data | PostgreSQL, MongoDB, Redis |
| Infrastructure | AWS, Docker, CI/CD |

Everything from domain acquisition to production deployment was built solo.

## Status

Live and functional, in active trial with real users. Active development.

---

Built and operated by [Toby Lee](https://github.com/llhtoby38).
