# Rishab — Nepal Full-Stack Website

A simple full-stack Next.js website showing:

- Name: Rishab
- Country: Nepal
- Live current time in Nepal
- Nepal-themed mountain background
- Backend API at `/api/profile`

## Run locally

Install Node.js 18+.

```bash
npm install
npm run dev
```

Then open:

http://localhost:3000

Backend endpoint:

http://localhost:3000/api/profile

## Project structure

- `app/page.tsx` — frontend
- `app/globals.css` — Nepal-themed design
- `app/api/profile/route.ts` — backend API
- `app/layout.tsx` — site metadata/layout
