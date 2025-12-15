# Recap.fit — Your Year in Motion

A beautiful, privacy-focused fitness year-in-review that connects to your Strava data.

## Features
- Visualize your 2025 fitness journey
- Fully client-side — your data never touches our servers
- Beautiful animated story-style cards
- Deep insights: streaks, best month, time preferences, and more
- Contextual comparisons (e.g., "SF to NYC", "Climbing Everest")

## How It Works
Users provide their own Strava API credentials. All data processing happens in the browser.

## Setup Your Own
1. Fork this repo
2. Enable GitHub Pages (Settings → Pages → Deploy from main branch)
3. Update the `CNAME` file with your domain (or delete it to use github.io)
4. Visit your site and follow the onboarding to connect Strava

## Privacy
- Your Strava API credentials are stored only in your browser's localStorage
- Your fitness data is fetched directly from Strava to your browser
- No data is ever sent to any server

## License
MIT
