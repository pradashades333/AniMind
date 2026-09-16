# AniMind

Full-stack app for character/scene data with an Express backend, Prisma database layer, and client/server project split.

## Stack

- TypeScript / JavaScript
- Express
- Prisma
- PostgreSQL
- Passport auth

## Live

- Demo link: add deployed URL when the app is public.

## Screenshot

Screenshot path: add a UI capture at `docs/screenshot.png`.

## What it does

- Handles account/session auth with Passport.
- Stores app data through Prisma.
- Keeps frontend and backend code separated for deployment.

## Run locally

```powershell
cd server
npm install
npx prisma generate
npm run dev
```

Set `DATABASE_URL` in `server/.env` before starting the API.
