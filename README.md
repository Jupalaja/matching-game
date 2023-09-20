# Matching Game

## Project Description

This is the repository for a Matching Game where a player is required to match pairs of cards with similar flags. The game is written in TypeScript and Svelte using SvelteKit as the application framework.

## Project Structure

```
.
├── package.json
├── src
│   ├── app.css
│   ├── app.d.ts
│   ├── app.html
│   └── routes
│       ├── +layout.svelte
│       ├── +page.svelte
│       └── flags.ts
├── static
├── svelte.config.js
├── tsconfig.json
└── vite.config.ts
```

## Main Files

**+layout.svelte** - Contains the main layout of our Svelte application.  
**+page.svelte** - This is where the logic for the game resides. It includes game states, timer, grid creation, card selection, winning/losing conditions, etc.  
**flags.ts** - Contains the representation of flags used in the game.  
**app.css** - Contains the main CSS styles for our Svelte application.

## How to Run the Project

You need to have Node.js and npm installed on your machine before running the following commands.

1. Clone the repo locally:

```bash
git clone https://github.com/<your-github-username>/matching-game.git
cd matching-game
```

2. Install dependencies:

```bash
npm install
```

3. Run the game:

```bash
npm run dev
```

4. Open a web browser and visit `http://localhost:5173` — you should see the game!

## Game Rules

- Players need to match pairs of cards with the same flag.
- Players win when all pairs of cards have been matched within the timeframe.
- Players can Pause the game by hitting the key [ESC].
