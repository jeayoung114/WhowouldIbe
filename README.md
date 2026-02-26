# 🎬 WhoWouldIBe

**Which movie character are you?**

Pick any movie or drama, answer a few personality questions, and AI will tell you which character you'd be — with a match percentage and shareable result card.

## Features

- 🔍 **Search** — Find any movie or drama with posters and details (TMDB)
- 🧠 **Quiz** — Answer AI-generated questions themed to your movie
- 🎯 **Match** — Get paired with a character based on personality analysis
- 📤 **Share** — Download and share your result card

## Demo

Open [`demo.html`](demo.html) in your browser, or run the [`WhoWouldIBe_Demo.jsx`](WhoWouldIBe_Demo.jsx) component in React.

## Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | React, Next.js, TypeScript |
| AI | Claude API |
| Movie Data | TMDB API |
| Database | Supabase (PostgreSQL) |

## Getting Started

```bash
npm install
cp .env.example .env.local   # add TMDB_API_KEY & ANTHROPIC_API_KEY
npm run dev
```

## License

[Apache 2.0](LICENSE)
