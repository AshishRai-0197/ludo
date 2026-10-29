# Ludo Tournament

A frontend prototype for a Ludo tournament setup flow, built with Next.js, React, and TypeScript.

## Current prototype

- Tournament name entry with an empty-name check
- Client-side tournament code generation
- Player name input
- Lobby layout with 16 placeholder player slots

This is a UI prototype. Tournament names and players are not persisted across pages, the lobby uses placeholder data, and the Start Tournament button is currently disabled. Multiplayer synchronization, playable Ludo, and a tournament backend are not implemented.

## Routes

| Route | Screen |
| --- | --- |
| `/` | Tournament name entry |
| `/second_page` | Code generation and player entry |
| `/third_page` | Tournament lobby preview |

## Technology

Next.js · React · TypeScript · Tailwind CSS · ESLint

## Run locally

```bash
git clone https://github.com/AshishRai-0197/ludo.git
cd ludo
npm ci
npm run dev
```

Open [localhost:3000](http://localhost:3000).

## Available commands

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm start` | Serve the production build |
| `npm run lint` | Run ESLint |
