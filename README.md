# MuseVis — Frontend Demo

A responsive music discovery and visualizer demo built with HTML, CSS, and JavaScript, served locally with Vite.

## Requirements

- Node.js 18 or newer
- npm (included with Node.js)

## Run in VS Code or another IDE

1. Clone or download this repository.
2. Open the project folder in VS Code (or your preferred IDE).
3. Open the integrated terminal in the project folder.
4. Install dependencies:

   ```bash
   npm install
   ```

5. Start the local development server:

   ```bash
   npm run dev
   ```

6. Open the local URL printed in the terminal (usually http://localhost:5173).

## Other commands

```bash
npm run build    # Create a production build in dist/
npm run preview  # Preview the production build locally
```

## Included

- Sample music library with search
- Mood filters
- Simulated playback controls and progress
- Favourites
- Animated visualizer

## Demo-only behaviour

All tracks and playback states are sample data. Playback is simulated; no audio is streamed. There is no login, Spotify connection, Firebase, API, database, server, or credential requirement. No environment variables are needed.

This repository intentionally contains only the frontend demo.
